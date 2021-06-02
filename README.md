# entretiens
This project is for hand written digits recognition 
I'am using jupyter-notebook so that the project will be more interactive 
(if u already have jupyter-notebook u can go to step 1)
To execute the programme you need first to install anaconda to access to jupyter notebook . (use this link : https://www.anaconda.com/products/individual )
after that you can use the  commands if you are using Linux : 
bash ~/Downloads/Anaconda3-2021.05-Linux-x86_64.sh
source .bashrc
anaconda-navigator

# step 1:
download test and train images and their labels from the link http://yann.lecun.com/exdb/mnist/ and extract them.
Launch jupyter notebook  , upload the jupyter  file called here (deep move entretien 2.ipynb) , and upload train and test images and labels 
# step 2:
download all the package (numpy, idx2numpy , matplotlib , tensorflow ,sklern ) using pip3 install + $name of the package
# step 3:
Execute the cells one by one 

# step 4:
you can after that call the function predict(image) on you're choosing image (here i tried with X_test[0]). 
And it will display to you the number on your image and a bar plot containing the probabilities .
