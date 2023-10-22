# Pixelmind
Third position in Pixelmind, a competition in IITM's esteemed Paradox fest.
The task at hand was to use deep learning models to enhance images taken by DSLRs, akin to what's done by the professionals using Lightroom and/or photoshop. The judging criterias were the quality of enhancements done, the generalisation ability of the model and the computational efficiency with respect to the entire training+inference process.
Our approach used the pre-trained MIRNetv2 (https://github.com/swz30/MIRNetv2) with the low light enhancement mode. The novelty of this solution was that it could be run entirely on a gpu-instance(T4) colab notebook, removing the need of a high spec-gpu server for training and inference. 
Teammates:
