# K-Nearest-Neighbors and K-means-clustering
a basic implementation of k-nearest-neighbors

This project is a build week for Lambda School Computer Science Unit 1. It was completed durring the week of May 25th.

[Requirements can be found here](https://github.com/LambdaSchool/CS-Data-Science-Build-Week-I)

### Monday

I choose to do this implimentation because as a part of my labs project I needed to cluster earthquakes but was unable to get the sklearn implementation to work for me. I'm going to check in tomorrow (Tuesday) if I can build an algorithm that is specific to my project instead of just recreating the base model.

Today I'm going to focus on getting the general structure of the class built. MVP lays out required methods and I'm going to get those in place along with a rudimentary predict method.


### Tuesday

I ran through the basic KNN classifier yesterday so I'm going to switch to k-means clustering. I'm going to start a KMC classifier, I have an idea involving a distance matrix but its only a basic idea that will not work fully. Perhaps something along the lines of finding the lowest average with the highest distances from each other.

OK, I was totally making it harder than it needs to be. I've implimented a basic solution that works but needs improvement following the pattern:
- select K random points
- group the data around those points
- get the average distances of the groups
- use those averages as the new center
- loop until the centers don't change
