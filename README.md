Weather Analysis – TP Python
Ce projet permet d’analyser les prévisions météo d’une ville donnée en utilisant l’API OpenWeatherMap.
Il récupère la météo sur 5 jours (toutes les 3h), calcule des statistiques et génère un rapport JSON.

Le programme :
    Demande en entrée : 
        le nom d'une ville
        un code pays ISO (2 lettres)

    Appelle l’API OpenWeatherMap
    Analyse les données :
        cumul de pluie et neige
        humidité maximale
        transitions météo importantes
    Génère un fichier weather_report_<city>_<country>.json

Installer les dépendances :
    pip install -r requirements.txt

Exécution : 
    python main.py

Si besoin d'un certificat, déposez le dans le dossier TP, décommentez la ligne 42 du fichier WeatherAnalysis.py, et commentez la ligne 41.
