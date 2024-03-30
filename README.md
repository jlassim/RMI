# serveur RMI n java
Ce projet est un exemple simple d'un serveur RMI en Java qui fournit un service de temps. Le serveur RMI expose un objet distant qui permet aux clients de récupérer l'heure actuelle à partir du serveur.
## structure
TimeService.java : Interface définissant le service de temps. TimeServiceImpl.java : Implémentation du service de temps. 
TimeServer.java : Classe principale du serveur RMI. TimeClient.java : Classe principale du client RMI.
## execution
Pour exécuter le serveur RMI, suivez les étapes suivantes :

Compilez toutes les classes avec javac :

javac TimeService.java TimeServiceImpl.java TimeServer.java TimeClient.java
Démarrez le serveur en exécutant TimeServer :

java TimeServer
## utilisation client
Une fois que le serveur est en cours d'exécution, vous pouvez exécuter le client RMI pour récupérer l'heure actuelle à partir du serveur. Exécutez le client avec la commande suivante :

```  java TimeClient ```

Le client établira une connexion avec le serveur RMI, récupérera l'heure actuelle à partir du service de temps et l'affichera.
