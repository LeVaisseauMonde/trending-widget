# ◈ Widget Tendance Blogger

> Générez un widget "En tendance" personnalisable pour Blogger — gratuit, prêt à coller

[![Live](https://img.shields.io/badge/LIVE-Essayer_l'outil-c8ff00?style=flat-square&labelColor=0a0a0a)](https://levaisseaumonde.github.io/trending-widget/)
[![BlackCrow](https://img.shields.io/badge/BlackCrow_OS-Hub-333?style=flat-square&labelColor=0a0a0a)](https://levaisseaumonde.github.io/BlackCrow/)

---

## Fonctionnalités

- Créer un widget "En tendance" pour la sidebar Blogger
- Personnaliser titre, image, lien, couleurs, tailles
- Prévisualisation en temps réel
- Générer le code HTML/CSS prêt à copier-coller
- Aucune dépendance externe — le widget généré est autonome

---

## Utilisation

1. Ouvrir [l'outil](https://levaisseaumonde.github.io/trending-widget/)
2. Renseigner l'URL de l'article, le titre et l'image
3. Personnaliser l'apparence
4. Copier le code HTML généré
5. Coller dans un gadget HTML/JavaScript de Blogger

Aucun compte requis. Aucune pub.

---

## Intégration BlackCrow OS

Cet outil fait partie de la suite [BlackCrow OS](https://levaisseaumonde.github.io/BlackCrow/), l'interface système de l'univers [Le Vaisseau-Monde](https://www.vaisseau-monde.fr).

La navbar est chargée dynamiquement depuis le hub central :

```html
<div id="bc-navbar"></div>
<script>
  fetch('https://levaisseaumonde.github.io/BlackCrow/navbar.html')
    .then(r => r.text())
    .then(html => document.getElementById('bc-navbar').innerHTML = html);
</script>
```

---

## Liens

- 🌐 [vaisseau-monde.fr](https://www.vaisseau-monde.fr)
- 📺 [YouTube @VaisseauMonde](https://www.youtube.com/@VaisseauMonde)
- 🔗 [BlackCrow OS](https://levaisseaumonde.github.io/BlackCrow/)

---

*QLVVP 🖤*
