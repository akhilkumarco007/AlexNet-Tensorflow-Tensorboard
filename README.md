# AlexNet-Tensorflow-Tensorboard
Implementation of AlexNet (CNN designed by Alex Krizhevsky) in Tensorflow+Tensorboard

The Network had a very similar architecture to LeNet (developed by Yann LeCun in 1990’s), but was deeper, bigger, and featured Convolutional Layers stacked on top of each other (previously it was common to only have a single CONV layer always immediately followed by a POOL layer).

Here, I changed the network to fit the MNIST dataset (the original network which was designed for ImageNet data)
You can load other inputs by modifying load_input.py file. You may also simply change the network architecture (e.g. changing the number of layers, stride value, kernel sizes, etc.) through alexnet_model.py and ops.py files.


## Training 
```
python MainCode.py 
```

## Reference paper: 
http://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks

## Nice slides on AlexNet
http://vision.stanford.edu/teaching/cs231b_spring1415/slides/alexnet_tugce_kyunghee.pdf
