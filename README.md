## GANs FashionMNIST with PyTorchLightning

#### FashionMNIST Dataset
![Screen Shot 2022-10-29 at 2 10 07 PM](https://user-images.githubusercontent.com/90480106/198849480-dc561c80-3685-4afe-a238-657512083fd4.png)

Class names: T-shirt/top, Trouser, Pullover, Dress , Coat, Sandal, Shirt, Sneaker, Bag, Ankle Boot

#### Generative Adversarial Networks (GANs)
![gan_schema](https://user-images.githubusercontent.com/90480106/198849677-9881e3e1-6db8-406e-a185-17c32782b048.png)

##### Generator: Generate fake data and make them look like the real images.
##### Discrimator: Detect whether the input image is fake or not.

#### Our outputs after training 50 epochs
![Screen Shot 2022-10-29 at 2 09 19 PM](https://user-images.githubusercontent.com/90480106/198849841-85810888-7641-4e73-987d-dae68b29eb4a.png)

The first image looks like an Ankle Boot. (A little hard to recognize)

The second image looks like a Pullover.

The third image looks like a pair of trousers. (A little hard to recognize)

The fourth image looks like a Bag.

The fifth image looks like a Pullover.

The last image looks like a Sneaker.

#### Reference:
https://wiki.pathmind.com/generative-adversarial-network-gan
https://pytorch-lightning.readthedocs.io/en/stable/notebooks/lightning_examples/basic-gan.html
