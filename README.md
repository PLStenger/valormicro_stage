# valormicro_nc
Characterization of marine microbial resources for analysis and enhancement of New Caledonia's natural heritage - Project from Drs **Anton Véronique** (CNRS/IRD Nouméa - New Caledonia)

### Installing pipeline :

First, open your terminal. Then, run these two command lines :

    cd -place_in_your_local_computer
    git clone https://github.com/PLStenger/valormicro_stage.git

### Update the pipeline in local by :

    git pull

### Running the script with :

    time nohup bash pipeline_complete.sh &> pipeline_complete.out
    time nohup bash 00_quality_and_cleanning_steps.sh &> 00_quality_and_cleanning_steps.out
   
