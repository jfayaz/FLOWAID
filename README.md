# FLOWAID (Flow and Leakage Forecasting using Weather-Adaptive neural network for Intelligent Decision-making)


FLOWAID (Flow and Leakage Forecasting using Weather-Adaptive neural network for Intelligent Decision-making) model is designed to enhance water flow forecasting and enable proactive leak detection in water distribution systems. The model leverages convolutional residual networks for hierarchical feature extraction, bidirectional long short-term memory cells for temporal context, and multi-layer perceptron for a unified prediction of water flow demand and leakage probability. A novel class-specific attention mechanism is introduced which prioritizes features relevant to the underrepresented leakage class. 

![image](https://github.com/user-attachments/assets/4be8e7cb-ba20-4e8d-82eb-2e68ba05a5b0)


The FLOWAID model utilizes five days of preceding water flow and weather data (including temperature, precipitation, specific and relative humidities, evaporation, and solar radiation) to generate dual output predictions, including water flow demands for the next 12 hours and corresponding leakage probability.


Download the model and Jupyter-notebook from the following Dropbox link

          https://www.dropbox.com/scl/fo/w9u44kwur2xpujzvnduge/AGkRDGGHUCt8WHG_9sUXM6Y?rlkey=f5vvw31wws7f2rn59ywwmzwre&dl=0

Reference:
          
    Jawad Fayaz, Lauren McMillan, Vivian Cardenas, and Liz Varga (under review). “An Interpretable Unified Attention-Based Neural Network for Real-Time Weather-Adaptive Water Flow Forecasting and Leak Detection”
