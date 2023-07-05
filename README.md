# docker-compose-snippets

This is nothing but just a collection of docker-compose snippets for services i need to use often.

For example a new selfhosted project i need a mariadb container,or postgres, then i just copy/paste from the snippet and into the actual project.

Most of these have been set up to have working healthchecks and i use autoheal to check on that, automatically restart unhealthy containers and notify me.

I typically have a permanent docker network named 'dockernet' for default services, thats where the reference comes from, obviously needs to be adjusted.

These are NOT meant to be just copy/pasted and run. They need to be adjusted to fit whatever stack you are using. Basic Docker knowledge is required.

Most of these have my default labels on them, they are for the following tools:

* https://github.com/willfarrell/docker-autoheal (i made a modified version with Pushover notification support)  
  https://github.com/users/l33tlamer/packages/container/package/autoheal-pover

* https://github.com/crazy-max/diun

* https://github.com/petersem/monocker
