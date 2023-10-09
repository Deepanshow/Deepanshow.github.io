


# Effect of Neutron star jet on Common Envelope Evolution (CEE)
## Supervisor: Dr. Luke Chamandy

In this project, we aim to investigate the impact of a neutron star jet on the Common Envelope Evolution (CEE) process. The Common Envelope Evolution occurs in binary star systems where one star expands and engulfs its companion within its envelope. This interaction leads to the formation of a close binary system, which can undergo various evolutionary paths.

## Common Envelope Evolution (CEE)

Common Envelope Evolution (CEE) is a crucial phase in the binary star evolution, which involves the envelope of one star engulfing its companion. During this phase, the orbital energy of the binary system is transferred to the envelope, resulting in the inspiral and subsequent ejection of the envelope. The CEE process plays a significant role in the formation of compact binaries, such as binary neutron star systems.

## Methods

In this section, we describe the methodology and setup employed in our study of Common Envelope Evolution using Adaptive Mesh Refinement (AMR) techniques with the ASTROBEAR code. The simulation setup involved a detailed consideration of the stellar parameters, computational domain, and resolution levels.

### **Stellar Parameters**

The primary star in our simulation has a mass of 1.96 solar masses ($ M_\odot $) and a radius of $48.1 R_\odot$. Within the primary star, the core contains a mass of $0.37 M_\odot$. The secondary star has a mass of $0.98 M_\odot$ and is situated at a distance of $49.0 R_\odot$ from the primary star.

### **Computational Domain**

The computational domain, or simulation box, was set to dimensions of $1150 R_\odot \times 1150 R_\odot$. This adequately encapsulates the physical region of interest for the common envelope evolution process, ensuring that the interaction between the two stars and the ensuing envelope ejection can be accurately simulated.

### **Adaptive Mesh Refinement (AMR)**

We employed Adaptive Mesh Refinement (AMR) techniques to ensure that our simulations achieved both high accuracy and computational efficiency. The highest resolution utilized in our simulations was $0.140 R_\odot$, which allowed us to capture intricate details of the common envelope evolution. Additionally, we used a base resolution of $2.25 R_\odot$ in regions where a coarser grid was sufficient, optimizing our computational resources.

### **Ambient Medium Properties**

To simulate the surrounding ambient medium accurately, we specified the density and pressure of the medium. The density of the ambient medium was set to $6.7 \times 10^{-9} \textit{g cm}^{-3}$ . The pressure was chosen to be $1.0 \times 10^5 \textit{dyn cm}^{-2}$ .

## JET MODEL

### **Jet Geometry**

- The jet axis is oriented perpendicular to the orbital plane of the binary system.
- The jet has a specific opening angle, denoted as $\theta_h$, which was set to $\theta_h = 15^\circ$. This angle defines the extent of the jet's angular spread.
- The distribution of density and radial velocity within the jet varies with polar angle. It is strongly peaked at polar angles less than $\theta_h/6$, emphasizing the concentration of jet material in a particular direction.
- The majority of the jet mass is concentrated at a distance approximately equal to half the distance between the boundary of jet's spherical sector and the secondary star. This distance, denoted as $r_j$, was defined as $2.25 R_\odot$.

### **Initial Conditions**

- To initiate the jet material, we provided it with an additional velocity component equal to the instantaneous orbital velocity of the secondary star.
- The temperature of the jet material was set to $T_j = 10^4$ Kelvin ($10^4$ K). It is worth noting that the results of our simulations are independent of the jet's temperature due to the supersonic nature of the jet.

### **Jet Structure**

- Following the framework established by Fedderath, our jet model features a high-momentum spine with a narrow opening angle. This spine represents a focused, collimated portion of the jet with high momentum.
- In addition to the high-momentum spine, our model also includes a lower-momentum component known as the 'wide angle wind.' This component is characterized by a broader angular spread, contributing to a more diffuse region of the jet.

## Simulation Runs

The following table shows the details of the simulation runs conducted in this project:

<p align="center">
  <img src="/Plots/Tables/Table 1.png" alt="Table" width="400" height="200">
</p>

<p align="center">
  Table : Parameters used for different runs 
</p>


# Unbound Mass with Time



<img src="/Plots/Total Escape Mass_2023-09-19.png" alt="Total Unbound Mass" align="center">

<p align="center">
  Figure : Total Escape Mass comparing J8 (magenta dashed), run001 (blue dash-dotted) and run003 (red solid)
</p>
  &ensp;

<img src="/Plots/Total Escape Mass due to jet_2023-09-19.png" alt="Total Unbound Mass jet only" align="center">
<p align="center">
  Figure : Total Escape Mass due to Jet comparing J8 (magenta dashed), run001 (blue dash-dotted) and run003 (red solid)
</p>



<img src="/Plots/J8 Vs 001 Escape Mass2023-09-19.png" alt="Difference in run 001 and J8" align="center">

### run004 Vs run003

<img src="/Plots/Total Escape Mass due to Jet 004.png" align="center">


<img src="/Plots/Total Escape Mass 004.png" align="center">


# Accretion 

<img src="/Plots/Accretion_with_time_2023-09-19.png" alt="Accretion rate for different runs" align="center">

<img src="/Plots/Accretion_rate_2023-09-19.png" alt="Accretion rate for different runs" align="center">



<br><br>
# Movies


