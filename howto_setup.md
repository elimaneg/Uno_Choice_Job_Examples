1. **Install** the uno-choice Jenkins plugin
2. **Copy** the USE_CASE01_UNOCHOICE folder in the JENKINS_HOME\jobs folder
3. **Copy** the contents of the userContent folder in the JENKINS_HOME\userContent folder
4. **Reload** the Jenkins configuration to load the new USE_CASE01_UNOCHOICE project
5. Build the project with parameters

You should see two choice controls and four uno-choice controls. 

The four uno-choice controls should display four different set of choices simulating the 2x2 combinations of the two choice controls. 
Once **cascading updates** have been implemented for the uno-choice control we should be able to have a single uno-choice control generating all of the four choice options with combinations of the PARAM01_METADATA and PARAM02_TYPE build parameters.
