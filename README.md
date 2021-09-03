# University of Liverpool Pharmacology  - DDI_ATZ_RTV_RIF

## Aim
This PBPK model aims to simulate the drug-drug interactions (DDIs) between Rifampicin (RIF) and Ritonavir-boosted Atazanavir (ATV/r), focused on the main enzymes and transporters involved in these drugs metabolism. Furthermore, to provide simulations of potential dose adjustments to overcome the RIF induction effect.

## Drug
The PBPK model was developed using in vitro data for the following drugs: Atazanavir (ATV), Ritonavir (RTV), and Rifampicin (RIF). RIF, used in the treatment of TB for patients coinfected with HIV, is a substrate and a potent inducer of cytochrome P-450 oxidative enzymes and the P-glycoprotein (P-gp) transport.  ATV, an HIV protease inhibitor (PIs), is a P-gp and CYP3A4 substrate extensively metabolized by the liver, and the co-administration of both drugs promotes a substantial decrease in ATV plasma concentration. RTV is a substrate of CYP3A and CYP2D6, additionally, it is a potent inhibitor of CYP3A. Moreover, it is considered a P-gp substrate and inhibitor. The coadministration of ATV/r improves the pharmacokinetic parameters and efficacy of ATV and, the virologic activity, decreasing the genetic resistance.

## PBPK model
The model was designed using Simbiology® v.5.8.2, a product of MATLAB® v.R2019a (MathWorks, Natick, MA, USA 2019). The detailed methodology is described in the published manuscript entitled: Predicting Drug-Drug Interactions between Rifampicin and Ritonavir-Boosted Atazanavir Using PBPK Modelling, Clinical Pharmacokinetics - DOI: 10.1007/s40262-021-01067-1.

## Dose and dosage
The drug dosages used to validate the model were ATZ 300 mg twice-daily, RIF 600 mg once-daily, ATV/RTV 300/100 mg once-daily, and ATV/RTV/RIF 300/100/600 once-daily, as described in the clinical studies. To simulate dose adjustments to overcome the DDIs, dosages of 300/100, 300/200, 400/100, 400/200, 600/100, and 600/200 of ATV/RTV twice-daily were used.

## Clinical data set
Two clinical studies, Acosta et al., (2007) and Burger et al., (2006) were used to obtain the observed clinical data.
  
## Conferences/Manuscript
This model was presented as a poster on “20th International Workshop on Clinical Pharmacology of HIV, Hepatitis & Other Antiviral Drugs”, May 2019 – Netherlands. 
Accepted manuscript - Predicting Drug-Drug Interactions between Rifampicin and Ritonavir-Boosted Atazanavir Using PBPK Modelling, Clinical Pharmacokinetics - DOI: 10.1007/s40262-021-01067-1 

## Reference
Manosuthi, W., Wiboonchutikul, S., & Sungkanuparph, S. (2016). Integrated therapy for HIV and tuberculosis. AIDS research and therapy, 13(1), 22.
Finch, C. K., Chrisman, C. R., Baciewicz, A. M., & Self, T. H. (2002). Rifampin and rifabutin drug interactions: an update. Archives of internal medicine, 162(9), 985-992.<br/>
Meintjes, G., Brust, J. C., Nuttall, J., & Maartens, G. (2019). Management of active tuberculosis in adults with HIV. The Lancet HIV, 6(7), e463-e474.<br/>
Acosta, E. P., Kendall, M. A., Gerber, J. G., et al (2007). Effect of concomitantly administered rifampin on the pharmacokinetics and safety of atazanavir administered twice daily. Antimicrobial Agents and Chemotherapy, 51(9), 3104-3110.<br/>
Burger, D. M., Agarwala, S., Child, M., Been-Tiktak, A., Wang, Y., & Bertz, R. (2006). Effect of rifampin on steady-state pharmacokinetics of atazanavir with ritonavir in healthy volunteers. Antimicrobial agents and chemotherapy, 50(10), 3336-3342.<br/>
Bertz, R. J., Persson, A., Chung, E., Zhu, L., Zhang, J., McGrath, D., & Grasela, D. (2013). Pharmacokinetics and Pharmacodynamics of Atazanavir‐containing Antiretroviral Regimens, with or without Ritonavir, in Patients who are HIV-positive and Treatment-naïve. Pharmacotherapy: The Journal of Human Pharmacology and Drug Therapy, 33(3), 284-294.<br/>
Achenbach, C. J., Darin, K. M., Murphy, R. L., & Katlama, C. (2011). Atazanavir/ritonavir-based combination antiretroviral therapy for treatment of HIV-1 infection in adults. Future virology, 6(2), 157-177.<br/>


 
