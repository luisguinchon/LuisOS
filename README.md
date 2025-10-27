Vous avez dit :
🧠 LuisOS

LuisOS est un système d’exploitation minimaliste codé en C# avec Cosmos.
Il fonctionne dans un environnement virtuel (QEMU, VMware, VirtualBox) et vise à montrer le fonctionnement d’un OS de base écrit entièrement en .NET.

⚙️ Fonctionnalités principales

Menu principal interactif (navigation avec ↑ ↓ et Entrée)

Explorateur de fichiers (simulation de fichiers virtuels)

Moniteur système (heure, date, info CPU/RAM simulées)

Éditeur de texte simple (bloc-notes intégré)

Calculatrice intégrée

Calendrier mensuel

Terminal minimal (commandes help, date, cat, ls, etc.)

Mini-jeu Pong en ASCII

Compatible QEMU et Cosmos UserKit

💽 Compilation

Projet compatible avec Cosmos UserKit pour Visual Studio.
Compiler en mode ISO puis exécuter avec :

qemu-system-x86_64 -cdrom LuisOS.iso -boot d -m 512 -vga std

🧰 Objectif

LuisOS sert de base d’apprentissage pour comprendre la structure d’un noyau :

Entrée clavier

Affichage terminal

Boucle de kernel simple

Gestion d’interfaces texte
