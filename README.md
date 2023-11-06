# Email Verification Demonstration in Laravel

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

EN: A simple demonstration project that showcases how to implement email verification in a Laravel application.

PT: Um simples projeto de demonstração de como implementar a verificação por email em uma aplicação laravel.

## Table of Contents

- [Features/Funcionalidades](#features)
- [Requirements/Requisitos](#requirements)
- [Files/Arquivos](#Files)

## Features

EN:
- User registration with email verification.
- Sending of verification emails.
- Sending of password recovery emails.

PT:
- Registro de usuário com verificação de email.
- Envio de emails de verificação.
- Envio de emails de recuperação de senha.

## Requirements

EN:
- This project uses laravel/ui

PT:
- Este projeto usa laravel/ui

## Files

EN:
- In routes/web.php a line was added to make verify available to use.
- Since I was using npm for reverse proxy, I added the npm container's IP to TrustProxies.
- In app/User/Models I added "MustVerifyEmail" namespace and interface to user class.

PT:
- No arquivo routes/web.php, uma linha foi adicionada para tornar o "verify" disponível para uso.
- Como eu estava usando o npm como proxy reverso, adicionei o IP do contêiner npm à lista de TrustProxies.
- Na pasta app/User/Models, adicionei o namespace "MustVerifyEmail" e a interface à classe de usuário.