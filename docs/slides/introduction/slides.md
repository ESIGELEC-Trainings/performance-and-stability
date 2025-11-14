# 🚀 Chapitre 1  
## Introduction à la Performance des Applicatifs  
### UE : Performance & Stabilité — 3A ESIGELEC

---

# 🎯 Objectifs du chapitre
- Comprendre ce qu'est la **performance applicative**  
- Connaître les **indicateurs clés** (latence, débit, disponibilité…)  
- Identifier les **causes principales** de lenteurs  
- Introduire la notion de **stabilité**  
- Comprendre pourquoi la performance est un **enjeu majeur**

---

# ❓ Pourquoi la performance est importante ?
- 🧑‍💻 **Expérience utilisateur**
- 💸 **Coût d’infrastructure**
- 📉 **Perte de clients en cas de lenteur**
- ⚡ **Disponibilité et SLA**
- 🔐 **Impacts sur la sécurité**
- 📈 **Scalabilité et croissance**

---

# 📉 Exemple réel
Une page web qui passe de **1.5s → 3.5s** au chargement peut entraîner :

- -40% conversions e-commerce  
- +30% abandon utilisateur  
- +80% coût infra pour compenser  

---

# 🧩 Performance vs Stabilité
👉 **Performance** = rapidité  
👉 **Stabilité** = capacité à fonctionner correctement, longtemps

---

# 🧪 Exemple d’application
Un service peut être :

|||  
### 🟢 Très rapide  
**Mais instable** → crash sous charge

|||  
### 🔵 Très stable  
**Mais lent** → mauvaise UX

---

# 🧠 Les 4 piliers de la performance
- ⏱️ **Latence**  
  Temps pour répondre **à une requête**

- 📦 **Débit / Throughput**  
  Nombre de requêtes traitées **par seconde**

- 💾 **Consommation de ressources**  
  CPU • RAM • I/O • Connexions DB

- 🕸️ **Scalabilité**  
  Capacité à **grandir** quand la charge augmente

---

# ⏱️ Latence : la mesure la plus connue

```text
Temps total = 
  Réseau 
+ Parsing 
+ Calcul 
+ Accès BDD 
+ Sérialisation
