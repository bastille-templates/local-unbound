# local-unbound
Local Unbound (DNS integreted System FreeBSD)

## Now apply template to container
```sh
bastille create unbound 14.1-RELEASE YourIP-Bastille
bastille bootstrap https://github.com/bastille-templates/local-unbound; bastille template unbound bastille-templates/local-unbound
```
