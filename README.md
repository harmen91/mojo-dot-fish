# MOJO [DOT] FISH

Personal portfolio website, currently a work in progress.

---

> Setting up nginx proxy manager explained here
> https://github.com/harmen91/nightscout-docker-simple

> Serving a static website using php:apache docker container explained here
> https://github.com/harmen91/jeandorie-website

## Steps

1. clone this repo 

```
https://github.com/harmen91/mojo-dot-fish.git
```

2. create .env file in the root of the project with one line (change port number): 

```
PHP_PORT=1234
```

3. run docker container

```
docker compose up -d
```

4. configure nginx proxy manager (see links above)

5. update website

```
git pull && docker compose restart mojo-dot-fish
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

