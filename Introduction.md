# The basics
Before we delve into the details, we need to agree on a definition:

## What is CFD?

> [!Note]
> CFD is the study of  fluid flow through numerical methods via computers.

Almost all types of contemporary fluid flow solutions fall within the definition above and can be formally thought of as CFD. This includes potential flow methods. However, since CFD evolved much later than potential flow, when we talk about CFD we typically refer to the Navier-Stokes equations. 
## Methods to analyse fluid flow phenomena
Three approaches can be used to analyse fluid flow phenomena:


<!-- tabs:start -->

#### **Experimentation**
Experiments can provide the 'ground truth for a given problem. However, we must not forget that instrumentation can have finite precision and sometimes has limitations in terms of biases and uncertainties in measurement. In addition, experimentation tends to be phohibitively expensive for many fluid flow problems due to the need to manufacture multiple candidate geometries or replicate flow conditions. Some fluid flow experiments are not feasible experimentally, for example, in ground water modelling. In other cases, we cannot satisfy similarity in all dimensionless groups, such as Froude and Reynolds numbers in ship hydrodynamics. 
#### **Theoretical/Analytical modelling**
Analytical methods can be very useful and provide an answer fast. However, most physical problems do not admit analytical solutions. An example being turbulence, for which a $1 million prize has yet to be claimed from the Millenium Foundation to the person who demonstrates an analytical solution to a turbulent flow in three dimensions. Nevertheless, analytical models can provide valuable insight and are frequently used to check the performance of CFD codes against simplified conditions. Thus, analytical solutions typically require simplified geometries, boundary conditions and flow.
#### **CFD/Numerical modelling**
The main advantege of CFD modelling include the fact that we are not limited to scale or other physical properties. For example, hypersonic capsule re-entry can be modelled in CFD which would be challenging experimentally. However, the main disadvantage of CFD is that it cannot give us correct answers if we do not have *a priori* information about the flow, as will be discussed subsequently. That is, we must know what physics and their regimes are prevalent in the flow and target them specifically. Mesh design is an excellent example of this problem.
Using CFD we can obtain a full description of the flow at any point we want. There are no experimental apparatus in the way so we can sample the flow with any resolution we want as long as our set up is accurate enough.
<!-- tabs:end -->


## Hierarchy of fluid flow
The image below shows the relationship between the different types of flow, starting from linear, inviscid, irrotational flow, all the way up to Direct Numerical Simulations (DES) where virtually no assumptions are made about the flow. This course will mostly focus at the level of Reynolds Averaged Navier-Stokes and items below, adapted from [Terziev et al. (2020)](https://doi.org/10.1016/j.oceaneng.2020.107434)

![Fluid flow hierarchy, adapted from Terziev et al. (2020)](/images/hierarchy.png)

## Reference
Terziev, M., Tezdogan, T. and Incecik, A., 2020. A posteriori error and uncertainty estimation in computational ship hydrodynamics. Ocean Engineering, 208, p.107434. DOI:https://doi.org/10.1016/j.oceaneng.2020.107434