## Below are the plots showcasing the simulation of a neutron star jet and its effect on the Common Envelope Evolution:



## Feedback Plot


<img src="/Plots/Feedback%20Plots/Feedback_edge_60Rsun.gif" alt="Feedback Edge 60Rsun" align="center">

Feedback edge 60Rsun

<br> <br>


<img src="/Plots/Feedback%20Plots/Feedback_edge_575Rsun.gif" alt="Feedback Edge 575Rsun" align="center">

Feedback edge 575Rsun

<br><br>


<img src="/Plots/Feedback%20Plots/Feedback_edge_P1_60Rsun.gif" alt="Feedback Edge View from P1 60Rsun" align="center">

Feedback edge view from P1 60Rsun

<br><br>


<img src="/Plots/Feedback%20Plots/Feedback_edge_P1_575Rsun.gif" alt="Feedback Edge View from P1 575Rsun" align="center">

Feedback edge view from P1 575Rsun

### run003 Vs run004

<img src="/Plots/Feedback%20Plots/Feedback_Edge_004_120Rsun.gif" alt="Rho Edge 120Rsun">
<em>Feedback edge 60Rsun </em>

<img src="/Plots/Feedback%20Plots/Feedback_Edge_004_1150Rsun.gif" alt="Rho Edge 1150Rsun">
<em>Feedback edge 575Rsun </em>

<img src="/Plots/Feedback%20Plots/Feedback_Edge_P1_004_120Rsun.gif" alt="Rho Edge 120Rsun">
<em>Feedback edge view from P1 60Rsun </em>

<img src="/Plots/Feedback%20Plots/Feedback_Edge_P1_004_1150Rsun.gif" alt="Rho Edge 1150Rsun">
<em>Feedback edge view from P1 575Rsun </em>


## Rho Plots



  <img src="/Plots/Rho/rho_edge_60Rsun.gif" alt="Rho Edge Full">

<em>Rho edge 60 Rsun </em>

<br><br>


  <img src="/Plots/Rho/rho_edge_575Rsun.gif" alt="Rho Edge Full">

<em>Rho edge 575 Rsun</em>

<br><br>


  <img src="/Plots/Rho/rho_edge_P1_60Rsun.gif" alt="Rho Edge View from P1 60Rsun">

<em>Rho edge view from P1 60Rsun</em>

<br><br>


  <img src="/Plots/Rho/rho_edge_P1_575Rsun.gif" alt="Rho Edge View from P1 575Rsun">

<em>Rho edge view from P1 575Rsun</em>

<br><br>

### run003 Vs run004

<img src="/Plots/Rho/Rho_Edge_004_1150Rsun.gif" alt="Rho Edge View from P1 575Rsun">

<em>Rho edge view from P1 575Rsun</em>

<img src="/Plots/Rho/Rho_Edge_004_120Rsun.gif" alt="Rho Edge View from P1 575Rsun">

<em>Rho edge view from P1 575Rsun</em>

<img src="/Plots/Rho/Rho_Edge_P1_004_1150Rsun.gif" alt="Rho Edge View from P1 575Rsun">

<em>Rho edge view from P1 575Rsun</em>

<img src="/Plots/Rho/Rho_Edge_P1_004_120Rsun.gif" alt="Rho Edge View from P1 575Rsun">

<em>Rho edge view from P1 575Rsun</em>



## Rho With Vector


  <img src="/Plots/Other_Plots/rho_with_vectors_edge_P1_60Rsun.gif" alt="rho with vector full">

<em>Rho with vectors 60Rsun </em>

##Temperature


  <img src="/Plots/Other_Plots/temperature_edge_1150.gif" alt="Temperature">

<em>Temperature (Kelvin) edge 1150Rsun  </em>


  <img src="/Plots/Other_Plots/temperature_edge_p1_575.gif" alt="Temperature p1">

<em>Temperature (Kelvin) edge view from P1 1150Rsun  </em>


## Unbound Mass Plot


  <img src="/Plots/Unbound/Unbound_mass_Edge_60.gif" alt="Unbound Edge 60Rsun">

<em>Unbound mass plot edge view 60Rsun </em>

<br><br>


  <img src="/Plots/Unbound/Unbound_mass_Edge_575.gif" alt="Unbound Edge 575Rsun">

<em>Unbound mass plot edge view 575Rsun </em>


  <img src="/Plots/Unbound/Unbound_mass_Edge_P1_60.gif" alt="Unbound Edge view from P1 60Rsun">

<em>Unbound mass plot edge view from P1 60Rsun </em>


  <img src="/Plots/Unbound/Unbound_mass_Edge_P1_575.gif" alt="Unbound Edge view from P1 575Rsun">

<em>Unbound mass plot edge view from P1 575Rsun </em>



  <img src="/Plots/Unbound/Unbound_mass_Face_60.gif" alt="Unbound Face-on 60Rsun">

<em>Unbound mass plot face-on view 60Rsun </em>



  <img src="/Plots/Unbound/Unbound_mass_Face_575.gif" alt="Unbound Face-on 575Rsun">

<em>Unbound mass plot face-on view 575Rsun </em>



  <img src="/Plots/Unbound/Unbound_face_z_20Rsun.gif" alt="Unbound Face-on (z+20Rsun) 575Rsun">

<em>Unbound mass plot face-on ( z + 20Rsun) view 575Rsun </em>




