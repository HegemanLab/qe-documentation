# Splitting positive and negative scans from a raw file with Genedata

When collecting + & - data in the same run the data must be separated in order to properly analyze the chromatograms.

Genedata can easily accomplish this, even if you are not going to further analyze or refine the data with Genedata. 

1. In order to separate the + & - chromatograms you must add  the selectioyn tool to your workflow after your data has been imported:
![](/images/data-splitting_polarity-gendata-image01.png)

2. Once added click on the selection tool to bring up its settings. Make sure chromatograms is checked and NOT spectra. Then set the “By:” category to “Names” and then write *pos* or *neg* in the “Pattern” box depending on which of the two chromatograms you’d like to extract. Make sure the lower box is set to include.  Genedata is case sensitive. ![](/images/data-splitting_polarity-gendata-image02.png)

3. Then proceed to refine and analyze the data normally, if you intend to do this in a different program you can export the data in any format desired.![](/images/data-splitting_polarity-gendata-image03.png)