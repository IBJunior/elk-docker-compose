<h2>Docker compose Elasticsearch et Kibana</h2>
<p>Ce repot github contient un fichier docker compose qui permet d'avoir elasticsearch et kibana sur PC/Mac sans les directement</p>

<h3>Comment l'utiliser ?</h3>
<ul>
    <li>Cloner ou télécharger ce repo pour l'avoir en local</li>
    <li>Avoir docker et docker compose installés, utilisez ce <a href="https://docs.docker.com/engine/install">lien</a> pour installer docker et <a href="https://docs.docker.com/compose/install/">celui-ci</a> pour docker compose.</li>
    <li>
    Sur Linux, rendez vous sur le repertoire contenant le fichier <i>docker-compose.yml</i> et excutez la commande <b>docker-compose -up</b> ajouter d'autres options si vous voulez, vous pouvez voir les options disponibles avec la commande <b>docker-compose -up --help</b>
    </li>
    <li>
     Sur windows ou Mac vous pouvez exécuter les mêmes commandes mais à conditions que le docker-desktop soit lancé avant.
    </li>
    <li>
      Pour tester si les conteneurs sont bien lancés, rendez sur un navigateur de votre choix, entrez <a href="http://localhost:9200">http://localhost:9200</a> pour elasticsearch et <a href="http://localhost:5601">http://localhost:5601</a>
      pour kibana
    </li>
</ul>