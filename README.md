# Image-cartoonifying---Lane-Detection
Computer Vision Assignment 1: Image Cartonifying using various image filters and Lane Detection using Hough Transform

Part (1) Image Cartoonifying

The basic idea is to fill the flat parts with some colour and then draw thick lines on the strong edges. In other words, the flat areas should become much flatter and the edges should become much more distinct. 
We will detect edges and smooth the flat areas, then draw enhanced edges back on top to produce a cartoon or comic book effect.

Part (2) Lane Detection

The objective of this part of the assignment is the detection of road lanes in an image using Hough Transform.
The Hough transform can be used to determine the parameters of a line when a number of points that fall on it are known. The normal form of a line can be described with the following equation: x cos θ + y sin θ = ρ where ρ is the length of a line that starts from the origin and perpendicular to the required line, and θ is its inclination. 
The true parameters ρ and θ will get maximum votes from the line points and can be found with a Hough accumulation array.

More details and outputs can be found in the report.
