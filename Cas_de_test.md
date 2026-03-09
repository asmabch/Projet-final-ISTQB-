Liste des cas de test:

# Cas de test 1

### **Nom du test**
Inscription d’un nouvel utilisateur

### **Identifiant du cas de test**
TC-01

### **Description**
Vérifier qu’un nouvel utilisateur peut créer un compte sur le site.

### **Références**
EXG-01 – Inscription utilisateur

### **Prérequis**
L’utilisateur ne possède pas encore de compte.

### **Étapes du test**
1. Accéder à la page d’accueil  
2. Cliquer sur Sign in  
3. Remplir le formulaire  
4. Valider

### **Résultats attendus**
Le compte utilisateur est créé avec succès.
---

# Cas de test 2

### **Nom du test**
Connexion d’un utilisateur existant

### **Identifiant du cas de test**
TC-02

### **Description**
Vérifier qu’un utilisateur déjà inscrit peut se connecter au site en utilisant un email et un mot de passe valides.

### **Références**
EXG-02 – Connexion utilisateur.

### **Prérequis**
Un compte utilisateur valide existe dans le système.

### **Étapes du test**
1. Accéder à la page d’accueil du site  
2. Cliquer sur Sign in  
3. Saisir l'adresse email du compte 
4. Saisir le mot de passe
5. Cliquer sur le bouton de connexion

### **Résultats attendus**
L’utilisateur est authentifié et redirigé vers son espace personnel.
---

# Cas de test 3

### **Nom du test**
Ajouter un produit au panier

### **Identifiant du cas de test**
TC-03

### **Description**
Vérifier que l’utilisateur peut ajouter un produit au panier depuis la page produit.

### **Références**
EXG-04 – Ajout de produit au panier.

### **Prérequis**
Le site est accessible et au moins un produit est disponible dans le catalogue.

### **Étapes du test**
1. Accéder au catalogue des produits  
2. Sélectionner un produit 
3. Cliquer sur le bouton « Add to cart »
4. Consulter le panier

### **Résultats attendus**
Le produit sélectionné est ajouté au panier et apparaît dans la liste des articles du panier.
---

# Cas de test 4

### **Nom du test**
Suppression d’un produit du panier

### **Identifiant du cas de test
TC-04

### **Description**
Vérifier que l’utilisateur peut supprimer un produit présent dans son panier.

### **Références**
EXG-05 – Fonctionnalité de gestion du panier.

### **Prérequis**
Un produit est déjà présent dans le panier.

### **Étapes du test**
1. Accéder au panier 
2. Identifier le produit ajouté
3. Cliquer sur l’option de suppression du produit
4. Consulter le panier

### **Résultats attendus**
Le produit est supprimé du panier et le panier est mis à jour.
