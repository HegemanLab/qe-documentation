# Q Exactive Tuning & Making a Tune File

**What is tuning?** Tuning optimizes the Q Exactive system for a particular component in order to obtain the highest sensitivity and stability. This includes probe position and gas flow. The tune files can be saved and are specific to the analyte and the LC conditions used such as flow rate and solvents. When dealing with a sample of unknowns tuning can be done with calibration solutions. Tuning and making a tune file are two different tasks but have some overlap in the steps. Please note that the automatic tuning procedure only tunes the entrance and exit lens potentials of the C-trap. The ion optics parameters are not changed. For any instrument method, an appropriate tune file needs to be provided. Change probe position, gas flow rates and temperatures and spray voltage according to the LC flow rate used. Save the adjusted parameters in a tune file, which can be loaded in an instrument method.

1. Set up LC lines to infuse from syringe pump and connect with a “T” to use your flow rate with 50/50 of your solvents from LC.

2. You should always tune to a known mass. Infuse 2-10ug/ml of your compound(s) of interest or calibration solution. 

3. In Tune Start the instrument by clicking on:
![](/images/QE_tuning_and_making_a_tune_file-image01.png)

4. In Chromeleon start the flow with 50/50 of your solvents.

5. In Tune start syringe flow rate 5 ul/min and increase until there is a signal intensity of E6 for your ions. 

6. Use the below source parameters and adjust the settings to the following values as a starting point:
    * For 0.400 ml/min flow, sheath gas flow rates between 30-60
    * Aux gas flow rate: 10-20
    * Sweep gas rate: 1 with sweep cone on
    ![](/images/QE_tuning_and_making_a_tune_file-image02.png)

7. Set the scan parameters for tuning and calibration using the Scan parameters windows in Tune.
![](/images/QE_tuning_and_making_a_tune_file-image03.png)
 
8. Observe the mass spectrum and make sure all calibration masses are present (or your compound of interest): n-Butylamine: m/z 74, Caffeine: m/z 138 (fragment), 195, MRFA: m/z 524, Ultramark 1621: m/z 1022, 1122, 1222, 1322, 1422, 1522, 1622, 1722, 1822
![](/images/QE_tuning_and_making_a_tune_file-image04.png)
> Note: n-butylamine and the caffeine fragment will not be visible in the selected scan range. The scan range will have to be changed accordingly.

9. Watch the TIC stability by performing mass traces and observe plot of masses in lower box. Adjust the position of the probe, gas flow rates, and the spray voltage to achieve a stable and intense spray (see step 10). Check you are having a stable spray by monitoring the injection time in the scan header as well as the TIC variation in the instrument status. The variation should be 15% or less, the injection time for the calibration solution should be less than 5ms, and the intensity of the base peak > 1e8. See below picture of instrument status.
> Note: If the TIC variation is large, adjust the probe position and gas flow rates until you have reached good signal intensity and a low variation.

10. To optimize your tune file change source settings and observe as described above:
    a. Heater temp: start 300, increase 25 unit steps and observe TIC plot if no change return to start value if TIC increases increase another step, repeat. Continue this same method with each source parameter. 
    b. Sheath gas: start 10, 5 unit steps
    c. Aux gas: start 5, 5 unit steps
    d. Sweep gas: 0 without sweep cone, keep at 1 if sweep cone is on when you increase >1 the S/N will increase. 
    e. Spray voltage: not flow rate dependent keep at 3.5-4
    f. Cap temp: Start 275 (at the lowest), 25 unit steps, usually 300-350
    g. Leave S-lens at 50.0
    > Note: capillary and heater temp are usually similar. 

11. To optimize the instrument for the calibration solution, select the Tune tab in the tune page, select TIC or mass (if not calibration solution) and click on start to start the tune procedure. Tune tab by TIC or mass: select tune (you are performing an automatic tuning of C trap to the HCD) if HCD mode checked (lens for transmission). 

12.  Save the tune file and the adjusted parameters (including the source parameters) by clicking on `File > Save Tune File` as.  