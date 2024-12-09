
# EMI-Experimental-Temperature-Variations

 <div align="justify">EMI-Experimental-Temperature-Variations comprises datasets and information pertinent to research in Structural Health Monitoring (SHM) via Electromechanical Impedance (EMI) technique. The studies were carried out on a 6063-T5 aluminum alloy beam with PSI-5H4E piezoelectrics transducers (PTZs) from Piezo Systems attached to its surface. This benchmark presents the experimental methods employed for the EMI technique. The experiments consisted of collecting electromechanical impedance signals for undamaged structural conditions, at different temperatures, using piezoelectric transducers attached to the structure in symmetrical and asymmetrical configurations. In addition, EMI signals for a beam with a symmetrical corrosion-type damage were obtained exclusively with PZTs symmetrically coupled to the structure, at different temperatures. Finally, EMI signal measurements were also carried out for a piezoelectric transducer in a free condition, i.e., uncoupled from any structure, under different thermal conditions. This dataset is valuable for validating SHM algorithms at different temperatures.

## 1. Data Access

Data are available for non-commercial research under the following terms: (i) the GMSINT Laboratory and UNESP/Ilha Solteira should be recognized as the source of the data; (ii) publications should include references pertinent to the publications of GMSINT members; (iii) it is necessary to cite this benchmark.

To learn more about the reserach group GMSINT: https://bit.ly/3RSReVl

To download the dataset (experimental signals) of the benchmark, please fill the form: https://bit.ly/3VINLtA

## 2. Experiment to collect EMI signals

This section presents the various experimental tests conducted. The methodology for measuring electromechanical impedance signals is outlined for four different cases. In the first one, EMI signals from an undamaged beam with a PZT coupled in an asymmetric configuration are measured. The second and third cases investigate, respectively, an undamaged and damaged beam with symmetrically coupled PZTs. In the fourth and final case, an uncoupled PZT is examined. All analyses were performed considering variations in ambient temperature.

### 2.1. Undamaged Beam with Asymmetrically Coupled PZT

The experiment consisted of collecting electromechanical impedance signals from a 6063-T5 aluminum alloy beam containing a PSI-5H4E piezoelectric transducer, from *Piezo Systems*$$^\circledR$$, asymmetrically placed on the structure in relation to its longitudinal direction, as shown in Fig. 1

<p align="center">
Figure 1 - Aluminum beam with an asymmetrically coupled PZT.
</p>

