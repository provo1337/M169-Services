# 20-Infrastruktur Automatisierung

## Aufbau der Umgebung

Die Infrastruktur des Webdienstes wurde nach folgender Anleitung aufgebaut.

### Wichtige Vagrant Befehle


1. vagrant init - initialisiert ein neues Vagrant-Projekt, indem es eine neue

2. Vagrantfile in einem leeren Ordner erstellt.

3. vagrant up - startet die virtuelle Maschine basierend auf der in der Vagrantfile definierten Konfiguration.

4. vagrant ssh - verbindet sich per SSH mit der virtuellen Maschine.

5. vagrant halt - stoppt die virtuelle Maschine.

6. vagrant destroy - löscht die virtuelle Maschine vollständig.

7. vagrant status - zeigt den aktuellen Status der virtuellen Maschine an.

8. vagrant reload - lädt die Konfiguration der virtuellen Maschine neu.

9. vagrant provision - führt die Konfigurationsskripte erneut aus, ohne die 
virtuelle Maschine zu zerstören und neu zu erstellen.

10. vagrant package - erstellt eine Box-Datei aus der aktuellen virtuellen Maschine.

11. vagrant box - verwaltet Box-Dateien, die als Basis für die Erstellung neuer virtueller Maschinen verwendet werden.

Diese sind nur einige der wichtigsten Vagrant-Befehle, es gibt jedoch noch viele weitere Befehle und Optionen, die je nach Bedarf und Anforderungen verwendet werden können.


