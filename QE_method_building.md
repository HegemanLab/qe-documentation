# Q Exactive Method Building

1. Go to `Start > Programs > Thermo Xcalibur > Xcalibur` to display the Xcalibur Home Page window.  Or open an old method and modify but DO NOT save over someone’s method, select `Save As`, and modify the method name

2. Choose `Go To > Instrument Setup` to display the Instrument Setup window. 

3. Click on the Chromeleon icon on the left to begin setting up the LC method. Change necessary parameters by selecting icons ie column temperature, multistep gradient, flow rate, max pressure, etc. The relay start should look exactly like picture.
![](/images/QE_method_building-image01.png)
**FLAG: Physical SOP has an X mark over the three device names in the photo above with a not that reads "Relay-4"**
> Note: Do not leave anything blank in the multistmethod-building.mdep gradient put 0 for solvents you are not using and put a curve value in for all, most users will use a linear curve of 5. Also when LC method imethod-building.mds complete go to commands icon to type in the correct finish time at the very bottom it sometimes won’t be correct. Please see examples below.

4. Click on `Q Exactive - Orbitrap MS` in the `View bar` to display the Method Editor.

5. In the Method Editor, drag an experiment symbol (for example, `Full MS - SIM`) from the Workflows pane (bottom left) to the gray bar in the Graph pane. A corresponding time bar is displayed in the Scan Groups pane. 
![](/images/QE_method_building-image02.png)
![](/images/QE_method_building-image03.png)

6. Edit the fields of the `Properties` pane (right) to set up the experiment parameters. Refer to the Q Exactive Software Manual or the Q Exactive Tune Help for a description of the available parameters. Change from standard to advanced to see more options e.g. the ability to switch to centroid instead of profile. 

7. Assign a correct tune file:  On the right browse for the tune file and assign it to the experiment. 

8. Check that the method time for LC matches MS method duration and run time. 

9. Save file with a unique filename and put it in your methods folder in your folder in the `D:` drive or `C:` Xcalibur.
![](/images/QE_method_building-image04.png)