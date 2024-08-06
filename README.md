# What is this?

[![Release](https://github.com/jacobsfederal/Collector-SonarQube-IB/actions/workflows/collect.yml/badge.svg?branch=main)](https://github.com/JacobsFederal/Collector-SonarQube-IB/actions/workflows/collect.yml)

This is a project that automatically collects artifacts to ease in air-gapped transfer from the internet.

It runs actions manually or on Push and creates a release.

In this case, it collects the source code repositories and the associated container images via skopeo for:

- dso.mil IronBank SonarQube Scanner CLI Hardened container image
- Docker Hub SonarQube Scanner CLI Container image
