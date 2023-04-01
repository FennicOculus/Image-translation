# Image Translation AutoEncoders
In this repo, I'll try to make a model that takes an image in a given domain A (Real face for exemple) and translate it to a different domain B (cartoon/anime domaine).  
My first test will be using auto encoders to do it, I'll train an AE to reconstruct a real face image, then do the same with cartoon. Once i have the two models, I'll swap the encoders and see the result.  
I'll also explore other options like VAE, CycleGan and UNIT models in the future.    




# TODO
- [X] Make a basic auto encoder.
- [X] Training two AE on different datasets.
    - [X] Anime Face Dataset.
    - [X] CelebA Dataset. 
    - [X] Combination.
