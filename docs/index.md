# Neural Network on Microcontroller (NNoM)

NNoM is a higher-level layer-based Neural Network library specifically for microcontrollers. 

Highlights

- Deploy Keras model to NNoM model with one line of code.
- Support complex structures; Inception, ResNet, DenseNet...
- High-performance backend selections.
- Onboard (MCU) evaluation tools; Runtime analysis, Top-k, Confusion matrix... 


[The temporary guide](A%20Temporary%20Guide%20to%20NNoM)

[Porting and optimising Guide](Porting%20and%20Optimisation%20Guide)

---

## Why NNoM?
The aims of NNoM is to provide a light-weight, user-friendly and flexible interface for fast deploying.

Nowadays, neural networks are **wider**, **deeper**, and **denser**.
![](figures/nnom_wdd.png)
>[1] Szegedy, C., Liu, W., Jia, Y., Sermanet, P., Reed, S., Anguelov, D., ... & Rabinovich, A. (2015). Going deeper with convolutions. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 1-9).
>
>[2] He, K., Zhang, X., Ren, S., & Sun, J. (2016). Deep residual learning for image recognition. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 770-778).
>
>[3] Huang, G., Liu, Z., Van Der Maaten, L., & Weinberger, K. Q. (2017). Densely connected convolutional networks. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 4700-4708).


**If you would like to try those more up-to-date, decent and complex structures on MCU** 

**NNoM can help you to build them with only a few lines of C codes**, same as you did with Python in [**Keras**](https://keras.io/)

---

## Dependencies

NNoM now use the local pure C backend implementation by default. Thus, there is no special dependency needed. 

## Optimization
You can select [CMSIS-NN/DSP](https://github.com/ARM-software/CMSIS_5/tree/develop/CMSIS/NN) as the backend for about 5x performance with ARM-Cortex-M4/7/33/35P. 

Check [Porting and optimising Guide](Porting%20and%20Optimisation%20Guide) for detail. 