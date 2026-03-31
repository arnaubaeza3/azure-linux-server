# Azure Linux Server

Servidor Linux desplegado en Microsoft Azure con nginx, dominio propio y HTTPS.

## Stack
- Microsoft Azure (VM Ubuntu)
- nginx como servidor web
- Let's Encrypt + Certbot para TLS/HTTPS
- DNS con registro A apuntando a IP pública

## Qué se hizo
- Creación y configuración de VM Ubuntu en Azure
- Apertura de puertos 80/443 en Network Security Group
- Instalación y configuración de nginx
- Configuración de dominio personalizado (arnauserver.me) via DNS
- Certificado SSL gratuito con Let's Encrypt
- Gestión remota via SSH

## Resultado
Web en producción: [arnauserver.me](https://arnauserver.me)
