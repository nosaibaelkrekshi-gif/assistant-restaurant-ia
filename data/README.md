# Données

Le chatbot s'appuie sur le jeu de données public **Restaurant & Consumer Data** (UCI Machine Learning Repository) : restaurants de la région de San Luis Potosí (Mexique), avec leurs cuisines, moyens de paiement, parkings et notes des clients.

🔗 Source : [UCI Machine Learning Repository, Restaurant & Consumer Data](https://archive.ics.uci.edu/dataset/232/restaurant+consumer+data)

Fichiers utilisés par le notebook, à placer dans le même dossier (ou dans `/content/` sur Google Colab) :

| Fichier | Contenu |
|---|---|
| `geoplaces2.csv` | Restaurants : nom, ville, adresse, prix, horaires… |
| `rating_final.csv` | Notes données par les clients |
| `chefmozcuisine.csv` | Types de cuisine par restaurant |
| `chefmozparking.csv` | Parkings disponibles |
| `chefmozaccepts.csv` | Moyens de paiement acceptés |

Après fusion : **130 restaurants, 1 161 avis, 17 villes et 23 types de cuisine**.

