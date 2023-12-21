# Logical_Embeddings_case_study
Probabilistic Verification using PRISM of ADTMC and APCTL/APCTL* properties by converting them to SDTMC and PCTL/PCTL*

Open PRISM as GUI. Load the model for each case study and parse and build it using keys 'F2' and 'F3'. Move to the properties bar and open the properties list. Click on each property and hit 'F5' to verify and view the result.

For PRISM in the command line, move to the PRISM bin, open a terminal and use the following command to view the results at once: 

prism ~/path-to/model-file-name.prism ~/path-to/property-file-name.props

Example: If you are currently in the PRISM bin, and the files are downloaded in the Downloads directory for the simulation of a dice case study, the following command should work:

prism ~/Downloads/Simulating_Dice/dice.prism ~/Downloads/Simulating_Dice/Dice-properties.props

For any queries/issues, write to susmoy18@iiserb.ac.in or arpit@iiserb.ac.in
