# **Q Exactive method for +/- polarity switching**

1. Open the tune page and tune file you would like to use. It is best to have the source parameters \(second tab under instrument control on tune page\) for + and - be similar if not identical.
2. Once all other settings, such as AUX & sheath gas flow rate, and heater temperature, are as desired set the polarity to negative and then go to `File > Save As` and choose a file name that denotes a neg and pos tune file. \(DO NOT overwrite someone else’s file!\)
3. Then change the polarity to positive and Save As once again with thesamefile name. \(This doesn’t make sense but go with it\). Yes, replace existing file. Now this tune file has both positive and negative information saved in it.
4. Open the method page and a method file. Set the tune file to the newly created +/- one.
![](/images/MS-polarity_switching_method-image01.png)
5. Add two full MS scans to the method one set to positive and one set to negative. Extend both for the entire length of run. During the entire length of the run the QE will switch between the positive and negative scan. Assign the desired values to the settings then save the method. \(DO NOT overwrite someone else’s file!\) See pictures below.

Note: the LC method will be the same but you can have differences in the MS method. For example different scan ranges.

Before
![](/images/MS-polarity_switching_method-image02.png)

After
![](/images/MS-polarity_switching_method-image03.png)

> Note: When you open the `.raw` file you will have to right click and go to ranges and select either the positive or negative as your scan filter.



