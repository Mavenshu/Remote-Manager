# 🚀 Remote Manager - Quick Start Guide (Updated)

## 📦 Installation et Configuration

## ⚡ Actions Rapides Essentielles

### 🔗 **Quick Actions Menu**
Cliquez sur "Remote Manager" dans la barre de statut pour accéder à :

- **Terminal** - Ouvrir un nouveau terminal
- **Sessions** - Gérer les sessions actives  
- **Tools** - Outils de diagnostic et utilitaires
- **Settings** - Configuration et préférences
- **Macros** - Système d'automatisation (Nouveau !)
- **Help** - Documentation et support

### 🎯 **Workflow Recommandé**

#### **Étape 1 : Créer vos credentials**
1. Sidebar → Section "Credentials" → Bouton "+"
2. Saisissez nom d'utilisateur et mot de passe
3. Validez avec "Create Credential"

#### **Étape 2 : Ajouter une connexion**
1. Sidebar → Section "Connections" → Bouton "+"
2. Remplissez les informations :
   - **Host** : IP ou nom de serveur (ex: `192.168.1.100`)
   - **Type** : RDP, SSH, Telnet, VNC
   - **Category** : Server, Desktop, Router, etc.
   - **Credential** : Sélectionnez depuis la liste
   - **Name** : Nom descriptif

#### **Étape 3 : Se connecter**
1. **Double-clic** sur la connexion dans la sidebar
2. **Ou** clic-droit → "Connect"
3. **Ou** utilisez Quick Actions → Sessions

## 📜 Système de Macros (Nouveau !)

### **Enregistrement de Macros**
```
Ctrl+Shift+F9  → Démarrer l'enregistrement
Ctrl+Shift+F10 → Arrêter l'enregistrement  
Ctrl+Shift+F11 → Jouer une macro sauvée
```

### **Utilisation Pratique**
1. **Planifiez** votre séquence d'actions
2. **Démarrez** l'enregistrement (`Ctrl+Shift+F9`)
3. **Nommez** votre macro (ex: "Connexion serveur prod")
4. **Exécutez** vos actions normalement
5. **Arrêtez** l'enregistrement (`Ctrl+Shift+F10`)
6. **Testez** immédiatement avec (`Ctrl+Shift+F11`)

### **Gestion des Macros**
- **Quick Actions → Macros → Macro Library** : Interface complète
- **Edit Macros** : Renommer, supprimer, voir les détails
- **Statistiques** : Nombre d'utilisations, dernière exécution

## 🔧 Configuration Recommandée

### **Paramètres de base**
1. **Quick Actions → Settings**
2. Ajustez selon vos besoins :
   - **Timeout** de connexion
   - **Répertoires** par défaut
   - **Niveau de logs**
   - **Comportement** des macros

### **Organisation des Connexions**
- **Utilisez les groupes** : Prod, Dev, Test
- **Catégories cohérentes** : Server, Desktop, Network
- **Noms descriptifs** : "DB-PROD-01" plutôt que "Server1"

## 📥 Import/Export

### **Sauvegarde complète**
1. **Quick Actions → Tools → Export Configuration**
2. **Choisissez le format** :
   - Complete : Connexions + credentials (sans mots de passe)
   - Connections only : Format legacy
3. **Sauvegardez** le fichier JSON

### **Restauration**
1. **Quick Actions → Tools → Import Configuration**
2. **Sélectionnez** votre fichier de sauvegarde
3. **Suivez** l'assistant d'import
4. **Re-saisissez** les mots de passe si nécessaire

## 🚨 Résolution Rapide des Problèmes

### **Connexion échoue**
1. **Vérifiez** l'adresse IP/nom d'hôte
2. **Testez** le ping depuis un terminal
3. **Contrôlez** les credentials
4. **Consultez** les logs : Quick Actions → Tools → Debug

### **Credentials non trouvés**
1. **Recreez** le credential si nécessaire
2. **Vérifiez** l'orthographe du nom d'utilisateur
3. **Utilisez** Debug Storage pour diagnostiquer

### **Extension ne répond pas**
1. **Redémarrez** VS Code
2. **Désactivez/Réactivez** l'extension
3. **Consultez** la console développeur (`F12`)

## 💡 Conseils de Productivité

### **Macros Utiles à Créer**
- **Connexion + ouverture d'outils** spécifiques
- **Séquences de diagnostic** réseau
- **Configuration** de nouveaux serveurs
- **Sauvegarde** automatique des settings

### **Organisation Efficace**
- **Un groupe par environnement** (Prod, Dev, Test)
- **Sous-groupes par fonction** (Web, DB, Monitoring)
- **Naming convention** cohérente
- **Credentials partagés** pour les groupes

### **Raccourcis Essentiels**
```
Ctrl+Shift+P     → Palette de commandes Remote Manager
Ctrl+Shift+F9    → Record macro
Ctrl+Shift+F10   → Stop recording  
Ctrl+Shift+F11   → Play macro
F1               → Aide contextuelle
```

Vous êtes maintenant prêt à utiliser Remote Manager efficacement ! 🎉

Pour plus de détails sur les macros, consultez le fichier `MACRO-SYSTEM-GUIDE.md`.
