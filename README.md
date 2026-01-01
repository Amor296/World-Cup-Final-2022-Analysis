# 🏆 2022 FIFA World Cup Final: A Deep Tactical & Statistical Analysis
## 🇦🇷 Argentina vs. France 🇫🇷

![World Cup Final](https://img.shields.io/badge/Data-StatsBomb-orange) ![Python](https://img.shields.io/badge/Built%20With-Python-blue) ![Analysis](https://img.shields.io/badge/Type-Tactical%20Analysis-green)

### 📖 Overview
This project provides a comprehensive, data-driven deep dive into the **FIFA World Cup 2022 Final**. Using advanced football metrics and spatial data, we break down how the match unfolded, from Argentina's early dominance to France's late resurgence.

---

### 📂 Project Structure
The analysis is divided into three tactical phases (Notebooks):

1. **`01_Data_Exploration.ipynb`**: 
   - Connecting to StatsBomb Open Data.
   - Initial cleaning and filtering of the 3,000+ events recorded in the final.
   - High-level match statistics (Possession, Pass counts).

2. **`02_Player_Analysis.ipynb`**:
   - **Lionel Messi's Territorial Influence:** High-resolution heatmaps showing his movement.
   - **The "Mbappé Explosion":** Analyzing the 2-minute window that changed the game.
   - Key passing networks and creative hubs.

3. **`03_Tactical_Insights.ipynb`**:
   - **xG Flow (Expected Goals):** A momentum chart visualizing the "emotional rollercoaster" of the 120 minutes.
   - **Shot Maps:** Visualizing every shot taken, colored by xG value.
   - **Goalkeeper Face-off:** Statistical comparison between Emiliano Martínez and Hugo Lloris.

---

### 📊 Key Visualizations Included
> **Note:** The following visuals are generated within the notebooks using `mplsoccer`.

* **Heatmaps:** Utilizing Gaussian filters to show action density.
* **xG Flow Charts:** Visualizing match momentum and the impact of substitutions.
* **Shot Maps:** Every attempt on goal, including the legendary 123rd-minute save by Dibu Martínez.

---

### 🛠️ Technical Stack
* **Language:** Python 3.x
* **Key Libraries:**
    * `statsbombpy`: For seamless data fetching.
    * `pandas`: For advanced data manipulation.
    * `mplsoccer`: The gold standard for football pitch visualizations.
    * `scipy`: Used for spatial smoothing (Gaussian filters).
    * `matplotlib` & `seaborn`: For custom styling and charts.

---

### 🚀 How to Replicate this Analysis
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Amor296/World-Cup-Final-2022-Analysis.git](https://github.com/Amor296/World-Cup-Final-2022-Analysis.git)
