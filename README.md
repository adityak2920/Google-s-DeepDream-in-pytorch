# Google's DeepDream in pytorch

We train an artificial neural network by showing it millions of training examples and gradually adjusting the network parameters until it gives the classifications we want. The network typically consists of 10-30 stacked layers of artificial neurons. Each image is fed into the input layer, which then talks to the next layer, until eventually the “output” layer is reached. The network’s “answer” comes from this final output layer.
for the further reading from google ai blog
https://ai.googleblog.com/2015/06/inceptionism-going-deeper-into-neural.html

In my code i have just shown a simple representation of deep dream using pytorch pretrained VGG16 mode we can also try with some other CNN archtectures like VGG19, AlexNet, Inception some of the results to show what it does(these results are of google) and what we can achieve through deepdream are below:

![screen shot 2018-09-23 at 1 04 42 am](https://user-images.githubusercontent.com/35501699/45921110-cf942b00-becc-11e8-99b5-71ba3528832d.png)
![screen shot 2018-09-23 at 1 05 11 am](https://user-images.githubusercontent.com/35501699/45921111-d02cc180-becc-11e8-9bf2-166fee42c8cf.png)


Some screenshots from the results of my professor training using the same code but he had trained on GPU are below:

![screen shot 2018-09-23 at 1 13 39 am](https://user-images.githubusercontent.com/35501699/45921162-f737c300-becd-11e8-9382-707599c28de4.png)

Note: I have trained my model on cpu that's why results are not good so if it's trained on GPU's then it will start showing some preety good results.
