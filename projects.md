---
layout: page
title: 🚀 Mes Projets
permalink: /projects/
order: 3
---

Bienvenue dans ma galerie de projets.
Cette page regroupe mes travaux réalisés dans le cadre de mon cursus à **Epitech**, ainsi que des projets personnels.


---

## 🌐 Projets Web

 * #### **[Klivio →](https://lucky-jhd13.github.io/Klivio/)**
> Plateforme de formation en ligne.

C'est un projet personnel complet axé sur le front-end. L'objectif était de créer une interface utilisateur propre et responsive sans utiliser de frameworks, pour maîtriser les bases.

**Technologies utilisées :**
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

---

## 🛠 Projets Epitech & Techniques

Voici les projets réalisés en interne, documentés sur ce portfolio.

{% for project in site.projects %}
### 📂 [{{ project.title }}]({{ project.url | relative_url }})

> {{ project.description }}

[Voir les détails du projet →]({{ project.url | relative_url }})

 {% endfor %}

---

*D'autres projets sont en cours de développement et arriveront bientôt sur cette page !*