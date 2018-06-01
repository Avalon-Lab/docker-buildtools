# docker-buildtools

Images dockers de nos différents build tools pour les plateformes de CI/CD (GitLab entre autre).
  
Ces images sont stockées sur le registry GitLab : https://gitlab.com/avalon-lab/oss/docker-buildtools/container_registry
  

## Polymer 2
Cette image docker permet de construire des projets Polymer 2, elle permet aussi de générer des certificats ssl Let's Encrypt grâce à https://github.com/rolodato/gitlab-letsencrypt (utile notament pour les Gitlab Pages en HTTPS avec un nom de domaine custom).

*Informations techniques :*  

- Node.js : 9.11.1
- npm : 6.1.0
- Polymer CLI : 1.7.2
- Bower : 1.8.4
- gitlab-letsencrypt : 3.1.1  

Pour récupérer cette image : 
```
docker pull registry.gitlab.com/avalon-lab/oss/docker-buildtools/polymer2:latest
```
