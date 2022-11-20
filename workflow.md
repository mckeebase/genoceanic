# GenOCEANIC base
openEHR Clinical Data Repository (CDR) 
this file is going to create a very simple picture of what genoceanic is and how it works in the light of current state of Test Directory

1. doctor logs on to GenOCEANIC
2. search for patient
3. review phenotypes
4. select INDICATION (this is the same as "Disease" in the 100K)
5. review ELIGIBILITY (from the Test Directory)
6. assert ELEMENTS of eligibility
7. add ADDITIONAL INFO
8. 😄 CDS detects whether eligibility criteria are met
9. generate REQUEST comprising...
    * INDICATION
    * ELIGIBILITY ELEMENTS
    * PHENOTYPES
    * Addiitonal information
