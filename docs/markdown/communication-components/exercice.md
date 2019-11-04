<!-- .slide: class="sfeir-bg-pink exercice" -->
## Exercice 
<ul>
    <li>Dans un dossier composant, créer un monoficher CarPanel.vue qui prend en propriéte person</li>
    <li>Copier le htmp et css dupliquer dans Home.vue et People.vue</li>
    <li>Utiliser card panel dans Home.vue et People.vue en lui passant une person</li>
</ul>
Notes: 
 - pour people utiliser la directive v-for sur le composant pour le répéter ;)

##==##

<!-- .slide: class="sfeir-bg-blue exercice" -->
## Solution
<span class="full-center">localhost:8080/step09_solution</span>

##==##

<!-- .slide: class="sfeir-bg-pink exercice" -->
## Exercice
<ul>
    <li>Sur l'icon trash du composant card panel, créer un event click</li>
    <li>Au click propager un event qui s'appelle person-delete</li>
    <li>A l'écoute de cet evenement, le composant People doit supprimer une personne</li>
    <li>A l'écoute de cet evenement, le composant Home doit changer de personne</li>
</ul>
Notes: 
 - api a appeler pour le delete: http://localhost:9000/api/peoples/:id => renvoie une liste de personnes mise à jour

 ##==##

 <!-- .slide: class="sfeir-bg-blue exercice" -->
 ## Solution
<span class="full-center">localhost:8080/step10_solution</span>