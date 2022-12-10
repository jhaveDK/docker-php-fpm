[Permissions](syncronize-file-permissions.md) |
[Tags](docker-tags.md) |
[Architectures](supported-architectures.md) |
[Versions](php-versions.md) |
Flavours |
[Extensions](php-modules.md) |
[Tools](available-tools.md) |
[Env Vars](docker-env-variables.md) |
[Volumes](docker-volumes.md) |
[Base Images](base-images.md)

---

<h2><img name="Documentation" title="Documentation" width="20" src="https://github.com/devilbox/artwork/raw/master/submissions_logo/cytopia/01/png/logo_64_trans.png"> Documentation</h2>



### Flavours

#### Image: base

Generic PHP-FPM base image. Use it to derive your own php-fpm docker image from it and add more extensions, tools and injectables.<br/><sub>(Does not offer any environment variables except for `NEW_UID` and `NEW_GID`)</sub>

#### Image: mods

Generic PHP-FPM image with fully loaded extensions. Use it to derive your own php-fpm docker image from it and add more extensions, tools and injectables.<br/><sub>(Does not offer any environment variables except for `NEW_UID` and `NEW_GID`)</sub>

#### Image: prod

Devilbox production image. This Docker image comes with many injectables, port-forwardings, mail-catch-all and user/group rewriting.

#### Image: work

Devilbox development image. Same as prod, but comes with lots of locally installed tools to make development inside the container as convenient as possible. See [Integrated Development Environment](../README.md#integrated-development-environment) for more information about this.