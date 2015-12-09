Pipeline to process epigenomics datasets and build classifiers for those datasets. 

The pipeline is managed with a gradle build script (build.gradle).   This build 
script is used in the same way a make file is used.  For example:

	gradle makeAllModelSelectionJobs 

Will execute a task to create the model selection jobs, including executing any 
dependent tasks.  

	gradle tasks 

will give you a list of available tasks. 


To setup environment to pick up the necessary libraries (on hgwdev/ku machines) do:

	source /cluster/bin/jvmtools/jvmtools.sh 