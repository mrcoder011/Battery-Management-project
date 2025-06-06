# EV/Hybrid Range Simulator with Battery Load Analysis

![Project Screenshot](screenshot.png)

This web application simulates how different electrical loads affect the driving range of electric and hybrid vehicles. It combines physics-based calculations with machine learning to provide accurate range predictions based on various parameters.

## Features

- **Vehicle Type Selection**: Choose between Pure EV or Hybrid
- **Interactive Controls**:
  - Driving Speed (20-120 km/h).
  - Climate Control Load (0-5 kW)
  - Terrain Elevation (Flat to Mountainous)
  - Battery Capacity (40-120 kWh)
- **Real-time Visualizations**:.
  - Animated vehicle that moves according to selected speed
  - Dynamic range calculation display
  - Performance metrics chart
- **Machine Learning Integration**:
  - TensorFlow.js neural network for enhanced predictions
  - Confidence indicator for ML predictions
- **Educational Content**:
  - Explanation of how different factors affect range
  - Comparison between EV and hybrid performance
  - Insights on driving operations and energy efficiency

## How It Works

### Physics-Based Model
The application uses physics-based calculations to estimate range:
- **Speed Impact**: Aerodynamic drag increases with speed
- **Climate Control**: Direct energy consumption.
- **Terrain**: Energy requirements for elevation changes
- **Battery Capacity**: Total available energy

### Machine Learning Model
The application uses TensorFlow.js to:
1. Create a neural network model
2. Train the model on synthetic driving data
3. Blend ML predictions with physics-based calculations
4. Continuously improve accuracy

### Visualization
- Vehicle animation shows real-time movement
- Performance chart displays key metrics
- Color-coded UI elements indicate system status

## Setup Instructions

1. Create a project directory:
```bash
mkdir ev-range-simulator
cd ev-range-simulator
