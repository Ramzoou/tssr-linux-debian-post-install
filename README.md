Ce script automatise la configuration post-installation d'un système Linux pour un environnement TSSR. Il effectue plusieurs tâches essentielles pour améliorer l'expérience utilisateur et la sécurité du système.

**Fonctionnalités**

✅ Mise à jour du système – Installe les dernières mises à jour pour garantir stabilité et sécurité.

✅ Ajout d'outils utiles – Installe une sélection d’outils pratiques pour l'administration et le développement.

✅ Personnalisation du MOTD – Affiche un message d’accueil lors de la connexion. 

✅ Modification du .bashrc – Ajoute des alias et des configurations utiles pour le terminal.

✅ Configuration de nanorc – Améliore l'expérience d'édition avec Nano.

✅ Gestion des clés SSH – Te demande d’ajouter tes clés SSH pour un accès sécurisé.

✅ Création d'un fichier de log – Archive toutes les actions effectuées pour un suivi facile.

Tu peux cloner le repo et éxécuter le script de cette manière
```
git clone https://github.com/ton-utilisateur/tssr-linux-postinstall.git
cd tssr-linux-postinstall
chmod +x install.sh
./install.sh
```
**Prérequis**

- Une distribution Linux compatible (Ubuntu, Debian, CentOS, etc.)

- Un accès root ou sudo

