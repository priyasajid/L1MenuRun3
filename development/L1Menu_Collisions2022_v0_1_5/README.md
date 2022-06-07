# L1Menu_Collisions2022_v0_1_5

[![online preview](https://img.shields.io/badge/Online%20preview-click%20here-blue)](https://htmlpreview.github.io/?https://github.com/priyasajid/L1MenuRun3/blob/master/development/L1Menu_Collisions2022_v0_1_5/L1Menu_Collisions2022_v0_1_5.html)

**Comment:** Menu for MWGR February, 2022, adding 7 new algos. 3 new Tau seeds, two with overlap removal and one with increased threshold of an existing double tau seed. And 3 Single Tau monitoring seeds and a LLP Jet seed.[Scale set reference, for grammar version 0.10]

- new L1 Double Tau + Jet seed & increasing threshold of old Double tau seed [https://its.cern.ch/jira/browse/CMSLITDPG-961]:
    - L1_DoubleIsoTau26er2p1_Jet55_OvRm_dR0p5
    - L1_DoubleIsoTau35er2p1 (increased threshold from previous seed L1_DoubleIsoTau32er2p1)

- new Double Jet + One Tau seed [https://its.cern.ch/jira/browse/CMSLITDPG-962]:
    - L1_DoubleJet35_Mass_Min450_IsoTau45er2p1_RmOvlp_dR0p5

- new L1 seed for displaced Jet [https://its.cern.ch/jira/browse/CMSLITDPG-963]: 
    - L1_HTT120_SingleLLPJet40

- Low pT threshold L1 Tau seeds [https://its.cern.ch/jira/browse/CMSLITDPG-964]:
    - L1_SingleIsoTau30er2p1
    - L1_SingleIsoTau32er2p1
    - L1_SingleIsoTau36er2p1

**Tag/GT:** [![L1Menu_Collisions2022_v0_1_5_xml]https://cms-conddb.cern.ch/cmsDbBrowser/search/Prod/L1Menu_Collisions2022_v0_1_5_xml]

**synthesized and tested in uGT test crate**

**NOTE:** The default behavior of the script sets the prescales of seeds using NotBptx or Bptx to zero. This is due to problems emulating NotBptx in ZeroBias. If you wish to include the prescale information for these seeds, use the --includeBptx option.