![https://github.com/Lorena591/Pesquisa-Doutorado-Direto/blob/main/VigaPZT.jpg](https://github.com/Lorena591/Pesquisa-Doutorado-Direto/blob/main/VigaPZT.JPG)

The following Fig. 2 shows a schematic of the experimental setup utilized. It was used a National Instruments board, model NI-USB 6211 (16 bits); a computer containing the software with the impedance analyzer developed by Baptista and Filho (2009) in LabVIEW environment; and a protoboard containing a resistance of 10 *k*Ω, which acts as an auxiliary circuit whose function is to limit the voltage in the piezoelectric transducer, thus avoiding potential damage to this device. The data acquisition (DAQ) board is responsible for capturing the response signal and, simultaneously, transmitting the excitation signal to the piezoelectric transducer. The excitation signal is generated by the impedance analyzer, which also calculates the electromechanical impedance based on the response signal captured by the DAQ. 

<p align="center">
Figure 2 - Schematic illustration of the experimental setup employed to measure the EMI signals.
</p>

![setup](https://github.com/Lorena591/Pesquisa-Doutorado-Direto/blob/main/Setup.JPG)

The aluminum beam was placed inside a thermal chamber from the brand *Thermotron*$$^\circledR$$ *S-Series* to simulate ambient temperature variations, as depicted in Fig. 3(a). The beam was positioned on a foam layer to replicate a free-free boundary condition, as shown in Fig. 3(b). Geometric and material properties of the piezoelectric transducer and the beam at 24°C are presented in the Tabs. 1 and 2, respectively.

<p align="center">
Figure 3 - (a) Thermal chamber and (b) beam positioned on a foam layer inside it.
</p>

![camara_viga](https://github.com/Lorena591/Pesquisa-Doutorado-Direto/blob/main/camara_viga.JPG)

Table 1 - Geometric and material properties of the PSI-5H4E piezoelectric transducer at 24°C.
| Property | Symbol | Value |                                                                 
| -- | -- | -- |                                                                                                   
|Length | $$L_p$$ | 13 mm|                     
|Width |$$b_p$$ |12 mm|
|Thickness |$$h_p$$ |0.2667 mm|
|Compliance |$${S}_{11}^E$$|11 1.6129×10−11 Pa−1|
|Density |$$\rho_p$$ |7800 kg/m3|
|Piezoelectric constant |$$d_{31}$$ |-327.18×10−12 m/V|
|Dielectric constant |$$\varepsilon_{33}^T$$ |3.24783.3630×10−8 F/m|
|Distance from the first PZT’s end to the origin| $$x_1$$ |81 mm|
|Distance from the second PZT’s end to the origin| $$x_2$$| $$x_1+L_p = 94 mm$$   |

Table 2 - Geometric and material properties of the 6063-T5 aluminum alloy beam at 24°C.
| Property | Symbol | Value |                                                                 
| -- | -- | -- |           
|Length | $$L_b$$| 498 mm |
|Width | $$b_b$$ | 12 mm |
|Thickness | $$h_b$$ | 3 mm |
|Young's modulus | $$E_b$$ | 69 GPa|
|Density | $$rho_b$$| 2680 kg/m3|

The signals were measured in a temperature range from 24°C to 70°C, which correspond to a large portion of the structures in operation. It was utilized a step of 5°C for the non-damage condition. In order to excite the structure, it was applied a sinusoidal frequency sweep with an amplitude of ±1 V in a frequency range of 1 Hz to 100 *k*Hz, with a step size of 1 Hz. The measurements were performed increasing the temperature and after 30 min of achieving the steady state for each one. Thirty signals were collected for each temperature and a sampling rate of 250 *k*S/s was employed.

### 2.2. Undamaged Beam with Symmetrically Coupled PZTs

To obtain the electromechanical impedance signals corresponding to the different structural dynamics (longitudinal and flexural), two PSI-5H4E piezoelectric transducers were symmetrically coupled to either side of the 6063-T5 aluminum alloy beam, as shown in Fig. 4. The experimental setup employed for data acquisition was identical to that described in Subsection 2.1 (see Fig. 2), with the exception that the object of study in this case involves a beam with two coupled piezoelectric transducers, rather than a single asymmetrically coupled PZT as investigated in the former analysis. The geometric properties of the PZTs and the beam are presented in Tabs. 3 and 4, respectively. As the same piezoelectric ceramics and beam utilized in the previous analysis (detailed in Subsection 2.1 and outlined in Tabs. 1 and 2) were employed here, their material properties have been omitted to avoid redundancy.

<p align="center">
Figure 4 - (a) Aluminum beam and (b) PZTs symmetrically coupled to it.
</p>

![VigaSimetrica](https://github.com/Lorena591/EMI-Experimental-Temperature-Variations/blob/main/VigaSimetrica.jpg)

Table 3 - Geometric properties of the symmetrically coupled PSI-5H4E PZTs.
| Property | Symbol | Value |                                                                 
| -- | -- | -- |                                                                                                   
|Length | $$L_p$$ | 12 mm|                     
|Width |$$b_p$$ |12 mm|
|Thickness |$$h_p$$ |0.2667 mm|
|Distance from the first PZT’s end to the origin| $$x_1$$ |81 mm|
|Distance from the second PZT’s end to the origin| $$x_2$$| $$x_1+L_p = 93 mm$$   |

Table 4 - Geometric properties of the 6063-T5 aluminum alloy beam with symmetrically coupled PZTs.
| Property | Symbol | Value |                                                                 
| -- | -- | -- |           
|Length | $$L_b$$| 499 mm |
|Width | $$b_b$$ | 12 mm |
|Thickness | $$h_b$$ | 3 mm |

The connection arrangement between the piezoelectric transducers for generating longitudinal and flexural waves is shown in Fig. 5. This configuration is essential for the proper excitation of the different dynamics, allowing the PZTs to operate in a complementary manner and promote the appropriate stresses, be they axial forces (longitudinal dynamics) or bending moments (flexural dynamics). 

<p align="center">
Figure 5 - Diagram of the connections between the PZTs for the excitation of (a) longitudinal and (b) flexural dynamics, by applying an electrical voltage $$V$$. The arrows on the PZTs indicate their polarization direction.
</p>

<p align="center">
<img src="https://github.com/Lorena591/EMI-Experimental-Temperature-Variations/blob/main/Conexoes.JPG" width="500">
</p>

The electromechanical impedance signals were acquired over a temperature range of 24°C to 65°C, with increments of 10°C. The beam, inserted in a thermal chamber (Fig. 6), was excited by a frequency sweep sinusoidal signal (*chirp*) with an amplitude of ±1 V, covering a range from 1 Hz to 100 *k*Hz, with a step of 1 Hz. In order to guarantee the reliability of the results, 10 sets of data were collected for each temperature, exclusively during the heating of the beam and after 30 min of achieving the steady state for each temperature. The sampling rate used was 250 *k*S/s.

<p align="center">
Figure 6 - Beam placed on a foam inside the thermal chamber.
</p>

![VigaSimetrica2](https://github.com/Lorena591/EMI-Experimental-Temperature-Variations/blob/main/VigaSimetrica2.jpg)

### 2.3. Damaged Beam with Symmetrically Coupled PZTs

In order to obtain the electromechanical impedance signals of the damaged beam, the experimental configuration of former tests, represented in Fig. 2, was replicated. The same system considered in the previous study, which covers different dynamics, was investigated with the aim of examining the effects of structural damage in different vibration contexts. The characteristics of the PZTs and the beam are detailed in the Tabs. 3 and 4, respectively, at a temperature of 24°C. A local reduction in the cross-sectional area of the beam was implemented to represent the damage. This modification was introduced symmetrically using the Emco Emcotronic CNC (Numerically Controlled Computer) lathe, model F1, shown in Fig. 7. The damage, measuring 25 mm in length and extending across the full width of the beam, features depth reductions corresponding to 3% and 6% of the original thickness of the structure, with half of this reduction distributed on each face of the beam. The damage was positioned 89 mm from the PZT, located at coordinate $$x_D$$ = 182 mm, as shown in Fig. 8.

<p align="center">
Figure 7 - CNC lathe used for machining structural damage.
</p>

<p align="center">
<img src="https://github.com/Lorena591/EMI-Experimental-Temperature-Variations/blob/main/CNC.jpg" width="700">
</p>

<p align="center">
Figure 8 - Beam-like structure with two PZTs transducers and a symmetric damage.
</p>

![setup](https://github.com/Lorena591/Pesquisa-Doutorado-Direto/blob/main/VigaDano.jpg)


The electromechanical impedance signals were collected over a temperature range of 24°C to 65°C, with increments of 20°C. A *chirp* signal with amplitude of ±1 V was applied, in the range of 1 Hz to 100 *k*Hz, with a step of 1 Hz. 10 sets of data were collected for each temperature, with a sampling rate of 250 *k*S/s. Measurements were conducted after gradually increasing the temperature and maintaining a steady state for 30 minutes at each one.

### 2.4. Free PZT

The experimental tests consisted of collecting electromechanical impedance signals from the PSI-5H4E piezoelectric transducer, from *Piezo Systems*$$^\circledR$$, shown in Fig. 9. The geometric characteristics of this transducer are detailed in Tab. 5. These properties are identical to those used in the experimental tests of the coupled system (beam and asymmetrically coupled PZT), guaranteeing repeatability of the test conditions.

<p align="center">
Figure 9 - Piezoelectric transducer PSI-5H4E.
</p>

<p align="center">
<img src="https://github.com/Lorena591/EMI-Experimental-Temperature-Variations/blob/main/PZTDesacoplado.jpg" width="700">
</p>

Table 5 - Geometric properties of the free PSI-5H4E PZT.
| Property | Symbol | Value |                                                                 
| -- | -- | -- |                                                                                                   
|Length | $$L_p$$ | 13 mm|                     
|Width |$$b_p$$ |12 mm|
|Thickness |$$h_p$$ |0.2667 mm|

The experimental setup employed for data acquisition was identical to that used in Subsection 2.1 (see Fig. 2), with the exception that, in this case, the object of study is a free piezoelectric transducer, as depicted in Fig. 10. Electromechanical impedance signals were collected at temperatures of 24°C, 45°C and 70°C. This was achieved using a *chirp* sinusoidal sweep with an amplitude of ±1 V, spanning a frequency range from 1 Hz to 100 *k*Hz, in increments of 1 Hz. The sampling rate was 250 *k*S/s, and 10 sets of signals were obtained for each temperature. The measurements were taken exclusively during the heating process of the piezoelectric element. It should be noted that the high fragility of the PZT, combined with the vibrations of the thermal chamber itself and, above all, the circulating air currents within, caused disturbances to the piezoelectric transducer, which compromised the EMI and led to negative interference in the signals, such as increased noise.

<p align="center">
Figure 10 - PZT positioned on a foam layer inside the thermal chamber.
</p>

<p align="center">
<img src="https://github.com/Lorena591/EMI-Experimental-Temperature-Variations/blob/main/PZTDesacoplado2.jpg" width="800">
</p>

#### References
Baptista, F.G. and Filho, J.V., 2009, 'A new impedance measurement system for pzt based structural health monitoring', *IEEE Transaction on Instrumentation and Measurement*, **58**(10), 3602–3608, doi: 10.1109/TIM.2009.2018693.

## 3. Authors
- Lorena Lopes Dias (UNESP/FEIS)
  - e-mail: lorena.dias@unesp.br
  - ORCID: https://orcid.org/0000-0002-1870-6103
  - Lattes: https://lattes.cnpq.br/0026374599165487
- Camila Gianini Gonsalez-Bueno (UNESP/FEIS)
  - e-mail: camila.gg.bueno@unesp.br
  - Lattes: http://lattes.cnpq.br/8692204806659405
- Douglas Domingues Bueno (UNESP/FEIS)
  - e-mail: douglas.bueno@unesp.br
  - Lattes: http://lattes.cnpq.br/3453163833110618

## 4. How to cite

Cite Github repository:

 - Dias, L. L., Gonsalez-Bueno, C. G. & Bueno, D. D. (2023), EMI-Experimental-Beam-Temperatura-Variations, *GitHub Repository*, https://github.com/Lorena591/EMI-Experimental-Beam-Temperature-Variations.

If you are using a LaTeX Editor, you can cite this repository using the BibTeX citation:

```
@misc{GithubDias2023,
	author         = {Dias, L. L. and Gonsalez-Bueno. C. G. and Bueno, D. D.},
	title          = {EMI-Experimental-Beam-Temperatura-Variations},
	year           = {2023},
	note           = {Github Repository, \url{https://github.com/Lorena591/EMI-Experimental-Beam-Temperature-Variations}}
}
```

The dataset, pertaining to the EMI collected from a beam with an asymmetrically coupled PZT, was utilized in this publication:

- Dias, L. L., Bueno, D. D. & Gonsalez-Bueno, C. G. (2023), 'SHM based on the Electromechanical Impedance Technique with Temperature Variations: Theoretical and Experimental Approach', _in_ 27th International Congress of Mechanical Engineering (COBEM), doi: 10.26678/ABCM.COBEM2023.COB2023-1251.

If you are using a LaTeX Editor, you can cite this article using the BibTeX citation:

```
@inproceedings{Dias2023,
  author         = {Dias, L. L. and Bueno, D. D. and Gonsalez-Bueno, C. G.},
  title          = {{SHM} based on the Electromechanical Impedance Technique with Temperature Variations: theoretical and experimental approach},
  booktitle      = {27th International Congress of Mechanical Engineering (COBEM)},
  year           = {2023},
  adress         = {Florianópolis, SC, Brazil},
  note           = {doi: 10.26678/ABCM.COBEM2023.COB2023-1251},
 }
```

## 5. Funding
São Paulo Research Foundation (FAPESP), Grant Number 2021/12008-2.

![fapesp](https://github.com/Lorena591/Pesquisa-Doutorado-Direto/blob/main/fapesp.png)


</div>
