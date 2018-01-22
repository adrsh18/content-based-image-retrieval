# Content Based Image Retrieval
Image search with Deep Learning

### Summary
Ever though how Google's Image Reverse Search or Pinterest's Visual Search algorithms work? Well, this project is one way to build such a system.

Your search image first goes through a **Convolutional Autoencoder**. What comes out is a small *vector representation* of the image which captures all the relevant features in it. This little *content vector* is searched against a previously indexed image database using **Approximate Nearest Neighbor** algorithm. The results are returned and ranked in the UI as shown below:

(Note: Examples show indexed images of smaller resolutions)

Searching for planes:
![Planes](https://raw.githubusercontent.com/adrsh18/content-based-image-retrieval/master/plots/plane2.png)

Searching for trucks:
![Trucks](https://raw.githubusercontent.com/adrsh18/content-based-image-retrieval/master/plots/truck.png)
