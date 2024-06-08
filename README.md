# Predicting Young's Modulus of Rocks Using Neural Networks

Rocks, the fundamental building blocks of the Earth's crust, exhibit a diverse range of mechanical properties that significantly influence various engineering endeavors, from construction to mining and beyond. Among these properties, Young's modulus stands out as a key parameter characterizing a rock's stiffness or resistance to deformation under applied stress. Understanding and accurately predicting Young's modulus of rocks is crucial for ensuring the safety and stability of civil engineering structures, geological formations, and industrial processes.

Traditionally, estimating Young's modulus of rocks has relied on empirical correlations derived from laboratory experiments, which are often time-consuming, expensive, and may not capture the full complexity of real-world conditions. In recent years, however, there has been a growing interest in leveraging machine learning (ML) techniques to predict Young's modulus with greater efficiency and accuracy.

## Results of Neural Networks

- The optimal configuration with 83 neurons in the hidden layer resulted in an impressive R^2 value of 77%, indicating a strong correlation between predicted and actual values.
- This finding underscores the predictive capability of our ANN architecture in rock engineering applications.
- Pinpointing the optimal number of neurons has allowed us to optimize our model for delivering accurate and reliable predictions.
- The iterative refinement process is visually represented in Figure 2, illustrating the impact of varying neuron count on model performance.
- Neural networks were not as beneficial due to the limited availability of data.
- The cooling parameter was excluded from consideration, as both literature review and testing indicated its insignificant effect on the final ANN model.
- Data augmentation was attempted; however, generating synthetic data for lab-scale testing proved ineffective due to the generation of ambiguous values within the specified range.
- Despite the challenges faced, neural networks remain a promising avenue for future exploration, particularly with larger datasets.

## Conclusion

The application of neural networks for predicting Young's modulus in rocks has shown promising results, with the optimal configuration achieving a strong correlation between predicted and actual values. While the limited availability of data poses a challenge, the potential for future improvements with larger datasets is significant.

## Future Work

- Explore the use of larger datasets to improve the predictive accuracy of neural networks.
- Investigate other machine learning techniques to complement and enhance the predictive capabilities of the model.
- Continue refining the ANN architecture to optimize performance for specific rock types and conditions.
