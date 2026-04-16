# Mathematische Simulationen
**Universitätsprojekt – Hochschule München**
(Korbinian Haberstetter, Tilman Patzak, Ilan Wiesner)

## Code & Simulation (Instant View)

GitHub unterstützt das native Rendering von Jupyter Notebooks.  
Sie können die Implementierung und die Ergebnisse direkt im Browser einsehen:  

1.  **[Waldbrand-Simulation anzeigen (Jupyter Notebook)](Waldbrandsimulation/Waldbrand_Notebook_Haberstetter_Wiesner_Patzak.ipynb)** | [DOKU](Waldbrandsimulation/Waldbrand_Dokumentation_Haberstetter_Wiesner_Patzak.pdf)
2.  **[Populations-Analyse anzeigen (Jupyter Notebook)](Populationsdynamiken/Populationsdynamiken_Notebook_Haberstetter_Patzak_Wiesner.ipynb)** | [DOKU](Populationsdynamiken/Populationsdynamiken_Dokumentation_Haberstetter_Patzak_Wiesner.pdf)

> **Technischer Hinweis:** > Die im Waldbrand-Notebook angezeigten Meldungen (*Widget Javascript not detected*) resultieren aus dem statischen Rendering durch GitHub. Die zugrundeliegenden `@interact`-Module zur dynamischen Parametersteuerung erfordern eine aktive Kernel-Verbindung (z.B. lokale SageMath-Umgebung). Sämtliche Code-Logik und statisch generierten Visualisierungen sind davon unberührt.

---

## Kurzbeschreibung
Dieses Repository umfasst zwei wissenschaftliche Simulationsprojekte, die in SageMath (Python-basiert) im Rahmen des Faches "Angewandte Mathematik" 2025 angefertigt wurden.

**Kernfunktionalitäten:**
* **Waldbrandsimulation:** Ein zellulärer Automat, der die Brandausbreitung unter Berücksichtigung von Windvektoren, Brenndauer und stochastischen Blitzschlägen modelliert.
* **Populationsdynamik:** Numerische Lösung von Lotka-Volterra-Systemen inklusive eines kritischen Vergleichs von DGS-Solvern (Euler, RK4, OdeInt) hinsichtlich Rechenzeit und Präzision.

---
