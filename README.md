# paper-airplane-doe-experiment
DoE-based optimization of paper airplane flight distance using ANOVA, half &amp; full factorial testing.
# 📌 Design of Experiments for Optimizing Paper Airplane Flight Distance

This project investigates how geometric and structural changes impact the flight performance of paper airplanes. Using both **half-factorial (2⁴⁻¹)** and **full-factorial** experimental designs, we test four key factors: **aspect ratio, ballast, nose fold, and wing flaps**, with flight distance and time as performance metrics.

## 🔍 Summary
- Two-phase DoE approach: **Half factorial ➝ Full factorial**
- 4 design factors tested: **Aspect Ratio, Ballast, Nose Fold, Wing Flaps**
- ~72 total flights performed indoors under controlled conditions
- ANOVA used to determine statistical significance
- **Aspect ratio was the dominant variable affecting flight distance**
- Full details, figures, and ANOVA tables in included report

## 🧠 Key Findings
- 📌 **Aspect ratio is the only statistically significant factor** affecting flight distance
- ✨ Optimal configuration:  
  **AR = 1.2**, no nose fold, **no ballast**
- 🔁 Converting nose fold to a **percentage (11.4%)** improved data consistency
- 🚫 Wing flaps + ballast increased noise / instability during launch
- 🎯 Design simplicity = best performance

## 📊 Results Overview

| Factor               | Effect on Distance       | Significant? |
|----------------------|--------------------------|--------------|
| Aspect Ratio         | ⭐ Strong impact          | ✔ Yes        |
| Nose Fold            | Mild effect              | ⚠️ Interaction only |
| Ballast              | Weak / inconsistent      | ❌ No         |
| Wing Flaps (initial) | Confounded AR, removed   | ❌ No         |

## 🛠️ Tools, Methods & Skills Demonstrated
- Design of Experiments (**2⁴⁻¹** & Full Factorial: 4×2×2)
- **ANOVA, residual analysis, normality & variance testing**
- Uncertainty quantification & error propagation
- SolidWorks modeling for dimension validation
- Frame-by-frame measurement from **30 Hz video**
- Controlling experimental noise & reproducibility
- Indoor controlled launch setup build + documentation


