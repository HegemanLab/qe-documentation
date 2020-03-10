# QE UPLC Line Cleaning

About once a month or whenever background becomes too high or a specific contaminant linked to the lines is noticed the LC lines should be cleaned. **Please note this is not a cleaning procedure for columns and your column should be removed and replaced with a blank connector (red line on right of stack) and the LC detached from the source prior to beginning this procedure.** To clean the LC lines use the following steps:

1. If you have a specific contaminant you need to remove from the lining check pg. 14 (table 2) of the **(FLAG: add document to git and link)** “Controlling Contamination in UltraPerformance LC/MS and HPLC/MS Systems” booklet located in the QE SOP binder or do your own searching. If only general cleaning is needed use a solution of 25/25/25/25 Isopropanol/Acetonitrile/Methanol/0.5% formic acid in water.

2. **Remove the LC line from the source and replace your column with the cleaning connector if you have not done so already.**

3. Place the cleaning solvent you will be using on any LC line and purge that line as normal

4. Make an autosampler vial containing each of the following:
    i. 0.5% formic acid in water
    ii.  methanol
    iii. Isopropanol
    iv. Acetonitrile
    
5. Load the pre-made sequence file located in the shared folder. Be sure it has not been changed and will do the following:
    i. Inject 40ul from the vials above in the order listed above twenty times each. This is to clean the sample loop, which would not be cleaned without an injection.
    ii. Run an isocratic run of < 1min for each injection using the solvent line that you have replaced with wash solvent
    iii. Note: Need to turn on MS to allow injections to occur, but DO NOT connect line to source

6. When the injections have finished run the LC overnight at a lower flow rate using the cleaning solvent. (Make sure there is enough solvent so you don’t run out at the flow rate your running)