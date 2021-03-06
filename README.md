## KERAS-DCGAN ##



This trains two adversarial deep learning models on real images, in order to produce artificial images that look real.



The generator model tries to produce images that look real and get a high score from the discriminator.



The discriminator model tries to tell apart between real images and artificial images from the generator.




## Usage


**Training:**

 `python dcgan.py --mode train --batch_size <batch_size>`



  python dcgan.py --mode train --path ~/images --batch_size 128



**Image generation:**

`python dcgan.py --mode generate --batch_size <batch_size>`



`python dcgan.py --mode generate --batch_size <batch_size> --nice` : top 5% images according to discriminator



python dcgan.py --mode generate --batch_size 128




## Result



**generated images :** 



![generated_image.png](./assets/generated_image.png)





![nice_generated_image.png](./assets/nice_generated_image.png)





**train process :**



![training_process.gif](./assets/training_process.gif)






**Install Dependencies**

`pip3 install -r requirements.txt`
 
