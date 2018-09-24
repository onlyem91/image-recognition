# Step 1: obtain DL4J
$ git clone https://github.com/deeplearning4j/dl4j-examples.git
$ cd dl4j-examples/
$ mvn clean install

# Step 2: import as maven project in your IDE 
Make sure you select the JDK instead of JRE. We'll assist you if necessary. 

# Step 3: test if it works
run class org.deeplearning4j.examples.feedforward.classification.MLPClassifierLinear.
This should almost immediately generate some visual feedback for you. 


# Recognizer source code: https://github.com/klevis/CatAndDogRecognizer
Simply execute bij starting the run class. (first time will be slow: 500 mb of weights will be downloaded)
Interesting other projects from the same author: http://ramok.tech/convolutional-neural-networks/






