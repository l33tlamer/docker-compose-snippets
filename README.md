# Docker Compose snippets

This is nothing but just a collection of **Docker Compose** snippets for services i use often.

As example, for a new selfhosted project i need a **MariaDB** container, or **Postgres**, then i just copy/paste the snippet and adjust the values.

Most of these have been set up to have working healthchecks. Ideally you would combine them with "depends_on" with "condition: service_healthy".

These are **NOT** meant to be just copy/pasted and run. They need to be adjusted to fit your own setup.

**Basic Docker and Compose knowledge is required.**
