#Redmine

Opdracht 3 op Toledo. Als je gebruik maakt van Helm, zet je values-file in deze map, en je commando hieronder. Maak je gebruik van klassieke deployments, zet dan je bestanden in deze map.


helm repo add bitnami https://charts.bitnami.com/bitnami
helm install --name redmine bitnami/redmine --values values.yaml

Gebruik gemaakt van Helm in Lens, andere procedure dus.