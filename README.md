# Deep-Learning

To change the image dimension

from train_x_orig shape: (209, 64, 64, 3)  to

to 
train_x_flatten = train_x_orig.reshape(train_x_orig.shape[0], -1).T 
train_x = train_x_flatten/255

train_x's shape: (12288, 209)
