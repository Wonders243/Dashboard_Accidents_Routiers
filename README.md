# Dashboard_Accidents_Routiers

## 🚗 Dashboard d’Analyse des Accidents Routiers.
Ce projet analyse les accidents de la route de la France en fonction de la météo, de la luminosité, du type de véhicule, des heures, et de la localisation.

## 📊 Fonctionnalités

### Visualisations :
- Carte interactive des accidents
- Diagramme des conditions météo
- Courbe des accidents par heure de la journée
- Graphique des types de véhicules impliqués
- Analyse de la gravité (blessés, tués)
- Histogramme des accidents par département

### 🎛️ Filtres :
- Année / mois
- Département
- Type de véhicule
- Météo / luminosité
- Gravité

``` arduino
road_accident/
|-- app.py
|-- data/
|   |--accidents.cvs
|-- components/
|   |-- charts.py
|   |-- map.py
|-- utils.py
| README.md
```

### 🛠️ Technologies
- Streamlit
- Pandas
- Plotly Express
- Folium
- scikit-learn (option prédiction)

### 📚 Data Source (France)

### Installation
``` bash
git clone https://github.com/Wonders243/road_accidents.git
cd road_accidents
pip install -r requirements.txt
```
### ▶️ Lancer l’app
``` bash
streamlit run app.py
```
  
