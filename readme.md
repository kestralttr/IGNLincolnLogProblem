# IGN Lincoln Log Problem

Web version can be found [here](https://kestralttr.github.io/IGNLincolnLogProblem/).

## Instructions

The Lincoln Log problem asks how many Lincoln Logs would be required to build a life-size replica of the Empire State Building so that King Kong can enjoy his famous perch from San Francisco. While I'm not sure how he plans on paying Bay Area rent prices on a lot that large, we can definitely help him figure out how many Lincoln Logs would be needed to build his second home.

## Empire State Building Dimensions

Our first challenge is to discover exactly how large the Empire State Building is.

Extensive Internet sleuthing failed to return the exact exterior dimensions of every major edge on the building, so while I was able to find some old blueprints, they didn't include all the information I needed to calculate that volume myself. So I had to settle for the official given stats, which are as follows:

- 37 million cubic feet
- 1454 feet high
- 187 feet wide at base
- 424 feet long at base

## Lincoln Log Dimensions

Next, we need to know the basic dimensions of Lincoln Logs. I found a very helpful image online that details the exact measurements of the logs:

<img src="http://res.cloudinary.com/dzo2s4ovl/image/upload/v1489487849/lincoln_log_dimensions_ouaubx.jpg">

Essentially, the regular Lincoln Logs are 4.5 inches long. And to keep things simple, we'll move ahead assuming that we'll be building the entire structure with the regular sized logs.

After looking into how people generally build superstructures out of Lincoln Logs, I found that there are two main ways:

First, you can build simple 1x1 squares out of the logs and situate them next to each other so that they take on the appearance of a larger structure. However, this approach is less stable and doesn't technically constitute a single building.

For that reason, we'll plan to build the Empire State Building the second way: using an interlocking pattern that offers stability and actually connects all the logs together so that each one is a part of the entire structure.

After deciding on a build pattern, I sketched out a to-scale blueprint in Photoshop to help with the visualization of what the Lincoln Log replica would look like up close:

<img src="http://res.cloudinary.com/dzo2s4ovl/image/upload/v1489521085/lincolnlogs2_evif26.jpg">

By modeling the shape and size of the Lincoln Logs in an interlocking formation, I was able to determine the dimensions of the basic building blocks that would make up a larger structure. Namely, that Lincoln Logs don't fit exactly into a square foot, but instead into a square whose edges are 10.5 inches long. Within that square, up to 28 Lincoln Logs would be able to fit (adding together the fractions of logs that would be within the square's limits).

After establishing the square (aka wall of Lincoln Logs) I'd be working with as well as the number of logs that fit into it, it was then a simple matter to model that square as a unit of volume. With the diagram I created along with some sketches I made, I determined that the size of the Lincoln Logs would mean that each of these 10.5 inch cubes would hold 8 walls of logs - 4 walls across the width, interlocking with another 4 walls across the length of the cube, and each wall being 10.5 inches high. This resulted in the maximum number of logs per 10.5 inch cube being 224 logs.

## Number of Lincoln Logs Needed

Now that we have workable dimensions for both the Empire State Building and the cubic units of Lincoln Logs, we can make a reliable estimate of how many logs will be required to build our structure.

As we discovered earlier, the volume of the Empire State Building is 37 million cubic feet. Since our units of volume in Lincoln Logs are 10.5 inch cubes, we divide 12 inches by 10.5 inches to find 0.875, which we then raise to the 3rd power to find that each 10.5 inch cube has 0.67 of the volume held by a cubic foot. We then divide 37 million by 0.67 to discover that it would take 55,223,881 10.5 inch cubes to fill up the Empire State Building.

Finally, we multiply 55,223,881 by 224 , which returns the total number of logs we'd need to reconstruct the Empire State Building:

### 12,370,149,254 logs
