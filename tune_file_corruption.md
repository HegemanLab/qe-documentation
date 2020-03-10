# Tune file corruption

1. Tune files may become corrupted and you will usually observe a difference in sheath or aux gas, for example you may have saved Sheath at 50 and Aux at 20 when you push play it may switch to a different value. Another scenario is that when you check your tune file it is fine but when it is run in your method under Xclaibur then the sheath gas value is different. 

2. To fix your tune file do the following:
        a. Write down the correct information for your tune file under  the HESI source section  (Sheath, Aux, Sweep gas, S-lens & Spray voltage, Heater and Cap temp.)
        b. Open an original tune file from the folder `C:/xclaibur/methods/serviceengineer`
        c. In tune save as the service engineer file in your folder as a different name than the corrupted file. 
        d. Change all HESI source parameters and save.
        e. Hit play in tune to make sure all values are as they should be. 
        f. Go to your method file and change to your new tune file.
        g. Delete your old tune file. 