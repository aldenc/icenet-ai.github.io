# IceNet-AI

# What is IceNet?

IceNet is a deep learning sea ice forecasting system developed by an [international team and led by the British Antarctic Survey and The Alan Turing Institute](https://www.bas.ac.uk/media-post/artificial-intelligence-to-help-predict-arctic-sea-ice-loss/).
The original IceNet research model, [published in *Nature Communicaitons*](https://www.nature.com/articles/s41467-021-25257-4) was trained on climate simulations and observational data to forecast the next 6 months of monthly-averaged sea ice concentration maps.
This version advanced the range of accurate sea ice forecasts, outperforming a state-of-the-art dynamical model (ECMWF SEAS5) in seasonal forecasts of summer sea ice, particularly for extreme sea ice events.
Since then, the IceNet team has focussed on building an operational version of the model which forecasts on a daily resolution.
The [original research code](https://www.github.com/tom-andersson/icenet-paper) was refactored into `icenet`: [a library for operational forecasting](https://github.com/icenet-ai/icenet).
The `icenet` library can support further research efforts into AI-based operational sea ice forecasting

In addition, several use cases and an ecosystem of service components are contained within this organisation, supporting execution and downstream analysis. 

For further information about the team involved, please look at the [project pages at BAS](https://www.bas.ac.uk/project/icenet/) or [The Alan Turing Institute](https://www.turing.ac.uk/news/artificial-intelligence-help-predict-arctic-sea-ice-loss). 

![](https://scotthosking.com/images/icenet/icenet_architecture.png)
