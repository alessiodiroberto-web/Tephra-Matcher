Browser-based tool to compare an unknown volcanic glass composition (major and trace elements, mean ± SD) with a database of Italian tephra. Ranks candidates using Borchardt's Similarity Coefficient, standardized Euclidean distance and Mahalanobis distance.

**Database Formatting Guide (Major Elements)**
To ensure your reference database is correctly parsed by **Tephra Matcher**, prepare your Excel (.xlsx) or CSV (.csv) file following the scheme below.

**Column Schema**
Column A = Eruption/unit
Column B = Age yrs BP
Column C = Age min yrs BP
Column D = Age max
Column E = Sample name
Column F = Reference
Columns G-U = raw (un-normalized) data for SiO2, TiO2, Al2O3, FeOt, MnO, MgO, CaO, Na2O, K2O, P2O5, Cl, F, SO3, Original Total, Total volatile free
Columns V-AI = Same major oxides and 3 volatiles normalized to 100 wt% 

**Data Conventions**
**Ages:** Express all ages in years BP. Leave cells blank if unknown.
**Missing Values & Qualifiers:** Leave missing measurements empty. Keep analytical qualifiers (e.g., <LOD, bdl, n.d.) as text strings **do not replace them with 0**.

**Normalization:**
If raw analytical totals are available, populate the raw data block (Cols G–U) and calculate the Normalized block (Cols V–AI) to 100 wt% on the 10 major oxides (SiO2 through P2O5, excluding volatiles Cl, F, SO).
If data were published already normalized, leave the un-normalized block empty and enter the values directly in the Normalized block.
