# vehicle_acq
# Vehicle Acquisition Optimization

## Overview
This project builds a machine learning model to optimize vehicle appraisal pricing by balancing acquisition probability and expected profitability.

## Business Problem
How do we determine the optimal appraisal offer that maximizes total expected value while maintaining margin?

## Approach
- Logistic Regression / Tree-based models
- Feature engineering (offer vs wholesale)
- Simulation across pricing scenarios
- Channel comparison (Website vs Other)

## Key Insight
Increasing offers increases conversion probability but decreases margin — the optimal point balances both.

## Results
- ~90% model accuracy
- Strong ROC-AUC
- Clear tradeoff curve identified

## Files
- `DSC680VehicleAcq.ipynb` → full analysis

## Future Work
- Causal inference
- A/B testing
- Real-time pricing engine
