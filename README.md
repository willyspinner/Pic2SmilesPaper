# Pic2SmilesPaper
Paper about a model that convert a chemical diagram drawing to its computer representation

I Worked with [@Leoputera2407](https://github.com/Leoputera2407) on this project. In the project, I worked on the image segmentation model to extract the chemical diagram, removing any distracting backgrounds. [@Leoputera2407](https://github.com/Leoputera2407) worked on implementing the model that convert that chemical diagram to its SMILES representation.

We implemented a bare-bones transformer from Harvard NLP group, which decodes to their SMILES representation.
We also integrated a self-critical training scheme, which uses policy gradient to optimize the model to minimize the levehstein distance between target and our predicted. All in all, we managed to get a SOTA performance of ~75+% accurancy (based on levenhstein distance). 

Check the paper out [here](https://github.com/willyspinner/Pic2SmilesPaper/blob/master/paper.pdf).
