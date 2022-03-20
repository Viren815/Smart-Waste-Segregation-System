# Smart-Waste-Segregation-System
<h2> Introduction </h2>
<p> Massive increase in population of cities and urban areas has led to improper waste management. In today’s world, waste has become an immense problem since it usually becomes a breeding ground for insects and bacteria and results in spreading of diseases. Waste bins brimming with waste are left unattended for days and are not timely collected by the Municipal Corporation. Another problem faced is that most people do not segregate the waste while disposing and this leads to more than half of the recyclable waste going unnoticed and being added to the pile of waste even when there is a chance to recycle it. To provide solution to this pressing problem, we propose a system that helps in segregating the waste into six different categories. The proposed system will use the technologies of Machine Learning. We hope to improve the waste segregation process with our proposed system which would thereby increase the efficiency of waste segregation and recycling rates.</p>
<h2> Methodology </h2>
<h3> 1. Dataset </h3>
<p> The foundation of a machine learning project is training data that will be used to teach the machine to recognize patterns. The quality of the training depends on the quality of the data input. Not many datasets are available for the field of waste classification, so we have selected the Garbage Classification dataset which have a total of 2,537 images. This dataset is divided into 6 categories – cardboard, glass, metal, plastic, paper and trash. Garbage Classification dataset has been selected as it has high resolution images as well as diverse images taken from every angle in each category. This dataset has 1314 training set examples which is the actual dataset that we use to train the model. Validation set is used to evaluate the model for frequent evaluation, while testing set is the gold standard for evaluating the model and only used once a model is completely trained using the training and validation sets. Here, 1,117 images are present in validation set and 106 images in testing set.</p> 
The Dataset can be downloaded from the below link:

https://drive.google.com/drive/folders/1rupZ0Z1iB4RJAFvuLF0FJsGncz2NqbOd?usp=sharing
<h3> 2. Requirement </h3>
<b>For training and testing the CNN model:</b>

Software Requirement
1. Python 3.6+
2. Tensorflow
3. Numpy
4. Cv2
5. Keras
6. Matplotlib
7. Os
8. Pandas

Hardware Requirement
1. High Core CPU (Intel 4 Core i7700k +)
2. 2GB GPU or more
3. More than 4GB of DDR 4 RAM
4. 1GB Hard disk storage

<h3>3. Implementation </h3> 

![image](https://user-images.githubusercontent.com/44722997/159151661-bc620dab-e830-413f-b49d-148cb5d06704.png)

<h2> How to run the project </h2>
<ul>
  <li> The project can be ran in Colab / Jupyter notebook </li>
  <li> Before running the project change the path of the given dataset </li>
  <li> Also change the runtime to GPU to run this project faster </li>
</ul>

<h2> Results </h2>

![image](https://user-images.githubusercontent.com/44722997/159151776-1d26e9cc-937e-441d-88ae-571199afec9a.png)

<h2> Conclusion </h2> 
The proposed Smart Waste Segregation System would strive to provide an efficient solution to the waste management problem. Our system segregates waste into 6 categories i.e. metal, cardboard, paper, plastic, glass and trash. This can further facilitate in deciding what kind of recycling process the particular waste undergoes and achieving efficiency in handling all types of waste.

