# GraphTech — installation et mises à jour

Installe ou met à jour le plugin [GraphTech](https://github.com/Pm74k/GraphTech-Cosmetics-) pour Vencord avec une seule commande. La même commande sert pour la première installation et pour chaque mise à jour.

**Prérequis (une seule fois)** : [Node.js](https://nodejs.org) (version LTS) et Git.

## 🍎 Mac

Dans l'app **Terminal** :

```
curl -fsSL https://raw.githubusercontent.com/Pm74k/GraphTech-Cosmetics-Auto-Update/main/install.sh | bash
```

## 🪟 Windows

Dans **PowerShell** :

```
irm https://raw.githubusercontent.com/Pm74k/GraphTech-Cosmetics-Auto-Update/main/install.ps1 | iex
```

## Ensuite

1. Première installation : choisis ton Discord dans la liste quand le script le demande.
2. Quitte Discord complètement (Cmd+Q sur Mac, clic droit sur l'icône puis Quitter sur Windows) et relance-le.
3. Première installation seulement : Paramètres → Vencord → Plugins → GraphTech → active-le.

Le script télécharge le plugin depuis [GraphTech-Cosmetics-](https://github.com/Pm74k/GraphTech-Cosmetics-) (code open source, GPL-3.0). Lis-le avant de lancer une commande qui exécute un script : les fichiers `install.sh` et `install.ps1` sont courts.
