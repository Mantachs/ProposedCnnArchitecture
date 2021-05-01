# ProposedCnnArchitecture

The code present here represent the architecutre that was proposed in the following paper:
Mantach S, Ashraf A, Janani H, Kordi B. A Convolutional Neural Network-Based Model for Multi-Source and Single-Source Partial Discharge Pattern Classification Using Only Single-Source Training Set. Energies. 2021 Jan;14(5):1355.

The  main  contribution  of  this project  includes  classifying  multi-source  PDs  andsingle-source  PDs  without  introducing  multi-source  PDs  in  the  training  stage.   The motivation of this work is that collecting multi-source PDs is difficult, expensive, time consuming , and not practical in regards to the combinational nature of the PDs.  The deep learning algorithm investigated here is two dimensional convolutional neural network.  The proposed architecture is different than traditional CNN architectures, where it consists of two parts: the convolutional layers which take care of learning generalized features of all the classes, and the fully connected layers which take care of learning the fine-tuned specific features of each class.  Extensive validation of the proposed neural network architecture has been conducted by evaluating the generalization in performance as we move from training data (i.e.  single source) to unseen testing data whichis multi-source.

