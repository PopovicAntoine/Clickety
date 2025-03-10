# Clickety
# Apothéose DevOps
**Durée :** 14 jours
**Objectifs :**
Mettre en production une application full stack avec une architecture trois tiers, sécurisée et supervisée, avec un serveur pour le front, un pour le back et un pour la bdd.
**Attendus** (par ordre de priorité) **:**
1. [Ansible](https://docs.ansible.com/ansible/latest/getting_started/index.html)
2. [Terraform](https://developer.hashicorp.com/terraform?product_intent=terraform)
3. [Github actions](https://docs.github.com/fr/actions)
4. Supervision de l’infrastructure [Grafana](https://grafana.com/docs/) / [Prometheus](https://prometheus.io/docs/introduction/overview/)
5. Containers en production [K8S](https://kubernetes.io/fr/docs/home/)
6. Reverse proxy et load balancer [Traefik](https://doc.traefik.io/traefik/contributing/documentation/) / [Caddy](https://caddyserver.com/docs/)
7. [Sonarqube](https://docs.sonarsource.com/sonarqube-server/latest/) et intégration des vérifications dans les github actions
**Détails :**
- La partie dev n’est pas la plus importante. Vous pouvez partir de template vite pour le front et d’un CMS au choix pour le backend (Wordpress, Directus, Pocketbase…).
  - [Doc vite](https://vite.dev/guide/#scaffolding-your-first-vite-project)
  - [Wordpress](https://wordpress.org/documentation/)
  - [Directus](https://docs.directus.io/getting-started/quickstart.html)
  - [Pocketbase](https://pocketbase.io/docs/)
- En cas de modification du code (à minima le frontend), un workflow github action doit le répercuter en production.
- En parallèle de la production applicative, une supervision des serveurs est à mettre en place, avec si possible un sonarqube en plus.
- Les serveurs linux doivent être configurés de façon restrictive pour éviter toute compromission : droits d’accès, firewall, ssl…
**Cerise sur le gâteau :**
- Automatisation complète de la livraison en production from scratch.
- Communication entre le front et le back via une API.
- Empaqueter un environnement de développement pour l’équipe de dev.
**Documents :**
- [Référentiel Emploi Activités Compétences](REAC.pdf)
- [Référentiel évaluation](RE.pdf)
