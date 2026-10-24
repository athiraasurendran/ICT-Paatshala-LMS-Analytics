# High-Level Solution Architecture

This diagram describes the project workflow at a conceptual level. It is not a reproduction of internal source code, infrastructure, or deployment details.

```mermaid
flowchart TB
    A["Excel LMS data<br/>2019–2025"] --> B["Python<br/>Jupyter Notebook"]
    B --> C["Pandas and NumPy<br/>Data preparation"]
    C --> D["EDA and descriptive statistics"]
    D --> E["Trend and programme comparisons"]
    E --> F["Matplotlib · Seaborn · Plotly"]
    F --> G["Flask-based dashboard"]
    G --> H["KPI cards and analytical views"]
```

## Components

| Component | Role |
|---|---|
| Input | Historical Excel files supplied for the internship work |
| Preparation | Python, Pandas, and NumPy |
| Analysis | EDA, descriptive statistics, time-based trends, and programme comparisons |
| Visualisation | Matplotlib, Seaborn, and Plotly |
| Presentation | Flask web application displaying selected indicators and visualisations |

The architecture intentionally excludes company-specific data models, internal infrastructure, endpoints, deployment configuration, and sensitive implementation details.
