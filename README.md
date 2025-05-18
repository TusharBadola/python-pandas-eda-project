# Project Summary
This project explores global marathon race data with a focus on USA races held in the year 2020. It invloves cleaning, insightful visualization to understand athlete participation patterns by gender, race distance, seasons and performance.

# Dataset
The data contains over 7 miilion records of marathon event with columns:
  * Year of event                  
  * Event dates                   
  * Event name                    
  * Event distance/length         
  * Event number of finishers      
  * Athlete performance           
  * Athlete club                  
  * Athlete country               
  * Athlete year of birth        
  * Athlete gender                
  * Athlete age category          
  * Athlete average speed         
  * Athlete ID 

# Data Cleaning
  * Filtered data by specific country (USA).
  * Removed unwanted characters like (USA).
  * Calculated athlete ages.
  * Dropped irrevelant and redundant columns.

# Key visualizations
  1. Gender wise participation:
     * Compared participation in 50mi vs 50km across genders.
     * Found that women and men both participated more in 50km than 50mi.
    
  2. Season wise trends:
     * Created a new race_season column after extracting race months.
     * Found that athletes performed fastest in winter, slowest in summer in 50mi races.
     * In 50km races, spring saw fastest performance, while summer had slowest.
     * Autumn recorded the highest participation in 50mi races.
     * Winter had most athlete participation in 50km races.

# Tools used
  * Python
  * Pandas
  * Matplotlib
  * Jupyter Lab
    
