# Exit Velocity vs Offensive Performance

This project analyzes whether hitters with higher average exit velocity tend to produce better offensive results, measured by wOBA.

## Data
- Source: MLB Statcast (via pybaseball)
- Season: 2024
- Sample: Hitters with at least 100 balls in play

## Method
- Calculated average exit velocity and average wOBA per hitter
- Fit a linear regression to estimate expected performance
- Identified overperformers and underperformers using residuals

## Key Findings
- Higher exit velocity is positively correlated with wOBA
- Several hitters significantly outperform or underperform expectations
- Exit velocity alone does not fully explain offensive success

## Files
- `exit_velocity_vs_performance.ipynb`: full analysis and visualizations

