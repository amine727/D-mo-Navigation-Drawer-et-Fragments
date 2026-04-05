# 📱 LAB 10 : Navigation Drawer et Fragments

## 🎓 Cours

Programmation Mobile – Android (Java)

---

## 🎯 Objectif

L’objectif de ce TP est de créer une application Android intégrant :

* Un **menu latéral (Navigation Drawer)**
* La gestion de plusieurs **fragments**
* Le changement dynamique de contenu dans une seule activité

---

## 🛠️ Technologies utilisées

* Java
* Android Studio
* Android SDK (API 24+)
* Material Design

---

## 📂 Structure du projet

```
app/
 ├── java/com.example.navigationdrawerdemo/
 │    ├── MainActivity.java
 │    ├── BlankFragment.java
 │    ├── BlankFragment2.java
 │    └── FragmentList.java
 │
 ├── res/
 │    ├── layout/
 │    │    ├── activity_main.xml
 │    │    ├── fragment_blank.xml
 │    │    └── fragment_blank2.xml
 │    │
 │    ├── menu/
 │    │    └── activity_main_drawer.xml
 │    │
 │    └── values/
 │         └── strings.xml
```

---

## ⚙️ Fonctionnement

L’application contient :

### 📌 1. Navigation Drawer

Un menu latéral permettant d’accéder à différents écrans :

* Fragment 1
* Fragment 2
* Fragment List

---



### 📌 3. Navigation

* Le menu s’ouvre avec le bouton ☰
* Chaque clic remplace dynamiquement le fragment affiché

---

## ▶️ Exécution

1. Lancer l’émulateur Android
2. Exécuter l’application
3. Ouvrir le menu via :

   * Bouton ☰
   * ou swipe de gauche à droite
4. Naviguer entre les fragments

---

## 📸 Résultat

<img width="439" height="906" alt="10" src="https://github.com/user-attachments/assets/2fdb5e84-cfcb-4957-ad07-5390a085a83f" />


---


---

## 🧠 Conclusion

Ce lab permet de comprendre comment structurer une application Android avec une navigation moderne et modulaire, en utilisant des fragments pour améliorer l’expérience utilisateur.

---



---
