# yMap

yMap is a python based fast and robust automated method to map large yeast variants data to 
            
            - proteins post-translational modifications 
                            
            - proteins domains, 
                            
            - proteins-nucleotide binding domains, 
                        
            - proteins structural regions, 
                
            - proteins active and binding sites 
                
            - proteins networks visualisation. 


The post-translational modifications in yMap are collected from different repositories like UniProt and sources 
with annotated PTMs like PTMcode 2.0 and PTMfunc, for more details, see README file.

In a user friendly way, it generates a "final-report" file to report all the non-synonymous 
mutations that overlaps or falls inside the above mentioned proteins functional regions.
The final-report is complemented with two other files; enrichment and visualsation id file. 


#Contents

            scripts: ymap.py

            README: Introduction and details of functions/methods and data with a Manual - with details of how to run yMap 

            Supported data: data/PTMcode + PTMfunc

            Example data: examples mutations files




#Dependencies 
   
    yMap depends on:
            
            python 2.7.x
            
            python 3.5.x
            
            Orange bioinformatics (http://pythonhosted.org/Orange-Bioinformatics/#installation)
            
#Installation

            pip install ymap


#Usage
    
            cd /path/to/ymap
            
            $ python ymap.py --data data        #download all the data need for proper execution of ymap
            
            $ python ymap.py --ymap_proteins ymap_proteins  #if starting file contains the mutations at proteins level 
                                                            (SEE example data).
            
            $ python ymap.py --ymap_genes ymap_genes        #if starting file contains the mutations at chromosomes leve with genetic                                                    coordinates (SEE example data).
            
            $ python ymap.py --web web                      # generates the html based visualization of mutated proteins on BioGrid db.
        
        
#Documentation     
    
            For complete instructions see README file

    
#Troubleshoots 

            To learn about the types of problems and how to solve them; see README file

# Contributors

            http://www.biw.kuleuven.be/CSB/
            
This work in supported by KU Leuven research fund. 