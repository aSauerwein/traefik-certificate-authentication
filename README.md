# traefik-certificate-authentication

use traefik as kubernetes ingress for certificate authentication and use header to forward certificate details to the backend

## setup
* traefik ingress controller
* letsencrypt certificate for webserver
* [webhook.site](https://github.com/webhooksite/webhook.site/tree/master/kubernetes) for testing

## links
https://github.com/webhooksite/webhook.site/tree/master/kubernetes
https://doc.traefik.io/traefik/middlewares/http/passtlsclientcert/
https://doc.traefik.io/traefik/https/tls/#client-authentication-mtls