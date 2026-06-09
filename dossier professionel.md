# Présentation du Projet Mafeliki
## Réaliser des interfaces utilisateur statiques web ou web mobile

---

## 🎯 Présentation générale

Bonjour, je m'appelle [Votre nom], et je vous présente mon projet web que j'ai réalisé : **Mafeliki - Les fruits et légumes de Mayotte**.

J'ai créé un site statique qui met en avant les produits agricoles de Mayotte. C'est un site informatif et commercial qui présente les fruits et légumes locaux, ainsi qu'un annuaire de producteurs.

---

## 📱 Structure du site

### L'en-tête
Ici, je place un header en haut de la page avec la balise `<header>` pour créer une section hautement identifiable. Je mets le titre "Mafeliki les fruits et légumes de Mayotte" avec une balise `<h2>` pour qu'il soit lisible. 

Ensuite, j'applique un dégradé de couleurs vertes avec du CSS - je fais un `background: linear-gradient(135deg, #4CAF50, #2E7D32)` pour créer cet effet visuel attractif qui parle aux fruits et légumes.

### La navigation
Je crée une barre de navigation avec la balise `<nav>` et une liste `<ul>` avec trois liens : Fruit, Légume et Formulaire. 

Pour les rendre plus dynamiques, j'ajoute une animation CSS : je mets un `::after` sur chaque lien qui crée une ligne jaune qui se remplit au survol. J'utilise `transition: 0.3s` pour que ce soit fluide et agréable à l'œil.

---

## 📄 Les articles

### La section Légume
Je crée un `<article>` avec l'id "legume" pour pouvoir le cibler depuis la navigation. 

Je mets un titre avec `<h2>Légume</h2>` et une explication : "Un légume est la plante ou la partie d'une plante comestible..."

Ensuite, je place une image avec la balise `<img src="Manioc.jpg" alt="Manioc">`. J'utilise l'attribut `alt` pour la description, c'est important pour l'accessibilité et le SEO.

Je mets le prix "5€ le kilo" et une description détaillée du manioc avec un paragraphe `<p>`.

### La section Fruit
Je fais exactement la même structure avec un autre `<article>` id="fruit".

Je mets le titre, l'explication générale sur les fruits, puis mon image `<img src="fruit à pain.jpg" alt="Fruit à pain" width="250">`. Ici, j'ajoute un attribut `width="250"` pour contrôler la taille de l'image.

Je mets le prix "3€" et la description du fruit à pain.

---

## 🔗 Les éléments additionnels

### Le lien Facebook
Je mets un lien vers la page Facebook avec `<a href="..." target="_blank">`. L'attribut `target="_blank"` est important car il ouvre le lien dans un nouvel onglet sans quitter mon site.

Je place ce lien dans une `<div class="facebook">` pour pouvoir le styliser avec du CSS.

### Le tableau des producteurs
Je crée un tableau avec la balise `<table>` pour afficher les producteurs locaux. 

Je mets une ligne d'en-têtes avec `<tr><th>` : Nom, Prénom, Entreprise, Type de produit, Village.

Ensuite, je remplis les données avec plusieurs lignes `<tr><td>` contenant les informations des producteurs.

---

## 🎨 Le style CSS

### Réinitialisation générale
Je commence par réinitialiser tous les styles par défaut du navigateur avec :
```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}
```

### Le header
J'applique un dégradé de vert `linear-gradient(135deg, #4CAF50, #2E7D32)` pour un effet moderne et professionnel. J'ajoute du padding, du texte blanc et une bordure inférieure épaisse en vert foncé.

### La navigation
Je transforme la liste en `display: flex` pour que les liens s'affichent horizontalement. J'ajoute un `gap: 40px` pour espacer les éléments.

Pour chaque lien, j'utilise `text-decoration: none` pour enlever le soulignement par défaut, et je change la couleur en vert.

### L'effet au survol
Je crée un pseudo-élément `::after` invisible au départ (width: 0%) qui se remplit (`width: 100%`) quand on passe la souris dessus (`:hover`). Cet effet anime une barre jaune sous le texte, ce qui rend l'interface interactive et professionnelle.

---

## ✅ Fonctionnalités

✔️ **Site responsive** : J'ai mis la balise `<meta name="viewport" content="width=device-width, initial-scale=1.0">` pour que le site s'adapte à tous les appareils (téléphone, tablette, ordinateur).

✔️ **Accessibilité** : J'utilise les bonnes balises sémantiques (`<header>`, `<nav>`, `<article>`, `<section>`), j'ajoute des attributs `alt` sur mes images.

✔️ **Navigation fluide** : Les liens permettent de naviguer facilement entre les sections avec des ancres (`#fruit`, `#legume`).

✔️ **Design moderne** : Dégradés, animations au survol, espacement bien pensé.

---

## 🛠️ Technologie utilisée

- **HTML5** : Pour la structure sémantique du site
- **CSS3** : Pour le design, les dégradés, les animations et la responsivité
- **Images** : Intégrées localement (Manioc.jpg, fruit à pain.jpg)

---

## 💡 Conclusion

Ce projet démontre ma capacité à créer une interface utilisateur statique attrayante et fonctionnelle. J'ai su structurer le contenu de manière logique, appliquer des styles modernes et créer une expérience utilisateur agréable. Le site est simple à maintenir et peut facilement être étendu avec des fonctionnalités dynamiques à l'avenir.
