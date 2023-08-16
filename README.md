# SCPViz
SCP Viz - A universal vizualization platform for single protein analysis in single cell proteomics data 

Single Cell Proteomics by mass spectrometry is an exciting and emerging field of research that has yet to take a final form. You can use many mass spectrometers and you can use any of the over 1,000 LCMS data analysis platforms to process your data.
The one constant right now is that when you've got hundreds of cells it is very difficult to see what each single protein is doing. And this is where SCP Viz comes in. 

![image](https://github.com/orsburn/SCPViz/assets/39571544/64d380e4-67e5-406a-82be-f00d7941913f)


Box plots with each individual cells and simple t-tests shown. You can graph your single protein as density plots, histograms, violin plots - whatever floats your boat - or the original data points - the last of which is fully interactable, zoomable, and exportable.

![image](https://github.com/orsburn/SCPViz/assets/39571544/d7f1e2de-7659-4333-91d0-71896b0335b2)


Why is it "universal" you have complete control over what columns you want to use within the text data that you upload. 
For example, Proteome Discoverer uses the word "Abundance" and for multiplexed data, you'll get a column header starting with an "Abundance_F...something" so you just use "Abundance_F" (no quotation marks) as your abundance flag. 
SpectroNaut uses PG.Quantity in the header. Use that instead. For FragPipe you have "Intensity" or "MaxLFQ" or "Normalized Intensity" use that text to pull data from the correct columns.
Once loaded, you can go to the columns tab and see what you've loaded.

Using this same functionality you can easily subset single cell populations with interesting phenotypes. Unlike PCA or (most) nonlinear reduction tools where you get pretty pictures, you can always get back to the original data.
For example if you're interested in cells 13, 42, 101, and 616, just add the text "Interesting" into the sample header in your CSV file and add a new condition. Now you can look at each single protein compared between these new subpopulations. 

You can easily check that you're looking at the right cells with the integrated quality control tables on the front end. 

![image](https://github.com/orsburn/SCPViz/assets/39571544/9f8e9a3e-e48e-4aa9-b007-3d6faff35002)


Tutorial videos on install and operation are cominng. Check back here soon. 

This App was created entirely by Ahmed Warshanna as during his training in proteomics and protein informatics as a research specialist in the Orsburn Lab (www.orsburnlab.org).


