# Step 1: obtain DL4J
$ git clone https://github.com/deeplearning4j/dl4j-examples.git
$ cd dl4j-examples/
$ mvn clean install

# Step 2: import as maven project in your IDE 
Make sure you select the JDK instead of JRE. We'll assist you if necessary. 

# Step 3: test if it works
run class org.deeplearning4j.examples.feedforward.classification.MLPClassifierLinear.
This should almost immediately generate some visual feedback for you. 

# XOR network
The XorExample is included in the dj4j-example project. Take a look :) 

Next:
1) build the other implementation of the Xor problem that we discussed, and run it
2) dl4j can provide you with a web interface to show you some network information: use it for your network. 

# Recognizer source code: 
https://github.com/klevis/CatAndDogRecognizer

Clone the repo and simply execute by starting the run class. (first time will be slow: 500 mb of weights will be downloaded)

3) Try to find a picture of a dog or a cat (on the internet or from pictures of your pet) that can't be recognized correctly (you may adjust the treshold from 0,55 to 0,95. 

4) Inspect the source code of the recognizer application.


# Investigate!

- The dl4j example project contains loads of interesting models
- dl4j tutorials: https://deeplearning4j.org/tutorials/setup (example code is written in Scala, ignore this, type similar stuff. it works.) 
- Interesting other projects from the same author as the recognizer: http://ramok.tech/convolutional-neural-networks/

