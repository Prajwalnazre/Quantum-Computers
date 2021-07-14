# Quantum-Computers
I have done a research project on 'Implementing Machine Learning on a Quantum Environment'.
This repo contains the Jupyter Notebook of the project as well as the paper that I have applied to publish at ICORT-2021.

The QNN (Quantum Neural Network) is being built and compared its performace to that of a CNN (Convoluted Neural Networks)
The QNN produced a result of 69 percent while the CNN produced a whopping 99.9 percent. The QNN was built on the grounds of quantum circuits and considering each image as an indvidual circuit. The computations it undergoes are complex. The loss factors needs to be optimized even further to get better results.

![QNN vs CNN Result with 100% data](https://github.com/Prajwalnazre/Quantum-Computers/blob/main/realresult.png)

A question arises as to what would happen when the data fed to both the models would be reduced. To find out, the data was halved and fed to both QNN and CNN. Interestingly, the accuracy of the QNN increased to 73 percent while that of CNN decreased significantly to 86 percent. CNN behaves bad when data fed is low while QNN took a bit of an advantage in this case. So, it is quite probable that QNN might have an application when the initial data is relatively less.


![QNN vs CNN Result with 50% data](https://github.com/Prajwalnazre/Quantum-Computers/blob/main/result4.png)
