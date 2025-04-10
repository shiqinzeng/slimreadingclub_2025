# SLIM Reading Club

[SLIM Group](https://slim.gatech.edu/) hosts a biweekly reading club on Fridays at 10 AM in Coda C1303 GlenWood. Any exceptions or changes to the location and time will be communicated in advance. Students present a paper relevant to the SOTA research pratices in the fields of [machine learning, uncertainty quantification, variational inference, and inverse problems]. These presentations are usually informal and participants are encouraged to take part in the discussion and share experiences with specific domain knowledge. 

This website is maintained by the GitHub repository at [https://github.com/shiqinzeng/slimreadingclub_2025](https://github.com/shiqinzeng/slimreadingclub_2025). If you have any questions or suggestions of the reading club series, please open an issue to the repo. If you would like to join our reading club or present your favorite paper, please open a pull request.

Organizers:
Shiqin Zeng, szeng44@gatech.edu    
Huseyin Tuna Erdinc, herdinc3@gatech.edu    
Zijun (Venice) Deng, zdeng78@gatech.edu  
Felix J. Herrmann, felix.herrmann@gatech.edu    

### The schedule for Spring 2025 SLIM Reading Club Schedule is:

**Friday 10:00 am Jan 17th, Coda C1303 Glenwood**		        
Paper: [Variational prior replacement in Bayesian inference and inversion](https://arxiv.org/pdf/2406.04072)  
Presenter: Huseyin Tuna Erdinc.

Slides can be found [here](https://drive.google.com/file/d/1Spgt3Lt5yLEeNb4RrAUY-2_lRk-5PTIs/view?usp=drive_link).  

Outline:    
-  Motivation for prior replacement
-  Recap on Bayesian Inference  
-  Derivation of prior replacement
-  Classic variational inference and variational prior inference
-  Physically structured variational inference (PSVI)	       
-  Results on FWI

**Friday 10:00 am Jan 31, Coda C1303 Glenwood**		        
Paper: [Learning spatiotemporal dynamics with a 
pretrained generative model](https://www.nature.com/articles/s42256-024-00938-z)  
Presenter: Shiqin Zeng.

Related materials can be found [Denoising trajectory details](https://drive.google.com/file/d/1qxckIetiS_JsRAnSqZhLttOvxr0xyco-/view?usp=sharing), [Results on CO₂ reservoir simulation data](https://docs.google.com/presentation/d/1TMvTjOMUspDJkaW1eeQ3oi6aNFFJ7HMR/edit?usp=drive_link&ouid=107090150198155230870&rtpof=true&sd=true).


Outline:    
- Introduction to Video U-Net
  - Spatial and temporal attention mechanisms

- Constrained Denoising – Gradient-Based Correction
  - Observation constraints
  - PDE constraints

- Time Series Data
  - Joint training with fixed time frames
  - Ensuring temporal consistency

- Results on CO₂ Reservoir Simulation Data

**Friday 10:00 am April 11, Coda C1303 Glenwood**	
Paper: [Gradient-free generation for hard-constrained systems](https://www.amazon.science/publications/gradient-free-generation-for-hard-constrained-systems)
Presenter: Zijun (Venice) Deng.

Outline:
-  Why Gradient-Free?
   - Motivation for hard-constrained generation
   - Limitations of gradient-based methods
- ECI Sampling
  - Extrapolate → Correct → Interpolate
- Handling Constraints
  - Value & region constraints
  - Controlling diversity with resampling
- Results
  - Performance on PDEs (Stokes, NS, etc.)
