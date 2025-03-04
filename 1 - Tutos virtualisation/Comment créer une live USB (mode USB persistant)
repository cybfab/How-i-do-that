# Création d'une Clé USB Live avec Tails OS (Mode Persistance)

## Introduction
Ce tutoriel explique comment créer une clé USB bootable avec **Tails OS**, en mode **persistance**, à l'aide de **Rufus**. Tails OS est un système d'exploitation axé sur la confidentialité et l'anonymat.

---

## Prérequis
### Matériel
- Une clé USB d'au moins **8 Go** (16 Go recommandés)
- Un ordinateur avec un **port USB**

### Logiciels
- **Tails OS** (dernière version) : [Téléchargement ici](https://tails.net/)
- **Rufus** : [Téléchargement ici](https://rufus.ie/)

---

## Étape 1 : Télécharger et Vérifier Tails OS
1. **Téléchargez** l'image ISO de Tails OS depuis le site officiel.
2. **Vérifiez** l'intégrité du fichier avec la somme SHA256 (optionnel mais recommandé) :
   ```sh
   sha256sum tails-amd64-x.x.x.iso
   ```
   Comparez le résultat avec celui fourni sur le site de Tails.

---

## Étape 2 : Création de la Clé USB Bootable avec Rufus
1. **Insérez la clé USB** dans l’ordinateur.
2. **Ouvrez Rufus** et sélectionnez votre clé USB.
3. **Paramétrez Rufus** :
   - **Périphérique** : Sélectionnez votre clé USB.
   - **Type de démarrage** : Sélectionnez l’ISO de Tails OS.
   - **Système de fichiers** : **FAT32**
   - **Taille d'unité d'allocation** : **Par défaut**
   - **Options avancées** : Cochez "Créer un disque bootable en mode ISO"
4. Cliquez sur **Démarrer** et attendez la fin du processus.

---

## Étape 3 : Activer la Persistance sur Tails
1. **Démarrez** sur la clé USB en choisissant Tails lors du boot.
2. Une fois sur Tails, allez dans **Applications > Tails > Configurer le stockage persistant**.
3. Sélectionnez votre clé USB et **activez la persistance**.
4. Redémarrez Tails et entrez votre **mot de passe de persistance** lors du boot.

### Fonctionnement du Stockage Persistance
Tout ce que vous faites disparaît automatiquement lorsque vous éteignez Tails.
Mais vous pouvez sauvegarder certains de vos fichiers et configurations dans un **Stockage Persistant chiffré** sur votre clé USB Tails, par exemple :
- Vos documents
- Vos mots de passe Wi-Fi
- Vos favoris de navigateur
- ...

Le **Stockage Persistant** est une partition chiffrée protégée par une phrase de passe qui occupe tout l’espace libre restant sur la clé USB.
Tout ce qui se trouve dans le Stockage Persistant est automatiquement chiffré.

À chaque démarrage de Tails, vous pouvez choisir de **déverrouiller ou non** votre Stockage Persistant.

⚠️ **Attention** : Le Stockage Persistant n'est **pas caché**. Un attaquant en possession de votre clé USB pourra voir qu'il existe, même s'il ne pourra pas y accéder sans la phrase de passe.

---

## Conclusion
Vous avez maintenant une clé USB **Live Tails OS avec persistance**. Cela vous permet de conserver vos paramètres et fichiers sécurisés tout en utilisant un OS axé sur la confidentialité.

**Bon usage et restez en sécurité !** 🔒
