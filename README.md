# Pangolin

## Comandos para instalar el script:

```
$ curl -fsSL https://static.pangolin.net/get-installer.sh | bash

$ sudo ./installer
```
<br>

NOTA. Mira antes la versión actual: https://docs.fossorial.io/Getting%20Started/quick-install

<br>


## Instalar con docker compose:

Reemplaza estos valores antes de iniciar:

pangolin.example.com - con el nombre de host de su panel de control

example.com - con su dominio base

replace-with-a-long-random-secret - con un fuerte secreto aleatorio

admin@example.com - en traefik_config.yml - tu correo electrónico de Let's Encrypt

-----------------------------------

Genera un secreto con el comando : openssl rand -hex 32

-----------------------------------

Login:

email: "admin@example.com" 
        
password: "Password123!"





