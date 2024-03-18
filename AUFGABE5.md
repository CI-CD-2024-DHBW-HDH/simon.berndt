# Klausur
## Aufgabe 5

### Welche Vorteile ein Kubernetes Deployment gegenüber einem Kubernetes Pod hat

Ein Deployment verwaltet einen oder mehrere Replikas eines Pods. Dadurch kann die
Anzahl der Pods variable skaliert werden. Pods können, sollten diese fehlerhaft sein,
automatisch neu gestartet werden. Ein großer Vorteil bietet die Rolling Update Funktion,
Pods können schrittweise aktualisiert werden, sodass die Anwendung immer verfügbar ist.
Falls das Update Fehlerhaft ist, kann dieses zurückgerollt werden.

### Wofür ein Kubernetes Service gut ist

Durch einen Service können Objekte, wie ein Deployment, eine feste IP Adresse erhalten.
Dadurch sind diese im Cluster erreichbar. Ein Service kann auch Load Balancing betreiben,
sodass Anfragen auf die Pods verteilt werden. Mit Hilfe der Konfiguration eines NodePorts
oder eines LoadBalancers können Services auch von außerhalb des Clusters erreicht werden.

### Mehrere Wege wie man eine Kubernetes Anwendung von außen erreichen kann

1. NodePort
2. LoadBalancer
3. Ingress