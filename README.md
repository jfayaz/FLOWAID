# FLOWAID (Flow and Leakage Forecasting using Weather-Adaptive neural network for Intelligent Decision-making)


FLOWAID (Flow and Leakage Forecasting using Weather-Adaptive neural network for Intelligent Decision-making) model is designed to enhance water flow forecasting and enable proactive leak detection in water distribution systems. The model leverages convolutional residual networks for hierarchical feature extraction, bidirectional long short-term memory cells for temporal context, and multi-layer perceptron for a unified prediction of water flow demand and leakage probability. A novel class-specific attention mechanism is introduced which prioritizes features relevant to the underrepresented leakage class. 


The FLOWAID model utilizes five days of preceding water flow and weather data (including temperature, precipitation, specific and relative humidities, evaporation, and solar radiation) to generate dual output predictions, including water flow demands for the next 12 hours and corresponding leakage probability.


Reference:
          
    Jawad Fayaz, Lauren McMillan, Vivian Cardenas, and Liz Varga (under review). “An Interpretable Unified Attention-Based Neural Network for Real-Time Weather-Adaptive Water Flow Forecasting and Leak Detection”
