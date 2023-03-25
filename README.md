# What this project is?

This is a follow along with modification of Mark Winterbottom and Brooke Rutherford's Udemy course, "Build a Backend REST API with Python & Django - Advanced".

## Personal notes

Essentially a linter:

```bash
docker-compose run --rm app sh -c "flake8"
```

Starts a project in the /app directory:

```bash
docker-compose run --rm app sh -c "django-admin startproject app ."
```

Run the application:

```bash
docker-compose up
```
