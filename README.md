# 📘 Doorlooptijd & SLA-analyse (Wire Solutions)

Deze repository bevat de Jupyter Notebook, dataset en ondersteunende code die zijn gebruikt voor de doorlooptijdanalyse (deelvraag 2) binnen het data-onderzoek voor Wire Solutions.


## 🎯 Doel van de analyse

In deze analyse is onderzocht hoe lang incidenten per categorie openstaan en welke verschillen er bestaan tussen 1e, 2e en 3e lijn, Functioneel Beheer en Hardware/Telefonie.  
Met behulp van statistiek en percentielberekeningen (P50–P95) is een datagedreven SLA-model opgesteld.

De resultaten worden gebruikt om:

- bottlenecks te identificeren (>14 dagen),  
- realistische SLA-grenzen te bepalen,  
- en inzicht te geven in werkdruk & capaciteit per incidentcategorie.

## 🧪 Inhoud van de notebook

De notebook bevat onder andere:

- Inladen en opschonen van incidentdata  
- Omrekenen van minuten → uren → dagen  
- Berekening van gemiddelde, mediaan, max & standaarddeviatie  
- Percentielen (P80, P90, P95) per categorie  
- Analyse van langdurige incidenten (>14 dagen)  
- Output ter ondersteuning van het SLA-model in het hoofdrapport  

**De code draait met:**

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## 🔒 Privacy & datagebruik

De dataset (`incidentdata_2019_clean.csv`) bevat geen persoonsgegevens.  
Alle analyses zijn uitsluitend gebruikt voor educatieve doeleinden binnen de leerlijn Data Science.

## 🧑‍💻 Auteur

Steffan Boer – Bootcamp Data Engineer – 2025
