
# Computing Dubins Path 

DubinsPaths is a beginner-friendly GitHub repository that provides a comprehensive guide to understanding Dubins Paths for path planning of vehicles, UAVs (Unmanned Aerial Vehicles), and robots. If you've been struggling to find accessible resources to learn about Dubins Paths, this repository is the perfect solution. It offers step-by-step code examples and practical illustrations, making it easy for beginners to grasp the concept effectively.

Dubins Paths are the shortest paths that connect two specified points in Euclidean space, subject to constant curvature and maximum curvature constraints. This repository breaks down the complex topic into simple explanations and code implementations, catering to learners of all levels.


## Introduction


Welcome to the Dubins Paths for Vehicle Path Planning GitHub repository! This project aims to provide an intuitive and beginner-friendly implementation of the Dubins Paths algorithm, which is widely used for path planning of vehicles, UAVs, and robots with specific kinematic constraints.

Dubins Paths are a family of paths that connect two points while satisfying the minimum turning radius constraint (Rmin) and maximum turning angle constraint for the vehicle. In this repository, we denote the initial and final configurations of the vehicle using arrows, making it easier to visualize the path planning process.

The main features of this repository are as follows:

1.Dubins Path Computation: Given the initial and final configurations of the vehicle, along with the minimum turning radius (Rmin), our code calculates the optimal Dubins Path.

2.Trajectory Classification: Based on the distance between the initial and final arrows (configuration), we determine the optimal trajectory type. If the distance is greater than or equal to 4 times Rmin, the optimal trajectory is classified as CSC (Curve-Straight-Curve). Otherwise, the optimal trajectory is CCC (Curve-Curve-Curve).

3.Shortest Path Determination: We further analyze the distance between the arrows to compute the shortest path within the chosen trajectory type. This ensures efficient and effective path planning for the vehicle.

4.Code Segments: We have organized the code into segments, making it easier for users to understand and utilize specific functionalities of the Dubins Paths algorithm.

Whether you are a beginner looking to grasp the fundamentals of Dubins Paths or an advanced user seeking to implement path planning for your vehicle, this repository has something for everyone. Feel free to explore the code, try out different configurations, and contribute to the project to enhance its functionality.
## Code segments

1. Initial plotting and checking - Calculates the distance between the initial and final arrows (denoting initial and final position of the vehicle).
2. CSC_trajectory - If the distance between the arrows is greater than 4*Rmin , then CSC CSC_trajectory is optimal , this code plots the tangent circle to the arrows and finds out tangent circles that are at a minimum distance.
3. Shortest_CSC_path - This code gives the shortest path among LSL,RSR,LSR,RSL.
4. CCC_trajectory - If the distance between arrows is less than 4*Rmin then CCC_trajectory is optimal, this code computes the shortest possible path among RLR and LRL. 


## Demo

![Demonstration](https://drive.google.com/drive/folders/12eNhMbuVeMaMMyHwrPnwck7WkA7E5r5l?zx=2th3iq11jctu)




## Acknowledgements

 - [A Comprehensive, Step-by-Step Tutorial to Computing Dubin’s Paths](https://gieseanw.wordpress.com/2012/10/21/a-comprehensive-step-by-step-tutorial-to-computing-dubins-paths/)
 - [On Curves of Minimal Length with a Constraint on Average Curvature, and with Prescribed Initial and Terminal Positions and Tangents](https://www.jstor.org/stable/2372560?casa_token=_rO95STAeiIAAAAA%3AY9Qd0bxru0j9X75mF6wxhJopMpoIqF6m3A0AT0Ja6EGnS0gMZK94YiUa_WTwXviu6f-Ul8tlADghroDjHzNpE5exDqjogmvimEdM-Z6D7QM3hnua6D0)
 - [Shortest Path for the Dubins Car](https://demonstrations.wolfram.com/ShortestPathForTheDubinsCar/)


## Authors

- [@SaarthakSharma-906](https://github.com/SaarthakSharma-906)


