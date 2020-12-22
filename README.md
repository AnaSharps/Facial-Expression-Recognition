# Facial-Expressions-Recognition

# Introduction #
People tend to listen to music based on their mood and interests. Studies have shown that music has a direct effect on moods of humans.   
The human face acts as the main indicator for the behavioral and the emotional state of the individual. Facial expression can be recognized to detect the mood of a person.  
It can further be used to make suggestions for music as it is often a tedious job to search from a huge number of songs present now-a-days on internet.  
We present a model which eliminates the time-consuming and the tedious work of manually playing the songs from any playlist available on the Web after detecting the mood of the individual.  

# Dependencies #
   sklearn  
   Tensorflow  
   Keras  
   Pillow

# Running Code #
1. To download the dependencies run the following code in terminal: 
  ```
    pip install -r requirements.txt
  ```
2. Now test facial expressions using various models:  
  a. Using CNN: run CNN/main.py  
 b. Using ResNet-50:   
      -- Download trained model from [here](https://drive.google.com/file/d/1KJhlFYyLkwaUypJg35xIFbZS2B0meGDq/view?usp=sharing) in models directory  
      -- run ```python ResNet50/resnet.py```   
  c. Using VGG16:   
      -- Download trained model from [here](https://drive.google.com/file/d/1S5SvTpzJTCW29hNy2HEn0XWaEQsvo-Nh/view?usp=sharing) in models directory   
      -- run ```python VGG16/vgg_test.py```    
  d. Using pseudo-labeling: run Pseudo_Labeling/pseudo_test.py  
