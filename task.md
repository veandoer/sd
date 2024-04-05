# Task 
## Setup

1. Fork this repo https://github.com/veandoer/sd
2. Follow https://github.com/veandoer/sd/blob/main/README.md to set up the environment
3. Download the weights for Stable Diffusion 1.4

## Task Description
In this task, we want to experiment with object consistency. 
You can use the given pipeline to generate two images of a piece of furniture, such as a table or a chair, or to try to generate a face. 
You will notice that the generated objects are most likely not similar or inconsistent. Please try to increase the consistency of both images without training.

In this task, you should: 
1. modify the self-attention mechanisms in the UNet to increase consistency between all images.
   - What is the intuition behind this task?
   - Do not modify the cross-attention layers.
   - Please provide sufficient comments in the code that explain your thoughts
   - _hint: Don't mind if the results are not consistent. It's not about results but about the way you approach this task._
2. Question: What is the task of the cross-attention layers in the UNet? How could cross-attention be used to increase consistency?
   - This is just a question; no programming is required.
3. Question: In general, what is the contribution of self-attention in this diffusion model?
   - This is just a question; no programming is required.
4. Empirically: Do you need to modify all self-attention layers in the UNet? _Hint: Don't evaluate all individual layers, but groups of layers._

## Submission of your results
Please commit all your changes to your forked repository and create a pull request for this repository to submit your task.
