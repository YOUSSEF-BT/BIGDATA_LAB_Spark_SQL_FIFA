# TP Spark SQL — FIFA World Cup (PySpark)

Ce projet est un TP réalisé avec **PySpark (Spark SQL)** sur **Google Colab**.
On charge le dataset `fifaworldcup.csv`, on crée une **vue temporaire** (`TempView`) puis on exécute des requêtes SQL, dont un exemple complet sur **le Maroc**.

## Fichiers
- `tp_spark_sql_fifa.py` : script PySpark
- `fifaworldcup.csv` : dataset utilisé

## Exécution sur Google Colab (recommandé)
1. Ouvre un notebook sur https://colab.research.google.com
2. Upload ces 2 fichiers :
   - `tp_spark_sql_fifa.py`
   - `fifaworldcup.csv`
3. Lance le code (copier/coller dans Colab ou exécuter le script)

## Installation (local)
```
pip install pyspark
```
Lancer le script (local)
⚠️ En local, vérifie le chemin du CSV dans le script.
Si besoin, remplace /content/fifaworldcup.csv par ./fifaworldcup.csv.

bash
Copier le code
python tp_spark_sql_fifa.py
Ce que fait le script
Crée une SparkSession

Lit le CSV en traitant "NA" comme valeur manquante (NULL)

Convertit la colonne date

Crée une vue temporaire SQL : matches

Exécute des requêtes SQL :

affichage des matchs

Maroc : 10 derniers matchs

Maroc : stats (V/N/D)

Maroc : buts pour/contre et différence

Auteur
Youssef BT

yaml
Copier le code

---

Si tu veux, envoie-moi le **nom exact de ton repo** (ou une capture) et je te dis où le mettre exactement dans l’interface GitHub (boutons à cliquer).
