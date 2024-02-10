# Adjustments for Slope m > 1
For the slope greater than 1 scenario in the Bresenham line drawing algorithm, adjustments are necessary to ensure accurate computation of intermediate points. The standard Bresenham algorithm is designed to handle slopes with absolute values less than or equal to 1 efficiently. When the slope exceeds 1, the algorithm needs to be adapted to accommodate this specific case.

The adjustments made for the slope greater than 1 scenario include:

Interchanging the Roles of x and y: In the standard Bresenham algorithm, the roles of x and y are interchanged when the slope is greater than 1. This means that instead of considering the progression along the x-axis for each step, the algorithm now progresses along the y-axis.

Incrementing y by 1: With a slope greater than 1, incrementing y by 1 for each step ensures that the algorithm accurately traverses the line between the two points. This adjustment maintains the integrity of the line's trajectory while accounting for the steep slope.

Updating the Decision Parameter: The decision parameter calculation is adjusted to reflect the change in the progression direction. The decision parameter determines the next pixel to be chosen and guides the algorithm's progression. In the case of a slope greater than 1, the decision parameter is updated based on the progression along the y-axis.

Handling the Decision Parameter Conditions: The conditions for updating the decision parameter are adjusted to suit the new progression direction along the y-axis. This ensures that the algorithm correctly selects the next pixel while drawing the line.

By making these adjustments, the algorithm can effectively handle slopes greater than 1 and accurately compute the intermediate points along the line between the given points.
# Output
![cgI](https://github.com/jerin-priya/Assignment/assets/74975012/c8496b4e-aa22-4da7-b64a-1d20c7051d91)
