# Météo Marées

Appli Android : météo de Saint-Médard-en-Jalles et heures des marées (Lacanau-Océan, Cap Ferret/Arcachon, Le Verdon).

- Données : [Open-Meteo](https://open-meteo.com) (météo + modèle de niveau de la mer), sans clé d'API.
- Interface : `app/src/main/assets/index.html`, affichée dans une WebView native.
- L'APK est compilé automatiquement par GitHub Actions à chaque push sur `main`, puis publié dans **Releases**.

Les heures de marée viennent d'un modèle (±15–30 min) : pour la navigation, se référer au SHOM.
