# CareLens Architecture

## Overall Flow

User
↓
Health Inputs
↓
Data Validation & Preprocessing
↓
Safety Rule Layer
↓
ML Screening Engine
↓
Explainability Layer
↓
Risk / Attention Level
↓
Recommended Next Step
↓
Doctor-Visit Health Summary

## Core Design

CareLens uses a hybrid approach:

Safety Rules + Machine Learning

The safety-rule layer handles predefined safety-critical situations,
while the ML model provides screening classification for other cases.

CareLens is a screening and care-navigation tool,
not a diagnostic system.