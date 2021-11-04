# Introduction to RunwayML

## Session A: Generative Adversarial Networks, Semantic Maps

### Objectives

- Understand the basics of how the GANs and Image Colorization models in RunwayML work
- Develop high-level understandings of nonlinear dimensionality reductions and the latent space.
- Understand how GANs can be applied to interactive systems to generate imagery.
- [GAN Slides](https://docs.google.com/presentation/d/1nH4trgM66rWpD6kUmnPXj7uuoyPLSa6faVEanmc8K1k/edit?usp=sharing)

### Additional references

- [Google's A.I. Experiments: Visualizing High-Dimensional Space](https://www.youtube.com/watch?v=wvsE8jm1GzE)
- [Using Artificial Intelligence to Augment Human Intelligence](https://distill.pub/2017/aia/) by Shan Carter (see the first three sections for latent space descriptions)
- Octavio Good on [Generative Adversarial Networks](https://www.youtube.com/watch?v=Oqm9vsf_hvU&feature=youtu.be&t=1313) (21:54 - 28:35)
- [GAN Lab](https://poloclub.github.io/ganlab/) by Minsuk Kahng, Nikhil Thorat, Polo Chau, Fernanda Viégas, and Martin Wattenberg
- [In the Age of A.I., Is Seeing Still Believing?](https://www.newyorker.com/magazine/2018/11/12/in-the-age-of-ai-is-seeing-still-believing) by Joshua Rothman

### Creative GAN projects

- [Playing a game of GANstruction](https://thegradient.pub/playing-a-game-of-ganstruction/) by Helena Sarin ([2019 Eyeo Talk](https://vimeo.com/354276365)]
- [Misremembering and Mistranslating: GANs in Art Context](http://annaridler.com/gans-in-art) and [Fall of the House of Usher](http://annaridler.com/fall-of-the-house-of-usher) by Anna Ridler
- [Using AI to Produce “Impossible” Tulips: Anna Ridler uses AI to bring “tulipmania” into the future](https://hyperallergic.com/487261/anna-ridler-tulipmania/) by Elain Ayers
- Mario Klingemann’s Neurography: [Cameraless Photography with Neural Networks](https://www.youtube.com/watch?v=21W5-q5YYjw)
- [Booksby.ai](https://booksby.ai/about/) by Andreas Refsgaard and Mikkel Thybo Loose
- [Unfinished](https://aiartists.org/roman-lipski) by Roman Lipski
- [Blackberry Winter](https://christianmioloclair.com/blackberrywinter) by Christian Mio Loclair
- [Meet AICAN, a machine that operates as an autonomous artist](https://www.interaliamag.org/articles/ahmed-elgammal/)

### Semantic Maps / Image Synthesis

- [Semantic Image Synthesis with Spatially-Adaptive Normalization](https://nvlabs.github.io/SPADE/), [original SPADE paper](https://arxiv.org/pdf/1903.07291.pdf) paper
- [GAUGan online demo](http://nvidia-research-mingyuliu.com/gaugan/)
- [Learning to See](http://www.memo.tv/portfolio/learning-to-see/) by Memo Akten
- [Uncanny Road](https://cvalenzuelab.com/uncannyrd/) by Anastasis Germanidis and Cristóbal Valenzuela
- [AI Lab Workshop: Painting Landscapes with the Body](https://github.com/ellennickles/painting-landscapes-with-the-body)

## Session B: Model Training, Hosted Models and Networking

### Objectives

- Learn how to integrate RunwayML with JavaScript and other software applications.
- Learn how to train your own StyleGAN model in RunwayML.
- Explore additional model training such as GPT-2 text generation and Object Detection.

### Training Resources

- 🐭 [Computer Mouse Conference GAN presentation and resources](https://thecodingtrain.com/more/talks/mouse-learning.html)
- 📄 [RunwayML Image Generation Model Training](https://learn.runwayml.com/#/create/train-image-generation)
- 📄 [RunwayML Object Detection Model Training](https://learn.runwayml.com/#/create/train-object-detection)
- 🎥 [Training StyleGAN machine learning models in Runway](https://youtu.be/vM8Cv8CLmr0) from Artificial Images
- 💻 [Processing Cube Generator](https://gist.github.com/shiffman/ada9c7003f1a042d31a675f1d95a1876)
- 🖼 [Google Images Download](https://github.com/Joeclinton1/google-images-download)
- 🖼 [Flickr Scrape](https://github.com/antiboredom/flickr-scrape)

### Hosted Model Resources

- [Hosted Models](https://learn.runwayml.com/#/how-to/hosted-models)
- [Interact with models in RunwayML over the network](https://learn.runwayml.com/#/how-to/network)
- [Networking examples and tutorials, organized by software application](https://learn.runwayml.com/#/networking/examples)

### Reading

- 📖 [On Lacework: watching an entire machine-learning dataset](https://unthinking.photography/articles/on-lacework) by Everest Pipkin

### Code Examples

- [Glitch! RunwayML template - StyleGAN](https://glitch.com/edit/#!/runway-ml-template)
- [Glitch! RunwayML StyleGAN walk](https://glitch.com/edit/#!/latent-sky-walk)
- [All Glitch + RunwayML templates](https://glitch.com/@daniel83693/runway-ml-templates)

### Assignment (Due Monday, Nov 9):

Choose one of the following options! You could also combine them by training your own model and connecting it to p5.js! Continue your reflection on RunwayML in a blog post. How is working with RunwayML from your code compared to the web interface? Include screenshots and screen captures of your workflow.

#### Model Training

- Collect your own image or text dataset and train a generative model in RunwayML. Render a latent walk video with the output (for images) or text output samples (for text).

#### RunwayML <-> p5.js

1. Create a p5.js sketch that receives data from RunwayML (using any model). You can use this [glitch RunwayML template](https://glitch.com/edit/#!/runway-ml-template) which hides the keys in a `.env` file. **(If you work with the web editor only, be careful about leaving your token in your code and the model active in the RunwayML interface!)**
2. Optionally, send data to RunwayML or use another programming environment or software tool besides p5.js.
