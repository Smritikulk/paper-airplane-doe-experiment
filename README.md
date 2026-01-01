# paper-airplane-doe-experiment
DoE-based optimization of paper airplane flight distance using ANOVA, half &amp; full factorial testing.

# Design of Experiments for Optimizing Paper Airplane Flight Distance

This repository documents a Design of Experiments (DoE) project studying how geometric and structural modifications affect the flight performance of paper airplanes. A two-phase experimental approach was conducted using both half-factorial (2⁴⁻¹) and full-factorial designs to evaluate the statistical significance of aspect ratio, ballast, nose folds, and wing flaps. Performance metrics included flight distance and time, measured indoors under controlled conditions.

## Project Overview
- Two-stage DoE approach: half-factorial screening followed by full-factorial refinement
- Four initial factors studied: aspect ratio, ballast, nose fold, wing flaps
- Full-factorial refinement focused on the most influential parameters
- Approximately 72 total flights conducted in controlled indoor conditions
- ANOVA and residual analysis used to evaluate factor significance

## Key Findings
- Aspect ratio was the only consistently significant factor affecting flight distance.
- The optimal configuration identified was:
  - Aspect Ratio: 1.2
  - Nose Fold: 0%
  - Ballast: None
- Converting nose fold to a percentage (11.4% of plane length) improved measurement consistency.
- Ballast and wing flaps introduced variation and contributed minimally to performance improvement.
- Results demonstrated that design simplicity improved aerodynamic stability and average distance.

## Factor Significance Summary

| Factor               | Impact on Distance         | Statistical Significance |
|----------------------|----------------------------|---------------------------|
| Aspect Ratio         | Strong                     | Significant               |
| Nose Fold            | Moderate (interaction only)| Partially Significant     |
| Ballast              | Weak / inconsistent        | Not Significant           |
| Wing Flaps           | Confounded and removed     | Not Significant           |

## Methods and Technical Skills Demonstrated
- DoE methodology: half-factorial (2⁴⁻¹) and full factorial (4×2×2)
- ANOVA, residual analysis, normality and variance testing
- Uncertainty analysis and error quantification
- SolidWorks CAD validation of aspect ratio geometry
- Video-based time measurement at 30 Hz frame rate
- Consistent indoor test protocol and controlled launch design





