# Master Thesis

### Toward automatic decomposition of monolithic software into microservices – Conception of a methodology and its exemplary implementation

<br>

## Abstract

The microservices paradigm gets more and more traction and many companies choose to adopt it
for new developments as well as to transform existing monolithic software to be
microservices-based instead.
However, the latter approach bears many difficulties that involve much manual work,
specifically in the early stages of such a decomposition process.
Determining the boundaries between the services, where one service ends and the next one begins,
is a notoriously difficult task for which a lot of literature exists that however mainly helps with
providing a framework to determine said boundaries manually, with _Domain-driven design_ by
Eric Evans laying the foundation for this entire domain of research.

This thesis devises a methodology that automatically generates microservice candidate recommendations
for any given piece of monolithic software without any further user input but the software itself.
To do this, four dimensions of coupling are calculated out of the input software that each
construct a weighted graph with the edges resembling coupling between the units of the software.
Next, the four graphs are merged into one before being clustered by specifically surveyed and assessed
state-of-the-art graph clustering algorithms – the resulting clusters then resemble the microservice
candidate recommendations. Additionally, a large set of numeric metrics was formulated to evaluate the
output of the methodology.
Finally, the devised methodology was fully implemented, with an additional
graphical user interface for ease of use, to work with input Java software while
being easily extensible to be able to support other platforms in the future.

## Download

You can download the full thesis from [GitHub](https://github.com/loehnertz/master-thesis/releases/download/v1.0/Master-Thesis_Jakob-Loehnertz.pdf)!
