# MOJO [DOT] FISH

Personal portfolio website, currently a work in progress.

---

## Overview

Mounts a local `site/` folder directly into the official `php:apache` container and serves it with Apache. No custom image, no build step, no scripts. To deploy or update the site, clone or pull this repository on your VPS and restart the container.

---

## Prerequisites

- A Linux VPS with Docker and Docker Compose installed
- A domain or subdomain pointed at your VPS IP
- Nginx Proxy Manager running on your VPS

> Setting up nginx proxy manager explained here
> https://github.com/harmen91/nightscout-docker-simple

> Serving a static website using php:apache docker container explained here
> https://github.com/harmen91/jeandorie-website

create .env file with one line, choose a different port: 

```
PHP_PORT=1234
```
---

## Repository Structure

```
mojo-dot-fish/
├── wip-site/               # Static PHP mojo[dot]fish placeholder work in progress website
│   ├── index.php
├── docker-compose.yml
└── README.md
```

