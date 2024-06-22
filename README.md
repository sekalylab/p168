# P168: source code
  
## List of figures:  
[Fig. 2c](#fig-2c)  

### Fig. 2c
![Fig. 2c](figure/fig2c.png)  
Fig. 2c: [R code [MD]](code/)  

## Supplemental material:  
  
code:  
- preprocessing: [R code [MD]](code/20180102_P168.preprocessing.md)  
  
input:  
- non-normalized (raw) intensities: [CSV] (see data release)  
- background intensities: [CSV] (see data release)  
- arrays annotation: [[CSV]](input/p168.GA_Agilent_one_color_matrix.Metadata.csv)  
- probes annotation: [[CSV]](input/p168.featAnnatation.csv)  

output:
- non-normalized EList: [RDA] (see data release)  
- quantile normalized EList: [RDA] (see data release)
- pre-vax substracted EList: [RDA] (see data release)
- MArrayLM list: [[RDA]](output/p168.fits.RData)
