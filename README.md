# FDEM1D
Frequency domain electromagnetic (FDEM) 1D forward and sensitivity modelling code.
Created by Daan Hanssens
Contact Daan.Hanssens@UGent.be

### Frequency domain electromagnetic 1D forward and sensitivity modelling: 
### Overview, assessment and practical implementation(including MATLAB, Python and pseudo-code)
Frequency domain electromagnetic (FDEM) data are commonly acquired to provide spatially continuous information about subsurface electrical conductivity and/or magnetic susceptibility. In order to link the phase sensitive instrument responses with the subsurface physical properties, a forward model is indispensable. Although forward and sensitivity modelling have been described in literature, precise details are often lacking, which impedes reproducibility. In addition, following the rapid growth of FDEM applications, an increasing number of end-users, with a varying background knowledge in geophysics, is applying FDEM instrumentation. To advance the critical implementation of these techniques in a practical manner, we present an extensive theoretical description alongside pseudocode, MATLAB and Python code of both forward and sensitivity modelling approaches. The presented models govern the 1D normalized electromagnetic response and sensitivity of a magnetic dipole located on or over an idealized horizontally n-layered half-space, obtained through a superposition of Bessel functions of the zeroth and/or first order determined by the Hankel transform, as numerically calculated by means of a digital filter. Ultimately, we tested and validated the algorithm by comparing it to established modelling codes. This work aims to provide a comprehensive and practical contribution to FDEM implementation through: (1) an overview of recent advances; (2) a presentation of forward and sensitivity modelling procedures aimed at full reproducibility; (3) an independent validation of prior procedures; and (4) the inclusion of sensitivity modelling.

Hanssens, D., Delefortrie, S., De Pue, J., Van Meirvenne, M., and De Smedt, P., 2018,
Frequency domain electromagnetic 1D forward and sensitivity modelling: Overview,
assessment and practical implementation(including MATLAB, Python and pseudo-code):
Submitted to IEEE Geoscience and Remote Sensing Magazine.
