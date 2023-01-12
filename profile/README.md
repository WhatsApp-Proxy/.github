# Hi there 👋

## This is the home for the [WhatsApp-proxy.com](https://whatsapp-proxy.com/) website

This GitHub organization hosts:

- Front-end web-app
- Back-end
- Discovery server for proxies

## Hosting your own proxy

Hosting your own proxy is fairly easy:

- Clone `https://github.com/WhatsApp/proxy/`
- Change the `CA_SUBJECT` and `SSL_SUBJECT` with something random in the `generate-certs.sh` file (located in `proxy/src`)
- Run `docker-compose up -d` in the `proxy/ops` folder

If you want your proxy to show up on our website, create an issue [here](https://github.com/WhatsApp-Proxy/whatsapp-proxies-web/issues/new/choose). Be sure to host our [Discovery Server](https://github.com/WhatsApp-Proxy/discovery-server), which makes it easier for users to ping your server when using our webapp. :) A discovery key is not needed when creating an issue.
