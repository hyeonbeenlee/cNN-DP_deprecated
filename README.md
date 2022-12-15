# cNN-DP: Composite neural network with differential propagation for impulsive nonlinear dynamics
*Lee, Hyeonbeen and Han, Seongji and Choi, Hee-Sun and Kim, Jin-Gyun, Cnn-Dp: Composite Neural Network with Differential Propagation For Impulsive Nonlinear Dynamics. Available at SSRN: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4296911*
  
![NN_conv_autograd](https://user-images.githubusercontent.com/78078652/204765197-5df81c5c-53c0-407f-988c-9ff8e68fadff.png)
![NN_cnnDP](https://user-images.githubusercontent.com/78078652/204765201-18266aa6-343f-40bd-9b41-c429c86a8d99.png)
## Abstract
In mechanical engineering, abundant high-quality data from simulations and experimental observations can help develop practical and accurate data-driven models. However, when dynamics are complex and highly nonlinear, designing a suitable model and optimizing it accurately is challenging. In particular, when data comprise impulsive signals or high-frequency components, training a data-driven model becomes increasingly challenging. This study proposes a novel and robust composite neural network for impulsive time-transient dynamics by dividing the prediction of the dynamics into tasks for three sub-networks, one for approximating simplified dynamics and the other two for mapping lower-order derivatives to higher-order derivatives. The mapping serves as the temporal differential operator, hence, the name “composite neural network with differential propagation (cNN-DP)” for the suggested model. Furthermore, numerical investigations were conducted to compare cNN-DP with two baseline models, a conventional network and another employing the autogradient approach. Regarding the convergence rate of model optimizations and the generalization accuracy, the proposed network outperformed the baseline models by many orders of magnitude. In terms of computational efficiency, numerical tests showed that cNN-DP requires an acceptable and comparable computational load. Although the numerical studies and descriptions focus on accelerations, the proposed network can be easily extended to any other application involving impulsive data.
