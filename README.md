# OpenCv
This is used to display images in Python

Inorder to use opencv in Jupyter notebook you have to install it in ananconda terminal using
pip install opencv-python 
i have done the installation part in my jupyter notbook you can follow that to install it on your jupyter notbook
Then further we have used matplotlib in the project so you can install it using
pip install matplotlib
then import it

Inititialy when u display a image using
plt.imshow() method you will get the image in BGR color something show below
![firstimage](https://user-images.githubusercontent.com/42214175/70439960-20367a80-1ab7-11ea-8e0b-c3371a13a7ec.png)


so you can change the color to RGB color using 
cvtColor(COLOR_BGR2RGB)
plt.imshow(img2)
# To understand this please open the attached jupyter notebook doc     



After this the output will change to orginal color
