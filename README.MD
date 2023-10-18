<h2>Compte rendu pour réaliser en atlier sur traitement automatique du language NLP</h2>
<h3>Partie 1 : Pré-traitement de texte </h3>
<p>On considère le corpus des textes suivant :
=&quot; Le chat dort sur le tapis.&quot;   ; =&quot; Les Oiseaux Chantent Le Matin. &quot; ; = &quot; Le chien court
dans le jardin. &quot;  ; = &quot; Mangeons des pommes délicieuses.&quot; ; = &quot;Je mange une orange
fraîche.&quot;</p>
<ul>
    <li>1. Créer un corpus qui contient les textes :</li>
    <img src="./img/img01.png"/>
    <li>2. Convertir le corpus en type DataFrame :</li>
<img src="./img/img02.png"/>
    <li>3. Quelles sont les différentes approches pour prétraiter un corpus de textes ? Décrire les :</li>

<ul>
    <li><h3>Minuscules</h3> : Convertir tous les caractères en minuscules pour éviter les duplications dues à la casse.</li>
    <li><h3>Tokenisation</h3> : Diviser le texte en mots ou en phrases (token).</li>
    <li><h3>Suppression des caractères spéciaux et de la ponctuation</h3> : Supprimer les caractères qui ne sont pas des lettres ou des chiffres.</li>
    <li><h3>Suppression des stopwords : </h3> : Supprimer les mots courants (comme 'le', 'la', 'et') qui ne portent pas beaucoup de sens.</li>
    <li><h3>Lemmatisation et Stemming : </h3> : Réduire les mots à leur forme de base (par exemple, "mangeons" devient "manger").</li>
</ul>

    <li>BiDirectional Streaming Model</li>
</ul>





<img src="pictures/Model1/img01.png">
<img src="pictures/Model1/img03.png">
<img src="pictures/Model1/img04.png">
<img src="pictures/Model1/img05.png">
<img src="pictures/Model1/img06.png">
<img src="pictures/Model1/img07.png">
