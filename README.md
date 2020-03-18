# COVID19 Logistic Growth Model

Viral infection generally follows a logistic growth curve. A population is infected at an exponential rate which eventually slows leading to saturation point.

The model being fit to the COVID19 dataset is:

<img src="images\GrowthEq.png" alt="GrowthEq" style="zoom:75%;" />


where L is the carrying capacity, k is the growth rate (how steep the curve is), and t0 is the time halfway to saturation. The output here is the number of aggregated US cases given a time t after the first case. See the code or pdf for more details.
