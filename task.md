# Task 
## Setup

1. Fork this repo https://github.com/veandoer/sd
2. Follow https://github.com/veandoer/sd/blob/main/README.md to setup the environment
3. Download the weights for Stable Diffusion 1.4

## Task Description
In this task we want to experiment with object consistency. 
Use the given pipeline to generate two images of a piece of furniture, like a table or a chair. You can also try to generate a face. 
You will notice, that the generated objects most likely do not share any simiarity and are not consistent at all. Please try to increase the consistency of both images without training.

In this task you should: 
1. modify the self-attention mechansims in the UNet to increase consistency between all images.
   - What is the intuition behind this task?
   - Please provide sufficient comments in the code that explain your thoughts
   - _hint: Don't mind if the results are not consistent. It's not about results but about the way you approach this task._
2. Question: What is the task of the cross-attention layers in the UNet? How could cross-attention be used to increase consistency?
   - This is just a question, no programming required.
3. Question: In general, what is the contribution of self-attention in this diffusion model?
   - This is just a question, no programming required.
4. Empirically: Do you need to modify all self-attention layers in the UNet? _Hint: Don't evaluate all individual layers, but groups of layers._

## Submission of your results
Please commit all your changes to your forked repository and create a pull-request for this repository to submit your task.
