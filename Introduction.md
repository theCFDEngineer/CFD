# The basics
Before we delve into the details, we need to agree on a definition:

## 1: What is CFD?

> [!Note]
> <a name="what-is-cfd">CFD is the study of  fluid flow through numerical methods via computers.</a>

Almost all types of contemporary fluid flow solutions fall within the definition above and can be formally thought of as CFD. This includes potential flow methods. However, since CFD evolved much later than potential flow, when we talk about CFD we typically refer to the Navier-Stokes equations. 
## Methods to analyse fluid flow phenomena
Three approaches can be used to analyse fluid flow phenomena:

## Hierarchy of fluid flow
The image below shows the relationship between the different types of flow, starting from linear, inviscid, irrotational flow, all the way up to Direct Numerical Simulations (DES) where virtually no assumptions are made about the flow. This course will mostly focus at the level of Reynolds Averaged Navier-Stokes and items below, adapted from [Terziev et al. (2020)](https://doi.org/10.1016/j.oceaneng.2020.107434)

![Fluid flow hierarchy, adapted from Terziev et al. (2020)](/images/hierarchy.png)

## Reference
Terziev, M., Tezdogan, T. and Incecik, A., 2020. A posteriori error and uncertainty estimation in computational ship hydrodynamics. Ocean Engineering, 208, p.107434. DOI:https://doi.org/10.1016/j.oceaneng.2020.107434

