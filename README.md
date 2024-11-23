This package analyzes brain blood vessel imaging data. Below are step-by-step instructions:
1. Make sure you download the Quantification.ijm, and add relevant ImageJ packages as described in the file. The Quantification.ijm was developed in this paper: (https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2020.00244/full)
2. Your raw image data can be in TIF format. Store them in the same folder. Change the path at the beginning of the code as needed.
3. Pipeline-Fig.2 extracts the green channel only. Change color channel if your blood vessel data is stored in other channels.
4. Pipeline-Fig.7 extracts both green and cy5 channels, as one of them is immunostained blood vessel results and the other is AAV-infected blood vessel results.
5. The Python code generates violin plots of clustered dots of blood vessel area, blood vessel branches, and nearest distance parameters. We use the linear mixed effects model to perform statistical comparisons of grouped repetitive measurements.   
