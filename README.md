This repo contains some of the colab-notebooks used for portrait generation found at 
<a href="https://rp-gen.com/">rp-gan.com</a>, as well as links to the necessary modified repos.

Two models are presented there:

* A fine-tuned conditional version of Stylegan which generates faces of characters. It is capable of generating faces from classic D&D style races.
* A fine-tuned version of <a href="https://github.com/eladrich/pixel2style2pixel">pixel2style2pixel</a> which performs style transfer from images of real faces to drawn character faces in the same style as the above model.


## Notebooks

*

## Forks used

* https://github.com/snakch/stylegan2-ada-pytorch

* https://github.com/snakch/stylegan2-ada-pytorch Main changes:
    * Modified to work with conditional labels


* https://github.com/eladrich/pixel2style2pixel: A fork from the original<a href="https://github.com/eladrich/pixel2style2pixel"> pixel2style2pixel</a> repo. Changes include:
    * stuff 1
    * stuff 2



TODO:

* Modify portraitify model to perform conditional style-transfer - ie. instead of mapping human face to human portait only, one could map human face to elven-version of the same face for example.



