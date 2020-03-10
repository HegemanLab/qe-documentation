# Q Exactive Check in and Starting a Sequence

1. Please consider if you need to run this on the QE or if another system would work. 
2. The instrument is highly sensitive please try injecting very low concentrations and then increase if needed. If you have not run similar samples on the QE please check to make sure if your sample is OK to put on the QE.
3. Look at sweep cone if visibly dirty and hasn’t been cleaned in 2-3 weeks cleran it. Also check when ion transfer tube last cleaned. See corresponding SOP for cleaning procedures. 
4. Check HESI probe height and move if necessary by loosening black knob on right. 
5. Check top off solvent tower to see if the correct solvents are in the lines you want if not change and purge. \(Purge by opening purge valve and in Chromeleon the second tab of on the left start purge, you will be asked if you opened the valve\). 
6. Put your column in compartment and remove LC line from source. Set end of line in waste container. Start flow and ensure it isn’t leaking at column fittings. 
7. Equilibrate/wash your column when LC line is removed from source to not dirty the source. When finished stop flow and reattach LC line to source.
8. Turn on DAD lamps \(if you are using\) and wait for column temperature to heat up or cool to correct temperature. 
9. Load your tune file in Tune and turn flow of LC on. Watch in Tune for signal and check a known mass for accuracy. For example, + m/z 371.101790 \(deamethylcyclopentasiloxane\) is a common containment/background ion check that the first two decimal places are identical and the third place should only vary slightly. If mass accuracy off you may want to calibrate if your experiments needs high mass accuracy. Also if the P is yellow on Tune then the system has not been calibrated in either + or -or both for more than 8 days. 
10. When making sequence in Xcalibur start and end with a shared blank method, inject 10 ul of water \(check RA1 tray position\) and save file to the `D:Shared &gt; Shared\_blanks &gt;monthyear` folder. If you have the instrument for more than one day you can run the last shared blank at the end of your time. Use method in Shared Blank folder based on flow rate and etc. 
    ![](/images/MS_check_in_and_starting_a_sequence-image01.png)
11. The only columns that require information for a sequence are the following: 
    file name, path, inst. Method, position, and injection volume. 
12. Sequence can be started if the following are done:
    1. Solvents correct and sufficient volume for your run.
    2. Samples are in auto sampler in correct positions.
    3. Column on, not leaking, column compartment at correct temperature.
    4. DAD lamps ON if using
    5. LC line connected to probe from DAD or column compartment.
    6. HESI probe height correct.
    7. Mass accuracy and presence of signal confirmed. 
    8. Your sequence starts and ends with shared blank. 
13. In Xcalibur start sequence, confirm sequence lines to run and that all devices will go into standby after run is complete. Click OK.
    1. Xcalibur will now ask if it should turn devices on if not already. Click OK. 
    2. Watch Xcalibur until Dionex syringe starts moving and you see needle inject sample. 
    3. Go to the real time plot in Xcalibur top left icon 3rd over. When you see signal then no errors have occurred in starting your sequence and you can walk away. NEVER walk away after starting your sequence until you have seen a successful injection and data being produced. It is also a good idea to check after the first sample has finished and every few hours when possible. 
    4. If an error occurs \(don’t panic it happens often and to everyone\): in Xcalibur go to `Actions > All Devices Standby` which should clear the error message and then hit stop run. Now go to the DMP log and see what the error was and attempt to correct.  Delete sequence that is queued at left and go over checklist at the minimum you will have to turn lamps back on \(Take control of Chromeleon\).  Resubmit sequence and repeat above checklist. 



