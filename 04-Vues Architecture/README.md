# Vues d’Architecture — FOOSUS

Ce dossier regroupe les représentations visuelles de l’architecture cible de la plateforme FOOSUS.  
Chaque vue illustre un aspect structurant du système, facilitant la compréhension, la communication et la validation des choix techniques.

Les vues ont été conçues pour répondre aux besoins des parties prenantes, soutenir les revues d’architecture et servir de support à la soutenance.

---

## 📘 Vues disponibles

### **Vue de Contexte**  
Représente les interactions entre FOOSUS et son environnement externe (utilisateurs, systèmes tiers, partenaires).  
Permet d’identifier les flux, les dépendances et les frontières du système.

### **Vue des Domaines**  
Découpe la plateforme en domaines fonctionnels cohérents : Recherche, Catalogue & Offres, Fournisseurs, Consommateurs, Back‑office, Expérimentation, Paiements (futur).  
Permet de structurer les responsabilités et de guider le découpage des services.

### **Vue Micro‑services**  
Présente les services techniques, leurs API exposées, leurs dépendances et leur organisation par domaine.  
Permet de visualiser les frontières, les interactions et les points d’observabilité.

### **Vue de Coexistence**  
Modélise la stratégie de migration entre l’ancien système et FOOSUS.  
Utilise le pattern Strangler pour permettre une transition progressive et réversible.

### **Vue de Déploiement**  
Décrit l’organisation technique de la plateforme : cloud provider, régions, load balancer, réplicas, CI/CD, monitoring.  
Permet d’évaluer la scalabilité, la résilience et la capacité de livraison continue.

---

## 🧭 Rôle des vues dans l’architecture FOOSUS

Les vues d’architecture :

- rendent la plateforme **lisible et partageable**,  
- facilitent les **revues techniques et fonctionnelles**,  
- soutiennent la **prise de décision** et la **communication inter‑équipes**,  
- constituent un **support visuel essentiel** pour la soutenance.

---

## 📂 Accès aux diagrammes

Les fichiers sont disponibles dans le sous‑dossier `Diagrams`.  
Chaque diagramme est nommé selon sa vue et accompagné d’une légende si nécessaire.
