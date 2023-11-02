## overall structure
sandwich the middle bit (getting in deep with the model spec/indexing) with
1. start: motivation. what's the problem we're trying to solve? expanding a model in "real life"
2. end: what are the downstream rewards of using macpan2?

the middle bit:
- cast a simple model like the SIR fully in our model spec
- then look at how we cast the structured model (get into implementation and show it just to solve one productify problem)
- then show all the other options for products

## more specific slide ideas
- high-level diagram of the macpan2 model definition -> simulate -> results and explain/justify zooming into the model spec part + getting simulation (and eventually calibration) for free
- define key terms up front, _e.g._, "structured model"
- table of analogous functions
  - dplyr::join -> mp_join
  - ...
- give a disclaimer about model components as tables being a useful way to think about specifying models, that will eventually help us understand how to use the sosftware, but to start we will just look at how to work with these special tables

