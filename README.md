# Mathematische Simulationen

![Simulation Demo](link)

<a href="doku waldbrand link" target="_blank">DOKU Waldbrand (PDF)</a> | <a href="doku populationsdynamik link" target="_blank">DOKU Populationsdynamik (PDF)</a>

---

## Kurzbeschreibung
Dieses Repository umfasst zwei wissenschaftliche Simulationsprojekte, die in SageMath (Python-basiert) im Rahmen des Faches "Angewandte Mathematik" 2025 angefertigt wurden.

**Kernfunktionalitäten:**
* **Waldbrandsimulation:** Ein zellulärer Automat, der die Brandausbreitung unter Berücksichtigung von Windvektoren, Brenndauer und stochastischen Blitzschlägen modelliert.
* **Populationsdynamik:** Numerische Lösung von Lotka-Volterra-Systemen inklusive eines kritischen Vergleichs von DGS-Solvern (Euler, RK4, OdeInt) hinsichtlich Rechenzeit und Präzision.

---

## Code & Simulation (Instant View)

GitHub unterstützt das native Rendering von Jupyter Notebooks. Sie können die Implementierung und die Ergebnisse direkt im Browser einsehen:

1.  **[Waldbrand-Simulation anzeigen (Jupyter Notebook)](waldbrand.ipynb)**
2.  **[Populations-Analyse anzeigen (Jupyter Notebook)](./population.ipynb)**

---

## Setup & Start (Lokale Ausführung)

### Voraussetzungen
Installiertes **SageMath (Version 10.x+)** oder eine Jupyter-Umgebung mit konfiguriertem Sage-Kernel.

### 1. Repository klonen

```bash
git clone [https://github.com/IIIilanIII/Sagemath-Simulationen.git](https://github.com/IIIilanIII/Sagemath-Simulationen.git)
cd Repo name
```

### 2. Jupyter Notebook starten

1. Starten Sie die Umgebung:
```bash
    sage -n jupyter
```
2. Öffnen Sie die gewünschte .ipynb Datei.
3. Führen Sie die Zellen aus (Shift + Enter).
