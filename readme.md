# Family Tree

Website for managing and displaying your family tree through generations

## Environnement de développement

### Pré-requis

* PHP 8.0.2
* Composer
* Symfony CLI
* Docker
* Docker-compose

Vous pouvez vérifier les pré-requis (sauf Docker et Docker-compose) avec la commande suivante (de la CLI Symfony) :

```bash
symfony check-requirements
```

### Lancer l'environnement de développement

```bash
docker-compose up -d
symfony serve -d
```

En alternative (prob. sous Windows 10)

```bash
docker-compose up --build
symfony serve
```