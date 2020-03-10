# QE Calibration (adjusts the m/z, everything after S-Lens)

**What is calibration?** Calibration is independent of the source type and it is crucial to achieve optimal mass transmission and mass accuracy. All calibration parameters are stored in the instrument and are common for all analytes. The MS mass calibration should be performed weekly. When MS mass calibration has not been done for either positive or negative for 8 days or more the “P” (performance status) will be yellow. If you are concerned about the accuracy at anytime: you can perform “calmix evaluations” (on the evaluate tab in Tune) and if anything fails then “calibrate” the corresponding parameter. 

1. Load the calibration tune file in Tune (either positive or negative). You can use your own or a shared file (see picture). If you change please do not save over shared file but rename. 
![](/images/QE_calibration-image01.png)

2. Start with HESI probe at position B you can move towards A or C as needed. The probe should be at micrometer 1.75 and side-to-side position of 0 (see page 5 of source hardware manual).
    
3. Use + or – calibration mix. In -20°C (coming from Adrian’s office first right at end, only -20°C ) on second shelf on right.  100ul aliquots. 
    
4. Wash line and syringe **before**, **between**, and **after** with 50/50 methanol/water and put in LC waste. Load the calibration solution into a 25 μL or a 500 μL syringe and place it in the syringe pump. Position syringe correctly and put the push bar against the head of the plunger. 
    
5. Un-attach LC line and attach line to end of syringe and to source. 
    
6. Click on the syrinbeforege pump icon and make sure the proper syringe type and volume are entered in the dialog box. Set the flow on the syringe pump to 5 μL/min. 
![](/images/QE_calibration-image02.png)

7. Turn tune on play and then start syringe pump. 

8. Monitor the real-time display of the mass spectrum to ensure that a stable spray of solution enters the mass spectrometer. Observe the mass spectrum (manual push some calmix in to get a good amount of ions in to start) and make sure all calibration masses are present. (See pictures on last page) 
    > Note: n-butylamine and the caffeine fragment will not be visible in the selected scan range. 
 
9. Before starting the calibration procedure, please make sure to have a satisfactory sensitivity and good spray stability. In order to achieve these results, the optimal probe position, spray voltage, gas flow rates, capillary temperature and S-Lens voltage have to be determined. As a rule, the inject times should be less than 5ms, base peak intensity should be around 1E8 for caffeine (E7 is OK), and TIC variation should be <10%. See picture of instrument status.
    * Adjust the following:
            i. Change position of probe 
            ii. Increase sheath gas 
            iii. Increase syringe flow rate
![](/images/QE_calibration-image03.png)

10. When above looks good go to Calibration tab and start MS Mass calibration.
        a. Select pos. or neg. 

**Note**: if starting with a new calibration tune file: Use the following scan and source parameters. Use scan parameters below (change to pos or neg).

Source starting parameters:
* Sheath gas: 10°C
* Aux: 0°C
* Lens: 0°C   (524 won’t show up unless you turn down) 
* Cap temperature:  275- 300°C
* S lens: 50
* Spray voltage 4 kV 
* Heat temperature: 0°C (never will actually reach 0°C b/c of cap temp) 

![](/images/QE_calibration-image05.png)

**Pierce LTQ VELOS ESI Positive Ion Calibration Solution Spectrum**. Formulation: caffeine (2µg/mL), MRFA (1µg/mL), Ultramark 1621 (0.001%) and n-butylamine (0.0005%) in an aqueous solution of acetonitrile (50%), methanol (25%) and acetic acid (1%).

![](/images/QE_calibration-image04.png)

**Pierce ESI Negative Calibration Solution Spectrum Formulation**: sodium dodecyl sulfate (2.9µg/mL),sodium taurocholate (5.4µg/mL) and Ultramark 1621 (0.001%) in an aqueous solution of acetonitrile (50%), methanol (25%) and acetic acid (1%).

**FLAG: Missing Calmix negative tune image!? In physical SOP, not in Word documents.**