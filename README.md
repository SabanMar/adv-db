# adv-db

Όλα τα κελία του κώδικά μας έχουν ήδη τρέξει και τα αποτελέσματα φάινονται σε κάθε notebook. 

Ωστόσο, για να τρέξει από την αρχή θα πρέπει να υπάρχει πρόσβαση στο Spark. Σε κάθε notebook πρέπει να γίνεται αρχικοποίηση του configuration και του SparkSession. Στη συνέχεια τα κελία εκτελούνται με την σειρά που δίνονται για κάθε notebook.

Αντιστοίχηση ερωτημάτων-notebooks:

Query 1 -> query1.ipynb

Query 2 -> query2.ipynb

Query 3 -> query3_final.ipynb

Query 4:
Ανάλογα με το configuration:
- 1 core/2 GB memory -> query4_1c.ipynb
  
- 2 cores/4GB memory -> query4_2c.ipynb

- 4 cores/8GB memory -> query4_3c.ipynb

Query 5:
Ανάλογα με το configuration:
- 2 executors × 4 cores/8GB memory -> query5_1c.ipynb
  
- 4 executors × 2 cores/4GB memory -> query5_2c.ipynb

- 8 executors × 1 core/2 GB memory -> query5_3c.ipynb
