

This is the model of the RTC3 counter described in the article:  
**Synthetic gene networks that count.**   
Friedland AE, Lu TK, Wang X, Shi D, Church G, Collins JJ. Science. 2009 May
29;324(5931):1199-202. PMID:
[19478183](http://www.ncbi.nlm.nih.gov/pubmed/19478183) , DOI:
[10.1126/science.1172005](http://dx.doi.org/10.1126/science.1172005)

Abstract:  
Synthetic gene networks can be constructed to emulate digital circuits and
devices, giving one the ability to program and design cells with some of the
principles of modern computing, such as counting. A cellular counter would
enable complex synthetic programming and a variety of biotechnology
applications. Here, we report two complementary synthetic genetic counters in
Escherichia coli that can count up to three induction events: the first, a
riboregulated transcriptional cascade, and the second, a recombinase-based
cascade of memory units. These modular devices permit counting of varied user-
defined inputs over a range of frequencies and can be expanded to count higher
numbers.

The 3 arabinose pulses are implemented using events, one for the start of
pulses and one for the end. The variable pulse_flag changes arabinose
consumption to fit behaviour during pulses and in between. To simulate two
pulses only, set the pulse length of the third pulse to a negative value
(though with an absolute value smaller than the pulse intervall length).

Originally created by libAntimony v1.4 (using libSBML 3.4.1)

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)

