# Introduction to Artificaial Neural Networks with Keras
![artificial-intelligence-1079012838-6ee85656ad2047f08371f47bd26f1b64](https://user-images.githubusercontent.com/62572088/235944251-a033b651-e39a-494d-96cf-42164857660a.jpg)
"Birds inspired us to floy ,burdouck inspired velco , and nature has inspired  countless  more inventions .It  seems only logical then, to look at the brains's architecture for inspiration on how to build an inteligent machine . <u>This is the logic that sparked artificial neural networks (ANNs):an ANN is a Machine Learning model inspired by the networks of biological neurons found in our brain <br>
# Biological Neuron 
A human brain has billions of neurons. Neurons are interconnected nerve cells in the human brain that are involved in processing and transmitting chemical and electrical signals. Dendrites are branches that receive information from other neurons.
![A1](https://user-images.githubusercontent.com/62572088/235947079-be02dec4-1279-4eda-a6e5-2b077d314e8f.png)
  Thus, individual biological neurons seem to behave in rather simple way but they are oranized in a vast network of billions with each neuron typically connected to thousands of other  neurons ,much like a complex computational anthill can emerge from the network of fairly simple neurons ants.
  # Rise of Artificial Neurons (Based on Biological Neuron)
  McCulloch and pitts proposed a very simple model of the biological neuron:it has one or  more binary(on/off)inputs and one binary output  ,which later became known aas artificial neuron activates its output when more than certain number of its inputs are active . 
  # What is Artificial Neuron
  An artificial neuron is a mathematical function based on a model of biological neurons, where each neuron takes inputs, weighs them separately, sums them up and passes this sum through a nonlinear function to produce output.
  
  
![vector-scientific-tech-icon-structure-600w-1390920110](https://user-images.githubusercontent.com/62572088/236154280-14b9bd4c-62eb-4658-958b-fc8cfc714a2b.jpg)
  # Biological Neuron vs. Artificial Neuron
  ![1_BRRH7w1DaPkThDHERNv5Ig](https://user-images.githubusercontent.com/62572088/235954566-f783c4c5-bec6-4b90-9e70-decff51568f6.png)
# The Perceptron
 The Perceptron is one of the simplest ANN architecture ,invented in 1957 iby frank Rosenblatt.it is based on a slightly different artificial neuron  called a threshold logic unit (TLU),or something a linear threshold unit (LTU) A Perceptron is an algorithm for supervised learning of binary classifiers. This algorithm enables neurons to learn and processes elements in the training set one at a time.
  
![general-diagram-of-perceptron-for-supervised-learning_4](https://user-images.githubusercontent.com/62572088/235954997-994bd0cc-4514-4eae-8943-e7b53c4eb630.jpg)
The most common step function used in perceptrons is Heavise step funtion .Sometimes the sign  function is used insted .
There are many functions u will see in DL .IF you want to learn more about The Perceptron .You can see this <a href="https://www.simplilearn.com/tutorials/deep-learning-tutorial/perceptron#biological_neuron">The Perceptron</a>
know you can see the implementation of The Perceptron <b>prec.ipynb</b>
  
![Perceptron_36](https://user-images.githubusercontent.com/62572088/235965311-5b166472-6308-40b2-b1c5-309aa3d71480.jpg)

in fact ,Scikit-Learn's perceptron class is equivelent to using  an SGDClassifier with some specific paramenters 
in 1969 they found number of weakness of perceprtons .They are incaple of solving some trivial problems (e.g,The Exclusive OR(XOR))classification problem.They found that limitations of Perceptrons can by eliminated by stacking Multilayer  Perceptron(MLP)
# the Multiplayer Perceptron & Backprobagation 
An MLP is compused of one (Passthrough) input layer ,one or more layers fo TLUs,called hidden layers of TLUs called output layer 
![multi-layer-perceptron-in-tensorflow (2)](https://user-images.githubusercontent.com/62572088/236154973-5783f644-eddd-4657-b37f-4223d617e76e.png)
