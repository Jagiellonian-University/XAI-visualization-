#  Paper Collections on advanced methods for visualization of XAI.
The baseline approach is LUX that uses the decision tree visualization. We have listed the visualization techniques that are common in XAI field.. 

The sharing principle of these references here is for research. If any authors do not want their paper to be listed here, please feel free to contact [Usman Akhtar] (Email: usman.akhtar@uj.edu.pl).

 XAI (Explainable Artificial Intelligence) aims to provide insights into how machine learning models make decisions, especially in complex or black-box models. Advanced visualization techniques play a crucial role in making these explanations more interpretable and accessible to humans. Here are some advanced methods for visualizing XAI:
 1. **LIME (Local Interpretable Model-agnostic Explanations)**
    LIME explains the predictions of machine learning models by approximating them with a locally interpretable model (e.g., linear regression) around a specific instance. LIME generates visualizations to 
    highlight influential features and their impact on the prediction for that instance.
 2. **LIME (SHAP (SHapley Additive exPlanations))**
    SHAP values are based on cooperative game theory and assign each feature an importance score in a way that guarantees fairness and consistency. Visualization using SHAP provides a detailed understanding of 
    how each feature contributes to a model's output for a specific instance.
 3. **Integrated Gradients**
    This method calculates the integral of the model's gradients with respect to the input features along a straight path from a baseline (e.g., all zeros) to the current input. The resulting visualization 
    shows feature attributions for the prediction.
 4. **Saliency Maps**
    Saliency maps highlight the most relevant regions in an input that contributed to a model's prediction. In deep learning, these maps are generated by computing gradients of the output with respect to the 
    input features.
 5. **Activation Maps (e.g., Grad-CAM)**
    Gradient-weighted Class Activation Mapping (Grad-CAM) visually shows which regions in an input image were most relevant to a model's prediction by highlighting regions that were active in the final 
    convolutional layer.
 6. **Attention Mechanisms** 
    Attention mechanisms visualize the attention weights assigned to different parts of the input when processing sequences (e.g., text or images). Attention maps provide insights into how the model attends to 
    specific elements during prediction.
 7. **Counterfactual Explanations** 
    Counterfactual explanations show what changes in the input would lead to a different prediction. Visualizing these counterfactuals helps in understanding how minor modifications can affect the model's 
    decisions.
 8. **Decision Trees and Rule Extraction** 
    For interpretable models like decision trees, visualizing the decision paths and rules provides a clear understanding of how the model makes predictions.
 9. **Layer-wise Relevance Propagation (LRP)** 
    LRP attributes relevance to each neuron or unit in a neural network layer and propagates this relevance back to input features. Visualization of relevance scores helps understand how different features 
    contribute to the model's output.
 10. **Network Dissection**  
    Network Dissection visualizes the parts of a neural network that correspond to semantically meaningful concepts, providing insights into the model's internal representations.
 11. **Interactive Visualization Tools**  
    Building interactive visualization tools that allow users to explore and manipulate the model's behavior can enhance understanding and trust in AI systems.
 12.  **Graph-based Visualization**  
    For models dealing with graph-structured data (e.g., social networks, molecular structures), visualization techniques that represent graphs and highlight important nodes or edges can aid in explaining the 
    model's predictions.

These advanced visualization methods play a crucial role in improving the transparency, interpretability, and trustworthiness of AI models, making them more accessible and understandable to both experts and non-experts.

## Overview
* [Research Papers](#Research-Papers)
* [Visual XAI](#Visual-XAI)
* [Human in the loop (XAI/AI)](#Human-in-the-loop)
* [Argumentative XAI](#Argumentative-XAI)



## Research Papers

#### Visual XAI

1. **A survey of visual analytics for Explainable Artificial Intelligence methods**
*Alicioglu, Gulsum, and Bo Sun.* Computers & Graphics, 2022. [paper](https://www.sciencedirect.com/science/article/pii/S0097849321001886) 

2. **Comparative evaluation of contribution-value plots for machine learning understanding**
*Collaris, Dennis, and Jarke J. van Wijk.* Journal of Visualization, 2022. [paper](https://doi.org/10.4230/OASIcs.ATMOS.2017.1)


### Human in the loop (XAI/AI)

1. **A comprehensive review on resolving ambiguities in natural language processing**
*Yadav, Apurwa, Aarshil Patel, and Manan Shah* AI Open, 2021. [paper](https://www.sciencedirect.com/science/article/pii/S2666651021000127)


## Argumentative XAI

1. **A Novel Human-Centred Evaluation Approach and an Argument-Based Method for Explainable Artificial Intelligence**
*Vilone, Giulia, and Luca Longo* IFIP International Conference on Artificial Intelligence Applications and Innovations, 2002. [book](https://link.springer.com/chapter/10.1007/978-3-031-08333-4_36)
    

