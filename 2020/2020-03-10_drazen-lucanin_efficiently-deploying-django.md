# Efficiently deploying Django

## Dražen Lučanin

## Summary

Have you ever thought how long it takes to start a new Django project? Getting tired of fiddling with Django settings every time to get static files, media files, Celery etc. all working on Heroku? Maybe you even had to self-host a Django app and fall down the rabbit hole of nginx configs, gunicorn / uwsgi, systemd / supervisor, domain mapping, Let’s encrypt TLS certificate settings? Maybe you were a part of a project once where someone started down the innocent path of introducing something like Ansible / Chef / Salt to automate the process?

Before you realize it, you’re no longer a hip developer sipping your cappuccino while crafting elegant API endpoints. No, you’re spending long nights under the glare of your screen, the terminal staring back at you while you’re digging through obscure log files of things you didn’t know existed to figure out why that CSS file is 404-ing. You’re no longer a developer, you’re a sysadmin! If mere thoughts of these experiences are giving you chills, then this talk is for you.

What we’ll cover in this talk is the twelve-factor app methodology which gives answers to many of the problems we’ve mentioned. We won’t stay on a theoretical level, however – we’ll go through a practical Django template showing you exactly how you can use the methodology in practice! Furthermore, we’ll show how to deploy a real Django web app to both Heroku and a self-hosted virtual machine using Dokku – from the same codebase. Remove the stress of starting new Django projects, make that family culinary recipe web app you’ve been meaning to for so long and become a happier developer and a happier cook!

### Resources

- [slides](https://speakerdeck.com/metakermit/efficiently-deploying-django)

## About Speaker

Dražen is a software developer and data analyst working in [Punk Rock Dev](https://punkrockdev.com/). He tweets as [@metakermit](https://twitter.com/metakermit).
