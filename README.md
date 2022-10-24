# SGAH-datasets.
## Introduction.
This dataset is logged at State Grid Corporation of China.  
The dataset contains four types fault and one normal data.  

## Explanation of fault type.
### Single-phase Grounding Fault.  
Fault phase current increases and fault phase voltage decreases.  
![SGF](/images/SGF.jpg)
### Two-phase Grounding Fault.  
Fault two-phase current increases, the voltage decreases, and the two fault phases have opposite currents.  
![TGF](/images/TPF.jpg)  
### Inter Phase Short-circuit Fault.  
Fault phase current increases, phase voltage increases.  
![TGF](/images/IPSF.jpg)    
### Main Transformer Fault.  
The three-phase current increases, the fault phase voltage is about half of the normal voltage, and the non-fault phase voltage increases.  
![MTF](/images/IPSF.jpg)  
## Document description.  
Different CSV files in the data folder correspond to different kinds of faults.       
      1-Single Phase Ground Fault (SGF)     
      2-Inter Phase Short Circuit Fault (IPSF)     
      3-Two-phase Ground Fault (TGF)      
      4-Main Transformer Fault (MTF)      
      5-Normal data (Normal)    
Each CSV file contains multiple fault data of the same type.  
Each fault data contains 100 sampling points of three-phase voltage and current data.  
Each fault data contains three phase current data (first three columns) and three phase voltage data (last three columns).   

## Reference
If you use the codes or the datasets, please cite the following papers:   
```  
@unknown{unknown,  
author = {Li, Qiyue and Deng, Yuxing and Liu, Xin and Sun, Wei and Li, Weitao and Li, Jie and Liu, Zhi},  
year = {2022},  
month = {05},  
pages = {},  
title = {Autonomous Smart Grid Fault Detection},  
doi = {10.48550/arXiv.2206.14150}  
}  

@article{li2022resource,  
title={Resource Orchestration of Cloud-edge based Smart Grid Fault Detection},  
author={Li, Jie and Deng, Yuxing and Sun, Wei and Li, Weitao and Li, Ruidong and Li, Qiyue and Liu, Zhi},  
journal={ACM Transactions on Sensor Networks (TOSN)},  
year={2022},  
publisher={ACM New York, NY}  
}    
```  
## Copyright   
See [LICENSE](LICENSE) for details.
