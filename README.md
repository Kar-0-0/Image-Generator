# Generative Adversarial Models (GANs)
- Goal of this method is to create two networks that
- One network creates synthetic images similar to the dataset in hopes that it tricks the other network 
- The other network outputs a probability of how likely the image inputted is a a part of the dataset

- There are two Networks
    - Generator
        - This is a 2 layer MLP that generates random samples similar to the images in the dataset
        - This network's goal is to trick the Discrimantor that is trying to guess if the inputted image is a part of the real dataset 
    - Discriminator
        - This is also a 2 layer MLP that takes in an image and outputs a probability of how likely it is that it's a part of the dataset 

- Both these networks are essentially pitted against each other like a game (Hints the word "Adversarial")
