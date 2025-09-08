Senior Thesis for undergraduate Computer Engineering degree at Boston University

## Efficent High-Precision Physics-Informed Neural Networks For Magnetic Resonance Electrical Property Tomography And Phonon Boltzmann Transport ##

### Abstract ###

Physics-Informed Neural Networks (PINNs) have emerged as a powerful tool for 
solving forward and inverse problems governed by partial differential equations (PDEs). 
This work advances two state-of-the-art applications of PINNs in biomedical imaging 
and thermal transport. 

First, we improve the Physics-Informed Fourier Networks (PIFON) framework, 
developed by collaborators at the NYU Department of Radiology for Magnetic 
Resonance Electrical Properties Tomography (MR-EPT), by introducing two novel 
architectures: EigenFunction-PINN (EF-PINN) and Multiscale Dropout-PINN 
(MS-DO-PINN), along with a Modified Mean Square Error loss function. These 
innovations address a critical limitation of classical PINNs, where high errors near 
material interfaces are smeared across neighboring regions, leading to poor 
reconstructions. Our approach significantly enhances reconstruction accuracy, reducing 
the error from ≤10% (baseline PIFON) to as low as ≤0.01%. These improvements 
generalize well to 3D and realistic 2D scenarios, achieving ≤0.1% error even under noise. 
 

Second, we refine a PINN-based solver for the mode-resolved phonon Boltzmann 
Transport Equation (BTE) by developing a Hard Constraint PINN (HC-PINN) that 
enforces boundary conditions exactly. With additional optimization techniques, we 
reduce training time from 4 hours to under 10 minutes, enabling efficient simulation of 
thermal transport across ballistic to diffusive regimes. 


These contributions not only advance the state of the art in PINN-based modeling 
but also highlight the power of tailored architectures and training strategies in 
overcoming long-standing challenges such as interface reconstruction and computational 
inefficiency. We demonstrate PINN’s capabilities by enabling precise, scalable solutions 
in biomedical imaging and nanoscale heat transport.
