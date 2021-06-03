# Machine Learning

Below you will find anything and everything pertaining to the Machine Learning Portion of this project. Before reading, please the the ~5 minute overview video. Goals, Objectives,
and Implementations are explained their.  


### Introduction Video

Machine Learning Overview Presenatation  
<pre>
<a href="https://youtu.be/zTTHPHJ2c48" target="_blank"><img src="http://img.youtube.com/vi/zTTHPHJ2c48/0.jpg"
alt="IMAGE ALT TEXT HERE" width="350" height="250" border="10" /></a>
</pre>

### Demo Video of Inferenced Model Recommender

Posted by end of June 3rd, 2021  


### LSTM Model Explanation

The goal of LSTM netorks is to solve the issue of memory in both Regressive and Classification models. This is done by sequentially adding LSTM nodes that are meant to mimic human neurons. The following image is an example of an LSTM neuron.

<p align="center">
  <img width="800" height="300" src="https://cdn.analyticsvidhya.com/wp-content/uploads/2017/12/10131302/13.png">
</p>
<strong>sub_t</strong>: Is moment in time, remember that LSTM's are meant to make decisions based on previous inputs.<br>
<strong>h_t</strong>: Hidden Layer of LSTM<br>
<strong>C_t</strong>: Can be seen as the out for a given layer<br>
<strong>X_t-n</strong>: Is the input for that given layer in reference to time n. Again predictions are made by looking back in time. You can decide the N, which implies
 how much does the model  remember.<br>
 
 #### <strong>Shortcomings</strong><br>
 While this model did serve to be dynamic, the given state is struggling to generalize. We believe this was because of the format of our given dataset. The given model was built as a multi-classification model which needs for any given input, please give me a vector of 0's and 1's. 1's implying a correct next chord, and 0's implying not a 'good' next chord. In its given state, each input only has one classifiction. (I.E. Only one, 1), but we have multiple inputs that are equal. We believe this was creating confusion, and requires tweaking to get better results.
 
 #### <strong>Next Steps</strong><br>
 Along with updating the dataset, we would like to use a GAN approach to hopefully create a generator model that is even better than the LSTM. For more information on GAN's please click the following link.<br>
<a href="https://wiki.pathmind.com/generative-adversarial-network-gan#:~:text=Generative%20adversarial%20networks%20(GANs)%20are,video%20generation%20and%20voice%20generation.">GAN Basics Link</a>

### Static Binary Tree/Forest Model

Explained in video, but more information will be provided in the future  

