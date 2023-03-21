# Fetch-Data-From-PMC

## Retrive the PMC articles and get the xml content and bibligraphy informatoin
[`getData.rmd`](getData.rmd) will retrive the PMC articles and get the xml content and bibligraphy informatoin.
It will save the original xml files in PMCoriginal_Feb2021 folder (link). It will save the bibligraphy information (metadata) in pubdata.csv (link). It will annotate the xml files based on sections, figures and tables using SectionTagger_XML.pl (use the one in the directory because it was edited) and save them in PMCtagged_Feb2021 folder. The Methods section for each file is stored in text format in PMC_MethodsTxt_Feb2021 folder. The names of the files without method sections are stored in PMC_NoMetTxt_Feb2021 folder. All the folders can be found [here](https://drive.google.com/drive/folders/1YOZm1PZ4ZAJyAqOd4gZ_a2rPRQlG3g8d?usp=sharing)


## Analyse the PMC articles 
[`analysePubData.rmd`](analysePubData.rmd)  plot the articles  based on year of publications. This is represented in 
[`analysePubData.pdf`](analysePubData.pdf)
