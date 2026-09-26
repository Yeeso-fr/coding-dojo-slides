---
theme: yeeso
title: "Coding dojo yeeso : redécouvrir la coopération"
highlighter: shiki
drawings:
  persist: false
transition: slide-left
mdc: true
layout: cover
---

<div class="subtitle">Coding dojo yeeso</div>

# Redécouvrir la <span class="highlight">coopération</span>

Atelier de mob programming

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: intro
---

**Manon Carbonnel**

- Développeuse et intégratrice web
- Facilitatrice Agile
- Animatrice chez <a target="_blank" href='https://mobilizon.fr/@dev_en_equipe' title="Mob Prog FR - lien externe">MobProgFR</a>
- <a target="_blank" href='https://bento.me/manoncarbonnel' title="Site web de Manon - lien externe">bento.me/manoncarbonnel</a>

---
layout: three-cols-header
---

# Tour de table

::left::
## Qui es-tu ?

Ton prénom, et tes pronoms si tu le souhaites

::center::
## Ton rapport au code

Débutant·e, confirmé·e, curieux·se, en reconversion…

::right::
## Une anecdote

Ton premier souvenir avec un ordinateur

<!--
Une minute maximum par personne. On commence par l'animatrice pour donner l'exemple.
-->

---
transition: slide-up
---

# C'est quoi le mob programming ?

|     |     |
| --- | --- |
| ✋ Vous avez déjà entendu parler de la pratique  | <Counter :count="0" /> |
| <v-click>✋ Vous avez déjà pratiqué </v-click> | <Counter :count="0" /> |

<br/>

<v-click>

Le développement en équipe (<span lang="en">mob</span> ou <span lang="en">ensemble programming</span> ou <span lang="en">Software Teaming</span>) c'est rassembler

<span class="highlight">toutes les personnes</span> nécessaires
au succès d'<span class="highlight">une tâche</span>
autour d'<span class="highlight">un seul poste de travail</span>.

</v-click>

---

# Vos attentes

```md {monaco}
Pourquoi êtes-vous ici ?

- 
- 
- 
-
-

Vous avez envie de repartir avec :

- 
- 
- 
-

```

---
layout: quote
transition: slide-up
---

Pour qu'une idée arrive dans le code, elle doit passer par le cerveau de quelqu'un d'autre.

Llewellyn Falco

---
layout: center
transition: slide-up
---

# Le kata

On le <span class="highlight">choisit ensemble</span> !

---
layout: image-right
image: /mob-andrea-zuill.webp
transition: slide-up
---

# Rôles

---

# <span lang="en">Driver</span> ou traducteur·ice

Personne au clavier

- Ne décide pas
- Implémente du mieux qu'iel peut
- Pose des questions pour clarifier

ℹ️ Aucune initiative.

---

# <span lang="en">Navigator</span> ou co-pilote

Extrait la connaissance de l'équipe

- Explique l'intention au <span lang="en">driver</span>
- Au plus haut niveau possible
- Jusqu'à l'explication des touches

ℹ️ Sélectionne une idée du groupe.

<v-click>

Par exemple :

```md {monaco}
1 - « Peux-tu écrire un test pour le cas Buzz ? »
2 - « Écris un test qui vérifie que quand on appelle la fonction avec le nombre 5 on retourne "Buzz" »
3 - « Tu peux dupliquer le bloc de code entre la ligne 17 et 23, et changer les valeurs ligne 18 et 22 »
```
</v-click>

---

# <span lang="en">Mobber</span> ou équipier·ère

- Proposer des idées
- Soutenez les idées des autres
- Lâchez prise
- Parlez au bon moment

ℹ️ Cherche comment aider, ou écoute attentivement.

---
layout: quote
transition: slide-up
---

Le but n’est pas de faire de l’art, c’est d’être dans cet état merveilleux qui rend l’art inévitable.

Robert Henri

---
transition: slide-up
layout: image-right
image: /psychological-safety.webp
---

# Sécurité psychologique

Partez du principe que nous sommes toustes très compétents et compétentes.

<v-click>

- Droit à l’erreur
- Partager ses échecs
- Favoriser la parole des personnes moins privilégiées
- Esprit de soutien et entraide
- Écoute active
- Laisser son ego de côté
- Évite l'aide infligée

</v-click>

<small>Amy Edmondson & Aristote project</small>

---

# TDD - Développement guidé par les tests

|                                                |                        |
|------------------------------------------------|------------------------|
| ✋ Vous avez déjà entendu parler de la pratique | <Counter :count="0" /> |
| <v-click> ✋ Vous avez déjà pratiqué </v-click> | <Counter :count="0" /> |

<v-click>

3 phases du cycle
1. Rouge (test simple qui échoue)
2. Vert (solution la plus facile)
3. <span lang="en">Refactor</span> (plus propre si nécessaire)

</v-click>

---

# Disclaimer

- On ne finira pas l'exercice de code
- On ne codera pas comme vous l'auriez fait seul·e

<v-click>

Mais <span class="highlight">c'est pas grave</span>, avancer ensemble et s'amuser c'est plus important.

</v-click>

---
transition: slide-up
---

# Bilan de vos attentes

```md {monaco}
Vous avez validé :

- 
- 
- 
-

Vous auriez aimé repartir avec :

- 
- 
- 

```

---
layout: section
index: "+"
---

# Bonus

Des petits liens cool

---
layout: two-cols
---

## <span lang="en">Ensemble Toolbox</span>

Facilitez vos sessions de travail en équipe

<Youtube id="c_oW0yJWveQ" width="100%" height="250px" />

::right::

## Ça vaut le coût !

Combien coûte vraiment « ce truc là » ?

<Youtube id="JXs7wNMq5dk" width="100%" height="250px" />

---
layout: center
---

# <span lang="en">Mob Time</span>

Gérer le chrono et la rotation des rôles facilement

<a target="_blank" href="https://mobtime.hadrienmp.fr/" title="Appli Mob Time - lien externe">mobtime.hadrienmp.fr</a>

<small>Une application développée par
  <a target="_blank" href="https://www.linkedin.com/in/hadrien-mens-pellen-39071231" title="Profil LinkedIn de Hadrien Mens Pellen - lien externe">Hadrien Mens Pellen</a> 🐙
</small>

---
layout: end
qrCode: /qrcode-openfeedback.webp
qrCodeLabel: "Votre avis sur OpenFeedback"
qrCodeAlt: "QR code vers le formulaire de feedback OpenFeedback"
---

**Vous étiez au top !**
