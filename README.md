# CANMOD Wrapup Meeting Workshop

https://workshops.birs.ca/events/23w5151

- 1 hr to motivate macpan and present an introduction
- 3 hrs for participants to respond to a modelling request from the tabletop exercise using macpan2

## `macpan2` workshop goals

Steve:
- motivate and advertise `macpan2` as a modelling software
  - why is this better than what people already use or just learning TMB yourself? 
  - advanced examples that show macpan's power (_e.g._ kevin's work)
 
Irena:
- basic use: finding existing models and simulate from them
- demo: how to modify an existing `macpan2` model (_e.g._ add a compartment like $I_a$ and $I_s$, adjust the force of infection)
- demo: calibrate a model to "real" data
- demo: forecast ensemble

## Plan

- Irena:
  - get a minimum viable product via the [quickstart guide](https://canmod.github.io/macpan2/articles/quickstart) + [calibration](https://canmod.github.io/macpan2/articles/calibration.html) + forecast ensemble by updating [this vignette](https://canmod.github.io/macpan2/articles/quickstart.html)
  - keep only first four columns of the `flows.csv` file for simplicity
- Steve:
  - make synonyms for partition columns in `flows.csv` that are linked to the action (_e.g._ `from_filter_on`, `from_to_join_by`)
  - a scheme/diagram of how the software works to make sense of the model defintion files   
  - hash out model canning using/inspired by the framework in [EPACmodel](https://phac-nml-phrsd.github.io/EPACmodel/) to potentially make it easier for users to jump into models and customizing their own
