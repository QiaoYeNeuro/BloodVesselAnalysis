This package analyzes brain blood vessel imaging data. Below are step-by-step instructions:
1. Make sure you download the Quantification.ijm (https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2020.00244/full), and add relevant ImageJ packages as described in the file.
2. Your raw image data can be in TIF format. Store them in the same folder. Change the path at the beginning of the code as needed.
3. Pipeline-Fig.2 extracts the green channel only. Change if needed.
4. Pipeline-Fig.7 extracts both green and cy5 channels, as one of them is immunostained results and the other is AAV results.
5. The Python code generates violin plots of clustered dots of blood vessel area, blood vessel branch, and nearest distance parameters. We used the linear mixed effects model to perform statistical comparisons of grouped repetitive measurements.   
