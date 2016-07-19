# Visualizing MAF file from the TCGA data

## Objectives:

- Select MAF files from the Pancreatic Adenocarcinoma
- Use MafTools to visualize the MAF file

All this will be done using the [Cancer Genomics Cloud](https://cgc.sbgenomics.com/) (CGC for short.)


# Overview video
![Overview video](img/2016-07-19-CGC-ICR-Workshop-screencast.gif)

# Step-by-step instructions

## Selecting a case
![Starting from Case](img/CGC-Case-selected-step2.png)

## Selecting Disease
![Selecting Diagnosis](img/CGC-hasDisease-step3.png)

## Selecting Pancreatic Adenocarcinoma
![Selecting Pancreatic Adenocarcinoma](img/CGC-findDisease-step4.png)

## Selecting open access files
![Selecting Files](img/CGC-hasAccess-step5.png)

## Selecting data format
![Selecting data format](img/CGC-hasDataFormat-step6.png)

## The final query results
![How the whole query looks like](img/CGC-finalQuery-step7.png)


# Import the CWL description of the tool

To import the CWL on your project, Go on the `Apps` and click on `add new tool`.
Then click on Import Json, and import from URL: https://raw.githubusercontent.com/sbg/maftools/cwl-desciption/maftools.cwl.json


![Import Json](https://raw.githubusercontent.com/sbg/icr-workshop/master/img/CGC-editor-import.png)

# Plots produced by the visualizeMaf application

After the application is launched, you can expect two main outputs:

- [SummaryPlot](https://github.com/sbg/icr-workshop/blob/master/img/example_summaryPlot.pdf)
- [OncoPlot and TiTv](https://github.com/sbg/icr-workshop/blob/master/img/example_oncoplot_and_titv.pdf)


