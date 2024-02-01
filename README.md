# metagenomics_qiime2
This is a practice work flow in google colab that will give you a general idea on how to use qiime2 using fasta files.

Please remember, this is a work flow showing how to use qiime2 using pre-processed fasta files, meaning the files have been demultiplexed, primers have been trimmed, and barcode sequences have been trimmed. Qiime2 is often used to work on fastq sequencing files, but for this class we will mostly work on pre processed fasta files. 

Also remember, this is google colab, so it is basically a python notebook that runs through a virtual machine. This means that it uses the virtual machine operating system (linux), not your host opperating system (ex: macOS or Windows). This way, we are all using the same opperating system, and we can all be on the same page during the work through. However, there are somethings to note since we are using google colab. 

THINGS TO KEEP IN MIND
1). Google colab is a python notebook, however, we are not writing code, we are doing command line work. Because we aren't in a normal terminal, we have to use syntax that we wouldn't normally use if we were in our terminal on Mac or Windows such as % and !. We must add those before certain commands to let the machine know we want to run a line as if it were in the terminal, not as python script. For example:
                      change directory in google colab = %cd directory_name
                      Change directory in MacOS/Unix terminal = cd directory_name

2). Since Google Colab is run on a virtual machine, you are competing for resources. This mean it runs kinda slow sometimes and also files will get deleted sometimes. Because of this, I would try to do this pipeline in one go, or download your output files locally to your computer as you go. If you are idle long enough, your files will be deleted. 

3). Qiime runs a little differently on here than if you were to download it on your local computer. When working on your computer, you need to be a qiime2 environment. 

4) DO NOT USE THE SAME CODE IN THIS RESPITORY TO DOWNLOAD QIIME2 TO YOUR LOCAL DEVICE!!!!!!!!!!!!!! IF you want to download qiime2 locally follow the installation instructions on the qiime2 website.  
