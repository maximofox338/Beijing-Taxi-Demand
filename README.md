# Beijing Taxi Demand

Clustering of taxi demand in Beijing from T-Drive GPS trajectories: where demand
concentrates across the city, and how those hotspots shift over the course of a day.

Work in progress — the notebook, figures and results are being prepared.

**Planned contents**

- Preprocessing of raw GPS traces: 3σ outlier removal and a speed filter for physically
  impossible readings.
- K-Means clustering of pickup locations, with K selected by the elbow method, silhouette
  score and the Davies-Bouldin index. DBSCAN as a contrast, since it needs no K and labels
  noise.
- Random Forest regression for trip duration.

**Data**

T-Drive (Microsoft Research) is not redistributed here. It can be downloaded from
https://www.microsoft.com/en-us/research/publication/t-drive-trajectory-data-sample/

**Context**

Group project for *Data Science and Algorithms*, Beijing Institute of Technology, spring 2026.
