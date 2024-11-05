# bandpass_sampler
This repo store the bandpasses drawn from the SO LAT  wafer measurements 


We provide a notebook to reproduce the bands. together with bands files in the `QTable` format. 

to open bandpass file: 

```
from astropy.table import QTable
QTable.read('resampled_bpasses_MF1_w0.tbl', format='ascii.ipac')

plt.plot(tab ["bandpass_frequency" ] ,tab ["bandpass_weights" ] ) 
```

