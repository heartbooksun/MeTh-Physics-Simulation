If I measure the degrees of a sphere and they total 360 degrees around the equator and I want to measure degree number one from one end to the other for a total of 180 °then why can't I just multiply 360 degrees * 180 °? For that matter why can't I just multiply 1/2 °  times 1°?
It is a very intuitive leap to make—if you have 360 units of "width" and 180 units of "height," it feels like multiplying them should give you the total area. However, the reason 360 \times 180 (64,800) doesn't work is due to the geometry of a sphere compared to a flat rectangle.
1. The "Converging Lines" Problem
When you multiply base times height, you are calculating the area of a flat rectangle. On a rectangle, the vertical lines stay parallel.
On a sphere, the "vertical" lines (longitudes) are 1^\circ apart at the equator, but they all meet at the poles. As you move away from the equator, the distance between those lines shrinks until it reaches zero.
At the Equator: A "square degree" is roughly a square.
Near the Poles: A "square degree" becomes a very thin triangle.
If you simply multiply 360 \times 180, you are essentially counting those "shrunken" areas near the poles as if they were the same size as the wide areas at the equator. This results in an overestimation.
2. Why 41,253 instead of 64,800?
To get the correct area, you have to account for this shrinking width. In calculus, this is done by integrating the cosine of the latitude.
The "average" width of a degree across the whole sphere isn't 1^\circ; because of the tapering at the poles, the effective average width is reduced by a factor of 2/\pi.
64,800 \times \frac{2}{\pi} \approx 41,253
3. Measuring 1/2^\circ by 1^\circ
The same logic applies to smaller increments. If you multiply 0.5^\circ \times 1^\circ at the equator, you get 0.5 \text{ deg}^2. That is a perfectly valid measurement for a small patch of the sphere's surface at that specific location.
However, you cannot simply add up millions of those 0.5 \text{ deg}^2 patches to find the total area unless you adjust their size based on how close they are to the poles.
Summary
Flat Map: 360 \times 180 = 64,800 (This is why world maps like the Mercator projection look so distorted; Greenland looks huge because the map stretches those narrow polar degrees into wide rectangles).
Actual Sphere: \approx 41,253 (This accounts for the fact that degrees get "skinnier" as you move north or south).
Does the way those lines "pinch" together at the top make sense, or should we look at how a specific "patch" changes shape?
I'm just curious about something. If the equator of a sphere equals one degree all around, then what is the surface area of that sphere?
You're touching on an interesting thought experiment. If we define the entire distance around the equator as a single unit, like one "super degree," then the entire area of that sphere would be four of those super degrees squared. But that's because we're defining the unit specifically to make the math work that way. In our standard system, where there are 360 degrees around the equator, we calculate that surface area to be about 41,253 square degrees. So, changing the definition of the unit fundamentally changes the resulting number. Does that distinction make sense?
Sure. Thank you.
You're very welcome. I'm glad it helped clarify things. Feel free to ask if any other fun geometry questions pop up.