# TheCFDMan

This repository contains lecture notes, literature recommendations,  tutorials, code, and examples for performing Computational Fluid Dynamics (CFD) simulations using mainly open-source software such as OpenFOAM, SU2, and PyFR. The aim is to provide a comprehensive resource for researchers and engineers who are interested in using CFD to solve fluid mechanics problems.

The repository includes scripts and configuration files for different types of simulations, such as laminar and turbulent flows, heat transfer, and multiphase flows. Additionally, it includes documentation on the theory and numerical methods used in CFD, as well as tutorials for beginners to get started with the software tools.

## Under Docs

Resources for theory and underlining governing equations involved in typical CFD analyses.

### FluidMechanics_Formulary

Collection of Fluid Mechanics/Dynamics Formulary from various sources.

### Literature

Lecture notes from various Fluid Dynamics and CFD Professors and third party sources.

## Bibliography Suggestions: Theory and Applications

Here are some bibliography recommendations for Fluid Dynamics and CFD, organized by beginner, intermediate, and expert levels:

### Beginner Levels

- [DE] Kuchling, H. (2014). Taschenbuch der Physik. Carl Hanser Verlag GmbH & Co. KG.
- [DE] Rösgen, T. (2011). Strömungslehre: Einführung in die Theorie der Strömungen. Springer-Verlag Berlin Heidelberg.
- [DE] Wille, R., & Case, K. (2006). Numerische Strömungsmechanik. Springer-Verlag Berlin Heidelberg.
- [EN] Versteeg, H.K., & Malalasekera, W. (2007). An Introduction to Computational Fluid Dynamics: The Finite Volume Method. Pearson Education Limited.
- [EN] Anderson Jr., J.D. (1995). Computational Fluid Dynamics: The Basics with Applications. McGraw-Hill Education.
- [EN] Anderson Jr., J.D. (2010). Fundamentals of Aerodynamics. McGraw-Hill Education.
- [EN] Batchelor, G.K. (2000). An Introduction to Fluid Dynamics. Cambridge University Press.

### Intermediate Levels

- [DE] Willi Bohl, Wolfgang Elmendorf (2014). Technische Strömungslehre: Stoffeigenschaften von Flüssigkeiten und Gasen, Hydrostatik, Aerostatik, Inkompressible Strömungen, Kompressible Strömungen, Strömungsmesstechnik. Vogel Fachbuch Kamprath-Reihe.
- [DE] Gersten, K., & Lutz, T. (2013). Strömungsmechanik: Grundlagen, Grundgleichungen, Lösungsmethoden, Softwarebeispiele. Springer-Verlag Berlin Heidelberg.
- [DE] Hoffman, J.D., & Chiang, S.T. (2011). Computational Fluid Dynamics. Oldenbourg Verlag GmbH.
- [DE] Schlichting, H., & Gersten, K. (2016). Grenzschicht-Theorie. Springer-Verlag Berlin Heidelberg.
- [EN] Ferziger, J.H., & Peric, M. (2002). Computational Methods for Fluid Dynamics. Springer-Verlag Berlin Heidelberg.
- [EN] Hirsch, C. (2007). Numerical Computation of Internal and External Flows: The Fundamentals of Computational Fluid Dynamics. Elsevier Butterworth-Heinemann.
- [EN] Roache, P.J. (1997). Quantification of Uncertainty in Computational Fluid Dynamics. Hermosa Publishers.

### Expert Levels

- [DE] Müller, U., & Stark, R. (2017). Numerische Strömungsmechanik: Grundlagen, Statik, Dynamik und Thermodynamik. Springer-Verlag Berlin Heidelberg.
- [DE] Oertel, H. (2013). Berechnung und Simulation von Strömungen. Springer-Verlag Berlin Heidelberg.
- [DE] Peters, N. (2000). Turbulente Strömungen. Springer-Verlag Berlin Heidelberg.
- [EN] LeVeque, R.J. (1992). Numerical Methods for Conservation Laws. Birkhäuser Verlag.
- [EN] Chorin, A.J. (1990). Vortex Sheet Approximation of Boundary Layers. Journal of Computational Physics, 91(2), 386-397.

## CFD Online Resources

- [CFD: Wolfdynamics](http://www.wolfdynamics.com/tutorials.html?layout=edit&id=181)
- [OpenFOAM Tutorials](https://www.youtube.com/channel/UCHXaKLlZRQxkSG6dD6ZWvSg)
- [OpenFOAM Tutorials Docs](https://github.com/openfoamtutorials/OpenFOAM_Tutorials_)
- [Take Your CFD Learning to the Next Level](https://www.youtube.com/playlist?list=PLQMtm0_chcLyEB1EJLUoouugMYZNQUslG)
- [Ansys Student Team Mechanical Tutorials](https://www.youtube.com/playlist?list=PLQMtm0_chcLwKt2NPwtUfbrP2s72hE47j)

## Software Applications

| Software | Commercial/Open Source | Free to use? | Degree of Freedom/Limitation | Node Limit | Physics | Interface |
| --- | --- | --- | --- | --- | --- | --- |
| ANSYS Fluent | Commercial | No | Unlimited | Unlimited | General CFD | GUI |
| ANSYS CFX | Commercial | No | Unlimited | Unlimited | General CFD | GUI |
| OpenFOAM | Open Source | Yes | Unlimited | Unlimited | General CFD | CLI |
| SU2 | Open Source | Yes | Unlimited | Unlimited | General CFD | CLI |
| PyFR | Open Source | Yes | Unlimited | Unlimited | General CFD | CLI |
| StarCCM+ | Commercial | Yes (with restrictions) | Up to 5 million cells | Up to 8 cores | General CFD | GUI |
| Gmsh | Open Source | Yes | Unlimited | Unlimited | Meshing | GUI/CLI |
| FEniCS | Open Source | Yes | Unlimited | Unlimited | General FEA | CLI |
| COMSOL Multiphysics | Commercial | Yes (with restrictions) | Up to 1,300 DOF | Up to 16 cores | General FEA/CFD | GUI |
| Autodesk CFD | Commercial | Yes (with restrictions) | Up to 2,500 nodes | Up to 16 cores | General CFD | GUI |
| SimScale | Commercial/Open Source | Yes (with restrictions) | Up to 32,000 core hours per year | Up to 32 cores | General CFD | GUI |
| NUMECA | Commercial | Yes (with restrictions) | Up to 10,000 cells | Unlimited | General CFD | GUI |

**Note:**

*   Degree of Freedom/Limitation: Refers to the maximum number of degrees of freedom or any other usage limitations that apply to the free to use option of the commercial software.
*   Node limit: Refers to the maximum number of computational nodes that the software can utilize for parallel computing.
*   Physics: Refers to the types of fluid mechanics problems the software can simulate (e.g. general CFD, multiphase flows, heat transfer, etc.).
*   Interface: Refers to the type of user interface provided by the software (e.g. graphical user interface, command line interface).

Keep in mind that this table only provides a brief overview of the different CFD software available and there may be other factors to consider when choosing a software tool for your specific needs.

## Contributing

Contributions to this repository are welcome, and we encourage users to share their own examples, tips, and tricks for performing CFD simulations. We hope that this repository will be a useful resource for the CFD community and help advance the state of the art in fluid mechanics simulations.

## License

This repository is licensed under the MIT License. See the [LICENSE file](LICENSE) for more information.
