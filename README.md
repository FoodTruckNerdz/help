<a id="readme-top"></a>
<div align="center">
  <a href="https://github.com/FoodTruckNerdz/help/graphs/contributors"><img src="https://img.shields.io/github/contributors/FoodTruckNerdz/help.svg?style=for-the-badge" alt="Contributors"></a>
  <a href="https://github.com/FoodTruckNerdz/help/network/members"><img src="https://img.shields.io/github/forks/FoodTruckNerdz/help.svg?style=for-the-badge" alt="Forks"></a>
  <a href="https://github.com/FoodTruckNerdz/help/stargazers"><img src="https://img.shields.io/github/stars/FoodTruckNerdz/help.svg?style=for-the-badge" alt="Stargazers"></a>
  <a href="https://github.com/FoodTruckNerdz/help/issues"><img src="https://img.shields.io/github/issues/FoodTruckNerdz/help.svg?style=for-the-badge" alt="Issues"></a>
  <a href="https://docs.foodtrucknerdz.com/help/latest/"><img src="https://img.shields.io/badge/Docs-FoodTruckNerdz-blue?style=for-the-badge" alt="Docs | FoodTruckNerdz"></a>
  <a href="https://github.com/FoodTruckNerdz/help/actions/workflows/encoding-guard.yml"><img src="https://github.com/FoodTruckNerdz/help/actions/workflows/encoding-guard.yml/badge.svg" alt="Encoding guard CI"></a>

  <h1 align="center">FoodTruckNerdz Help Center</h1>

  <p align="center">
    The Help site and help docs for users.
    <br />
    <br />
    <a href="https://help.foodtrucknerdz.com">Visit site</a>
    &middot;
    <a href="https://github.com/FoodTruckNerdz/help/issues">Report Bug</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About The Project

This repository contains the customer-facing help documentation for FoodTruckNerdz.

Canonical readme source: [README.adoc](README.adoc).

### Structure

- **Astro + Starlight**: Landing page at root (`help.foodtrucknerdz.com`) and documentation at `/docs` (`help.foodtrucknerdz.com/docs`)
- **Antora Docs**: `docs/` component on [FTN Docs](https://docs.foodtrucknerdz.com/help/latest/) via the [`FoodTruckNerdz/docs`](https://github.com/FoodTruckNerdz/docs) Antora playbook

### Documentation

- **Public Site**: `help.foodtrucknerdz.com` (landing) and `help.foodtrucknerdz.com/docs` (Starlight docs)
- **Contributor docs**: [Developing guide](https://docs.foodtrucknerdz.com/help/latest/developing/) (local setup, allow-list `.gitignore`) and [changelog](https://docs.foodtrucknerdz.com/help/latest/changelog/) on FTN Docs

## Getting Started

```bash
pnpm install
pnpm dev
pnpm build
```

## Contact

Food Truck Nerdz — support@foodtrucknerdz.com

Project Link: https://github.com/FoodTruckNerdz/help

Site: https://www.foodtrucknerdz.com/

<p align="right">(<a href="#readme-top">back to top</a>)</p>
