# Exercice Java : Système de Gestion de Bibliothèque

## 👨‍🎓 Objectif Pédagogique
Mettre en pratique les concepts fondamentaux de Java vus lors de la première session :
- Types primitifs et références
- Structure d'un programme Java
- Variables et opérateurs
- Structures de contrôle
- Méthodes et paramètres

## 📝 Description
Développer un système simple de gestion de bibliothèque permettant de :
- Gérer un catalogue de livres
- Gérer les emprunts et retours
- Rechercher des livres
- Afficher l'état de l'inventaire

## 🎯 Fonctionnalités à Implémenter

### 1. Classe `Livre`
```java
public class Livre {
    // TODO: Implémenter la classe
}
```
- Attributs à prévoir :
  - Titre
  - Auteur
  - ISBN
  - Statut (disponible/emprunté)
- Constructeur(s)
- Getters/Setters
- Méthode toString()

### 2. Classe `Bibliotheque`
```java
public class Bibliotheque {
    // TODO: Implémenter la classe
}
```
Méthodes à implémenter :
- `ajouterLivre()` : Ajoute un nouveau livre
- `retirerLivre()` : Retire un livre du catalogue
- `emprunterLivre()` : Marque un livre comme emprunté
- `retournerLivre()` : Marque un livre comme disponible
- `rechercherLivres()` : Trouve des livres par titre ou auteur
- `afficherInventaire()` : Affiche l'état de la bibliothèque

## 💻 Comment Démarrer
1. Créer un nouveau projet Java
2. Implémenter les classes requises
3. Créer une classe Main avec des tests
4. Vérifier toutes les fonctionnalités

## ✅ Critères de Validation
- [ ] Le code compile sans erreur
- [ ] Les classes sont correctement structurées
- [ ] Les méthodes sont bien documentées (JavaDoc)
- [ ] Les cas d'erreur sont gérés
- [ ] Les conventions de nommage Java sont respectées
- [ ] Les tests démontrent le bon fonctionnement

## 🎖️ Bonus
Pour aller plus loin :
- Ajouter une gestion des dates d'emprunt
- Implémenter un système de réservation
- Ajouter des catégories de livres
- Gérer les amendes pour retard

## 📚 Exemple d'Utilisation
```java
public class Main {
    public static void main(String[] args) {
        // Créer une bibliothèque
        Bibliotheque biblio = new Bibliotheque();

        // Ajouter des livres
        biblio.ajouterLivre(/* params */);

        // Emprunter un livre
        boolean empruntOk = biblio.emprunterLivre(/* params */);

        // Rechercher des livres
        List<Livre> resultats = biblio.rechercherLivres("Java");

        // Afficher l'inventaire
        biblio.afficherInventaire();
    }
}
```

## 🔍 Points d'Attention
- Valider les données en entrée
- Gérer les cas null
- Utiliser les bons types pour chaque attribut
- Organiser le code de manière claire
- Documenter les choix d'implémentation

## 📋 Échéance
À remettre avant la prochaine session.

## 💡 Conseils
- Commencer par les fonctionnalités de base
- Tester chaque méthode au fur et à mesure
- Ne pas hésiter à refactoriser le code
- Privilégier la lisibilité du code
