# Untargeted Metabolomics: Compound identifications from MS2 (MS/MS) data

Once you have completed statistics and collected MS2 data you are faced with the daunting task of interpreting fragmentation data. While this is a difficult process it quickly becomes manageable when approached with the correct methodology. 

## Database searches and basic tools: 

**Database searches** – The first thing you should do with your MS2 fragmentation spectra is search them against a database of known MS2 fragmentation spectra, a good one is MetFusion (http://msbi.ipb-halle.de/MetFusion/). Database searches will sometimes correctly identify your spectra, but more often will just show you what compounds your unknown is chemically similar to. Remember that a good match to something in the database is not a confirmed ID and that databases are heavily biased by the nature of previous research. 

Some other good databases: 
    * [http://metlin.scripps.edu/index.php](http://metlin.scripps.edu/index.php)
    * [http://www.hmdb.ca/#](http://www.hmdb.ca/#)
    * [http://www.massbank.jp/SearchPage.html](http://www.massbank.jp/SearchPage.html)

**Molecular formula calculator** – This tool uses high resolution exact mass data to determine elemental composition. It can be used to quickly determine the atomic make up of an unknown. One obstacle to using this tool is that as molecular weight increases the number of possible molecular formulas increases as well. If this is preventing you from determining the formula of your unknown try getting a formula for several of its fragments. Then, by using the number of heteroatoms like oxygen and nitrogen in the different fragments you can narrow down the possibilities for the molecular ion’s molecular formula. When using this tool remember that you are unlikely to encounter molecules with atoms aside from C H O and N, but you will occasionally. Remember to add or subtract a hydrogen depending on ionization mode to determine the compound’s neutral mass. 

[http://www.bmrb.wisc.edu/metabolomics/mass_query.php](http://www.bmrb.wisc.edu/metabolomics/mass_query.php)

A version of this tool is built into Thermo Xcalibur and can be found online as well, a good one is [http://www.chemcalc.org/mf_finder/mfFinder_em_new](http://www.chemcalc.org/mf_finder/mfFinder_em_new). 

**Exact mass calculator** – Calculates the exact mass for a given molecular formula, a good basic one is http://www.sisweb.com/referenc/tools/exactmass.htm. 



## Literature review:

This is the most important step for finding the identity of an unknown compound. You will need to spend a large amount of time looking through scholarly articles about your organism(s) of interest, and any leads you may have acquired from your database searches. You should have already done some research at this point and should have an idea of what to expect for the predominant metabolites in your organism(s) of interest. Make sure to use a variety of search terms and phrasings when searching to get as wide of a range of articles as possible. For searches I recommend using the scholarly article search Google Scholar [http://scholar.google.com/](http://scholar.google.com/). Keep in mind when looking through articles you do not have to read everything. By skimming intelligently and using the ctrl+f “find” function you should be able to quickly determine if an article is valuable or not. Make sure to keep track of useful articles to go back to later. 

Pubmed is another scholarly search: [http://www.ncbi.nlm.nih.gov/pubmed](http://www.ncbi.nlm.nih.gov/pubmed).

For finding articles that reference a particular compound or to find compounds with a particular molecular formula SciFinder can be useful: [https://www.lib.umn.edu/services/external_auth?id=sfsw](https://www.lib.umn.edu/services/external_auth?id=sfsw). 


## Manual Spectra analysis: 

While the prospect is intimidating, useful information can be garnered by a thorough and thoughtful manual analysis of your fragmentation spectra. Most importantly manual examination will allow you to compare your spectra to one another, revealing trends that otherwise may not have been noticed during database searches and literature review. This skill must be built by practice more than any of the others discussed here. The more time you spend looking at spectra and trying to interpret them the better you will become. Pay careful attention for patterns in the fragmentation spectra even between experiments and it will quickly start to pay off. Many of these patterns can reveal what class of compounds an unknown is in, or what it may be chemically similar to. 

As previously mentioned, some groups of compounds have common fragmentation patterns you can learn to recognize, for instance, below are fragmentation spectra from five different flavonoid glycosides. While they are slightly different, they all show a loss of a sugar group to reveal the mass of the flavonoid agylcone. 

Similarly the presence of a 191 ion in all of these fragmentation spectra reveal the presence of a quinic acid moiety. 

Making comparisons between your spectra can yield valuable information about unknown compounds. As an example, nothing from the database searches for the two compounds below indicated that they might be chemically related. But manual observation reveals that they are the same spectrum but part of one is shifted by a mass of 14, which corresponds to one CH2 unit in a hydrocarbon chain. This indicates that these two compounds are actually very similar, the only difference between being the presence of a carbon. Perhaps one has an ethyl group where the other compound has a methyl group at the same place. With that knowledge in hand if you identify one ion, you can quickly deduce the identity of the other. In the example below the red circled ions represent fragments shifted by 14 Da (one CH2) from each other. The green circled ions are fragments shared in common between the two compounds.

# FLAG IMAGES MISSING!

## Running standards: 

Once you have a good hypothesis for what an unknown compound is, you must test that hypothesis using an authenticated sample of the compound. The authentic standard is acquired by either purchasing it from a chemical vendor or via synthesis. Before purchasing or attempting synthesis please check the lab chemical inventory as well as other associated labs. If none of those options is possible its identity must be confirmed with techniques that are outside the scope of this document. Assuming an authentic standard is available a very dilute sample of it should be prepared (the concentration will vary based on every compounds’ properties). Using the targeted fragmentation (tMS2) method you should have already developed for the unknown run a pooled sample and your authentic standard consecutively. If the retention time and MS2 spectra of the authentic standard matches that of your unknown then you have identified the unknown. As a final test spike some of the pooled sample with the standard to confirm unambiguous co-elution of the standard and your unknown. If you do not get a match, don’t be frustrated it often takes several attempts to identify the right standard to use. 