# Behavioral-Emission-Impacts-of-Multimodal Accessability Improvements-via-Utility-Based-Mode-Choice-Modeling
This research proposes a behaviorally grounded framework that links: Infrastructure configuration → Mode utility → Mode choice probability → System-level emissions, cost, time, and exposure outcomes. The study uses New York City as an empirical testbed.

# ============================================================
# NYC-Connected County Flows (FULLY SYMMETRIC, NY+NJ+CT LODES OD)
# + 95% FILTER (by total connected trips T = P + A)
# + Flow lines between filtered counties
# + Low-flow lines colored RED
# + Directional arrowheads
#
# Definitions (NYC = 5 county-boroughs):
#   P(county) = total flow county -> NYC  (production to NYC)
#   A(county) = total flow NYC -> county  (attraction from NYC)
#   T(county) = P + A  (total NYC-connected volume for that county)
#
# Filtering:
#   Keep counties that cumulatively account for 95% of total T (plus always keep NYC)
#   Then draw ALL NYC-connected OD pairs among the kept counties.
#
# Notes:
# - Arrowheads on a huge number of lines can get slow/cluttered.
#   Use TOP_LINE_PAIRS / MAX_ARROWS if needed.
# ============================================================