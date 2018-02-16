# ModRefTriplestore
Digital Humanities - Semantic Web - CIDOC-CRM Triplestores - ModRef Project: Modelling, References, Digital Culture - Laboratory Labex "Past in Present" - University of Paris Nanterre, France. See http://modref-labexpassespresent.huma-num.fr . 

<p>
ModRef Project (Modelling, Repository, Digital Culture) is a set of projects 
from laboratory Labex (Laboratory of Excellency, Past in Present: history, 
heritage, remembrance - Laboratoire d'Excellence, Les Passés dans le Présent: histoire, 
patrimoine, mémoires. See http://passes-present.eu/) 
involving several organisms, such as: 
</p>

<ul>
<!-- de l'université de Paris Ouest Nanterre La Défense -->
<li> MoDyCo (Modelling, Dynamic, Corpus) : http://www.modyco.fr/fr/ </li>
<li> BDIC (International Library of Contemporary Documentation - Bibliothèque de la Documentation Internationale Contemporaine) : http://www.bdic.fr/ </li>
<li> MAE (House of Archeology and Ethnology - Maison de L'Archéologie et de L'Ethnologie) : http://www.mae.u-paris10.fr/ </li> 
<li> ArScAn (Archeology and Antique Science - UMR 7041 - Archéologie et Sciences de l'Antiquité) : http://www.mae.u-paris10.fr/arscan/ </li> 
</ul> 

<!-- figuring out or working out  -->
<p>
ModRef goal is to provide Labex's projects with a digital expertise as well as figuring 
out a Proof of Concept (POC) concerning "linked open data" 
and modelling using references, in order to encourage 
discussions over issues related to data migration to the web semantic by creating 
and exploiting "triplestores" (collections or datawarehouses of RDF files). 
The CIDOC-CRM norm (see http://www.cidoc-crm.org/) has been chosen 
since it is currently the reference for the semantic description of museographic or 
cultural heritage data. An OWL implementation of the CIDOC-CRM by the University of 
Erlangen-Nuremberg is available at the following address: http://www.erlangen-crm.org/. 
</p>

<p>
Three projects have been selected for the Proof Of Concept: 
</p> 
<ul>
<li>CDLI (Cuneiform Digital Library Initiative): Digital museum on antique documents in cuneiform writing (see http://www.cdli.ucla.edu) </li>
<li>ObjMythArcheo: Antique archaeological objects with mythological iconography (see http://www.limc-france.fr and http://medaillesetantiques.bnf.fr) </li> 
<li>BiblioNum: Digital library on history of France during the 20th century (see http://www.argonnaute-u.paris10.fr) </li> 
</ul> 

<table border>            
    
    <caption style="caption-side:bottom">
    <b> Table. Comparing data for the Proof Of Concept of ModRef</b>              
    </caption> 
    
    <tr>
       <td>  </td>
       <td class="indication"> <b>CDLI</b> </td>
       <td class="indication"> <b>ObjMythArcheo-LIMC</b> </td>
       <td class="indication"> <b>BiblioNum-BDIC</b> </td>
    </tr> 
    
    <tr>
       <td> <b>Languages</b> </td>
       <td> English </td>
       <td> French-English </td>
       <td> French </td>
    </tr> 
    
    <tr>
       <td> <b>Size (Texts)</b> </td>
       <td> 300 Mo </td>
       <td> 100 Mo </td>
       <td> 100 Mo </td>
    </tr> 
    
    <tr>
       <td> <b>Data Number</b> </td>
       <td> 313 332 objects - 105 000 exposed </td>
       <td> 17 424 objects - 8250 exposed </td>
       <td> 77 collections - 62 392 files </td> 
    </tr> 
    
    <tr>
       <td> <b>Logical Structure</b> </td>
       <td> Database of type spreadsheet </td>
       <td> Relational database </td>
       <td> XML-EAD </td>
    </tr> 
    
    <tr>
       <td> <b>Elements number of logical structure</b> </td>
       <td> 1 table of 61 attributes </td>
       <td> 59 tables </td>
       <td> 146 XML-EAD elements </td>
    </tr>   
      
</table> 

<p>
Moving data into triplestores involves different steps: 
</p>

<ul>
<li>data preparating (study and structural description of data), </li>
<li>data semantic modelling and mapping (or matching or alignment), </li>
<li>creating triplestores - migrating data into triplestores, </li>
<li>publishing and visualizing triplestores, </li>
<li>exploring and querying triplestores 
using general forms and "end point sparql" (interface for sparql queries execution). </li>
</ul> 

<p>Hence, the main issues are (1) moving from non-structured or semi-structured data 
(notebook, books, html) to structured data (spreadsheets, relational databases, XML files) 
and then, (2) moving those structured data into semantic data (RDF files) in order to improve 
the sharing, the exchange and the discovery of new knowledge.  
</p> 

<p>
On the other hand, various projects around the world work on the migration of data into 
triplestores (CIDOC-CRM or not), such as: </p>

<ul>
<li> The <i>British Museum</i> (see http://collection.britishmuseum.org/), 
which is a museum on history and culture located at London (UK) 
and that uses the CIDOC-CRM </li> 
<li> <i>Arches</i> 
(see http://www.getty.edu/conservation/our_projects/field_projects/arches/), 
which is a collaboration between the Getty Conservation Institute (GCI) 
and the World Monuments Fund (WMF) on immovable cultural heritage (monuments, bridges) 
and that uses the CIDOC-CRM </li> 
<li> <i>Biblissima</i> (see http://www.biblissima-condorcet.fr/), which works on french 
written cultural heritage of Middle Age and Renaissance and that uses the CIDOC-CRM </li> 
<!-- --> 
<li> </li>
<li> <i>DBPedia</i> (see http://www.dbpedia.org/sparql), which is an online 
encyclopedia 
and that does not use the CIDOC-CRM norm but various metadata languages, such as: 
dbpedia, foaf, umbel, schema.org, dublin core, geo 
</li>   
<li> <i>Symogih</i> (see http://www.symogih.org/sparql), which works on 
history information 
and that does not use the CIDOC-CRM norm but various metadata languages, such as: 
symogih, example.org, geo 
</li> 
<li> <i>Nakala</i> (see http://www.nakala.fr/sparql), which is a service to store, 
document and publish data 
and that does not use the CIDOC-CRM norm but various metadata languages, such as: 
foaf, skos, dublin core, vcard 
</li> 
<!-- --> 
</ul> 


# ModRefTriplestore FR 

Humanités Numérique- Web Sémantique - CIDOC-CRM Triplestores - Projet ModRef: Modélisation, Références, Culture Numérique - Laboratoire Labex "Les Passés dans le Présent" - Université de Paris Nanterre, France. Voir http://modref-labexpassespresent.huma-num.fr . 

<p>
Le projet ModRef (Modélisation, Référentiels et Culture Numérique) fédère un ensemble de projets du Labex (Laboratoire d'Excellence, Les Passés dans le Présent : histoire, patrimoine, mémoires. Voir http://passes-present.eu/) 
impliquant divers organismes, parmi lesquels : 
</p>

<ul>
<!-- de l'université de Paris Ouest Nanterre La Défense -->
<li> MoDyCo (UMR 7114 - Modèles, Dynamiques, Corpus) : http://www.modyco.fr/fr/ </li>
<li> BDIC (Bibliothèque de la Documentation Internationale Contemporaine) : http://www.bdic.fr/ </li>
<li> MAE (Maison de L'Archéologie et de L'Ethnologie) : http://www.mae.u-paris10.fr/ </li>
<li> ArScAn (UMR 7041 - Archéologie et Sciences de l'Antiquité) : http://www.mae.u-paris10.fr/arscan/ </li>
<!-- mais aussi : CNRS, Universit\'{e} de Paris Ouest Nanterre La D\'{e}fense, 
Mus\'{e}e du Quai Branli, Mus\'{e}e d'Archéologie Nationale, 
BNF Biblioth\`{e}que Nationale de France, ... -->
</ul> 

<p>
ModRef a pour objectif d'apporter une expertise numérique aux différents projets du Labex qu'il fédère en son sein 
ainsi que de proposer une Preuve Conceptuelle (Proof of Concept ou POC) 
autour des questions du "linked open data" et de la modélisation via des référentiels, 
afin d'encourager les débats sur ces problématiques 
de migration de données vers le web sémantique via la création et l'exploitation de 
"triplestores" (collections ou entrepôts de fichiers RDF). La norme CIDOC-CRM 
(cf. http://www.cidoc-crm.org/) a été choisie car elle est actuellement la norme de 
référence pour la description sémantique de données muséographiques ou d'héritage culturel. 
Une implémentation OWL du CIDOC-CRM par l'Université de  
Erlangen-Nuremberg est disponible à l'adresse suivante : http://www.erlangen-crm.org/. 
</p>

<p>
Trois projets ont été sélectionnés pour la phase de Preuve Conceptuelle de ModRef : 
</p>
<ul>
<li>CDLI (Cuneiform Digital Library Initiative) : 
Conservatoire numérique ("musée virtuel") de l'ensemble des documents antiques rédigés 
en écriture cunéiforme (cf. http://www.cdli.ucla.edu) </li>
<li>ObjMythArcheo : Objets antiques archéologiques à iconographie mythologique (cf. http://www.limc-france.fr et http://medaillesetantiques.bnf.fr) </li> 
<li>BiblioNum : Bibliothèque numérique sur l'histoire de France du 20ième siècle (cf. http://www.argonnaute-u.paris10.fr) </li> 
</ul>

<table border>            
    
    <caption style="caption-side:bottom">
    <b> Table. Comparaison des données des projets de la Preuve Conceptuelle de ModRef</b>              
    </caption> 
    
    <tr>
       <td>  </td>
       <td class="indication"> <b>CDLI</b> </td>
       <td class="indication"> <b>ObjMythArcheo-LIMC</b> </td>
       <td class="indication"> <b>BiblioNum-BDIC</b> </td>
    </tr> 
    
    <tr>
       <td> <b>Langues</b> </td>
       <td> Anglais </td>
       <td> Français-Anglais </td>
       <td> Français </td>
    </tr> 
    
    <tr>
       <td> <b>Taille (Textes)</b> </td>
       <td> 300 Mo </td>
       <td> 100 Mo </td>
       <td> 100 Mo </td>
    </tr> 
    
    <tr>
       <td> <b>Nombre de données</b> </td>
       <td> 313 332 objets - 105 000 exposés </td>
       <td> 17 424 objets - 8250 exposés </td>
       <td> 77 collections - 62 392 fichiers </td> 
    </tr> 
    
    <tr>
       <td> <b>Structure logique</b> </td>
       <td> Base de données de type tableur </td>
       <td> Base de données relationnelles </td>
       <td> XML-EAD </td>
    </tr> 
    
    <tr>
       <td> <b>Nombre d'éléments de structure logique</b> </td>
       <td> 1 table de 61 attributs </td>
       <td> 59 tables </td>
       <td> 146 éléments XML-EAD </td>
    </tr>   
      
</table> 

<p>
La migration de données vers des triplestores est un processus qui passe par différentes 
étapes : 
</p> 

<ul>
<li>préparation des données (étude et description structurelle des données), </li> 
<li>modélisation sémantique et alignement des données, </li> 
<li>création des triplestores - migration des données vers des triplestores, </li> 
<li>exposition et visualisation des triplestores, </li> 
<li>exploration et interrogation des triplestores notamment via des 
formulaires généraux et des "end point sparql" 
(interface de saisie et d'exécution de requêtes sparql). </li>
</ul> 

<p>Ainsi, il s'agit principalement (1) de passer de données non structurées ou semi structurées 
(notes, livres, html) vers des données structurées 
(tableur, base de données relationnelles, fichiers XML) 
et ensuite, (2) de transformer ces données structurées en données sémantiques (fichiers RDF) 
afin d'améliorer le partage, l'échange et la découverte de nouvelles connaissances. 
</p> 

<p>
D'autre part, plusieurs projets dans le monde s'intéressent à la migration de données vers des 
triplestores (CIDOC-CRM ou non), parmi lesquels :  
</p>

<ul>
<li> Le <i>British Museum</i> (cf. http://collection.britishmuseum.org/) 
qui est un musée sur  l'histoire et la culture humaine situé à Londres au Royaume-Uni 
et qui utilise le CIDOC-CRM </li> 
<li> <i>Arches</i> 
(cf. http://www.getty.edu/conservation/our_projects/field_projects/arches/) 
qui est une  collaboration entre le Getty Conservation Institute (GCI) 
et le World Monuments Fund (WMF) sur l'héritage culturel immobilier (monuments, ponts) 
et qui utilise le CIDOC-CRM </li> 
<li> <i>Biblissima</i> (cf. http://www.biblissima-condorcet.fr/) 
qui traite du Patrimoine écrit français du Moyen Âge et de la Renaissance 
et qui utilise le CIDOC-CRM </li> 
<li> </li> 
<li> <i>DBPedia</i> (cf. http://www.dbpedia.org/sparql) qui est une encyclopédie en ligne 
et qui n'utilise pas le CIDOC-CRM mais différents langages de métadonnées comme: 
dbpedia, foaf, umbel, schema.org, dublin core, geo 
</li>   
<li> <i>Symogih</i> (cf. http://www.symogih.org/sparql) pour la gestion 
de l'information historique 
et qui n'utilise pas le CIDOC-CRM mais différents langages de métadonnées comme: 
symogih, example.org, geo 
</li> 
<li> <i>Nakala</i> (cf. http://www.nakala.fr/sparql) qui est un service pour déposer, 
documenter et diffuser des données  
et qui n'utilise pas le CIDOC-CRM mais différents langages de métadonnées comme: 
foaf, skos, dublin core, vcard 
</li>
</ul> 


