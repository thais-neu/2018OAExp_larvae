# Test i5 primer using traditional library prep 

**Overview** Used [KAPA hyperprep library kit](https://rochesequencingstore.com/wp-content/uploads/2017/10/KAPA-HyperPlus-Kit_KR1145-%E2%80%93-v5.19.pdf), adapters (from Saras Stock), i7 primers (Sara's stock), and i5 primers (my stock used previous for BS conversion).


Performed half volume Kapa hyperprep library prep with two samples.

### DNA 

Used 150 bp unmethylated lambda DNA (327 ng per sample), sheared using sonicator.

### END Repair and A-tailing

**Master Mix** 
| Reagent | Vol |
|:-------:|:---:|
| ER & ET Buffer | 3.5 uL |
| ER & ET Enzyme | 1.5 uL |

**Reaction**  
25 uL sample + 5 uL MM = 30 uL 

Thermocycler : 30 min @ 20C then 30 min @ 65C

### Adapter Ligation

Master Mix
| Reagent | Vol |
|:-------:|:---:|
| Ligation Buffer | 15 uL |
| Ligation Enzyme | 5 uL |
| H20 | 2.5 uL |

**Reaction**  
30 uL sample + 22.5 uL MM + 2.5 uL adapter = 55 uL 

Thermocycler : 30 min @ RT 

**Notes**  
* Used Y adapter 10 from Sara's stock.  

### First Cleanup

**Prep**
* Created 80% EtOH  
* 0.8X  Beadwash
* 2 x 200uL EtOH wash
* Eluted using TRIS HCL 20 uL

**Initial Reaction**
50 uL samples + 44 uL beads

### STOP

After clean-up left sample overnight in fridge.

### PCR

**Notes**
* i5 L1 my stock and L2 Sara's stock
* i7 (L3) Sara's stock

**Master Mix**
| Reagent | Vol |
|:-------:|:---:|
| Hot Start| 12.5 uL |
| i5 primer (L1 mine or L2 Sara's stock) | 1.25 uL |

**Reaction**
10 uL sample + 1.25 uL i7 (L3) + 13.75 uL MM == 25 uL 
* Sample 1 used my i5 L1 stock
* Sample 2 used i5 L2 Sara's stock

### Second Cleanup

**Prep**
* Created 80% EtOH  
* 0.8X  Beadwash
* 2 x 200uL EtOH wash
* Eluted using TRIS HCL 20 uL

**Initial Reaction**
25 uL samples + 20 uL beads

### Quantification

Used Qubit high sensitivity (HS) kit

| Sample | Conc. (ng/ul) |
|:-------:|:---:|
| Sample 1 ( my i5 primer) | TOO LOW |
| Sample 2 ( Sara's i5 primer) | TO LOW |
| Starting Sheared Sample | 33.3 |
| End repair A-tail product (Sample 1) | 8.01 |
| Post first BW prodduct (Sample 1) | 1.92 |

## Discussion
The library prep failed. It seems like during either the final bead clean-up or amplification steps sample was lost the remaining sample. 
