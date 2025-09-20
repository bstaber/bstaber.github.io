---
layout: page
permalink: /repositories/
title: software
description:
nav: true
nav_order: 4
---

**Projects I'm currently working on**:

- [rustineers](https://github.com/bstaber/rustineers): A collection of crates to learn Rust with applied sciences. I try to comment and explain my journey in a small [book](https://bstaber.github.io/rustineers/) that goes with it.
- [plaid](https://github.com/PLAID-lib/plaid): An open-source project developped by my colleagues.
- [cppxplorers](https://github.com/bstaber/cppxplorers): A C++ mono-repository playground. There's a [book](https://bstaber.github.io/cppxplorers) I try to fill as well.
- [kernax](https://gitlab.com/drti/kernax): A small JAX-based package that implements kernel methods. I've been refactoring that library a bit.
- [pbnn](https://github.com/bstaber/pbnn): A code that benchmarks UQ methods for neural networks in JAX and PyTorch. I'm cleaning this up as well.
- [Python lecture notes](https://bstaber.github.io/ensai-2a-prog-alg-ml/): Some lecture notes for a lecture I give about implementing algorithms in Python. I'm trying out marp.
- [Marimo notebooks](https://bstaber.github.io/python-ml-tutorials-marimo/): Some notebooks that go along with the lecture notes. Trying to make nice visual examples.

**Experimenting**:

- [uv python monorepo](https://github.com/bstaber/uv-monorepo-example): I made a template for a python mono-repository setup with `uv`. I added all the tools I like to use right now. It can easily be used as a standard repository too.
- [endurance](https://github.com/bstaber/endurance): An example of python playground based on the above template.

**Older stuff**:

- [TrilinosUQComp](https://github.com/bstaber/TrilinosUQComp): A 3D parallel finite element solver I made during my PhD thesis. It relies on [Trilinos](https://trilinos.github.io/) and good old `Epetra` (which is deprecated now). It was my first C++ project, it has several flaws but I was happy with it! Nowadays I would probably use [Spack](https://spack.io/) and rewrite the finite element solvers with [Kokkos](https://github.com/kokkos/kokkos)/[Tpetra](https://trilinos.github.io/tpetra.html).
- [BaTorch](https://gitlab.com/drti/batorch): A code for benchmarking Bayesian neural networks with PyTorch and [Hydra](https://hydra.cc/) We implemented several Bayesian methods for deep neural networks, and kernel-based distances stuff like the maximum mean discrepancy and the kernelized Stein discrepancy. It is outdated but I plan to use Hydra again in another project.

{% if site.data.repositories.github_users %}

## GitHub users

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.liquid username=user %}
  {% endfor %}
</div>

---

{% if site.repo_trophies.enabled %}
{% for user in site.data.repositories.github_users %}
{% if site.data.repositories.github_users.size > 1 %}

  <h4>{{ user }}</h4>
  {% endif %}
  <div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% include repository/repo_trophies.liquid username=user %}
  </div>

---

{% endfor %}
{% endif %}
{% endif %}

{% if site.data.repositories.github_repos %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
