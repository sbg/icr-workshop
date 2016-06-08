# Visualizing MAF file from the TCGA data

## Objectives:

- Select MAF files from the Pancreatic Adenocarcinoma
- Use MafTools to visualize the MAF file

All this will be done using the [Cancer Genomics Cloud](https://cgc.sbgenomics.com/) (CGC for short.)

# Selecting the file via the Data Browser

## Starting from Case
![Starting from Case](https://raw.githubusercontent.com/sbg/icr-workshop/master/img/CGC-case-selection-step1.png)

## Selecting Diagnosis
![Selecting Diagnosis](https://raw.githubusercontent.com/sbg/icr-workshop/master/img/CGC-hasDiagnosis-step2.png)

## Selecting Pancreatic Adenocarcinoma
![Selecting Pancreatic Adenocarcinoma](https://raw.githubusercontent.com/sbg/icr-workshop/master/img/CGC-diagnosis-filter-step3.png)

## Selecting Files
![Selecting Files](https://raw.githubusercontent.com/sbg/icr-workshop/master/img/CGC-hasFile-step4.png)

## Selecting AccessLevel Node
![Selecting AccessLevel Node](https://raw.githubusercontent.com/sbg/icr-workshop/master/img/CGC-hasAccessLevel-step5.png)

## Selecting Open Files only
![Selecting Open Files only](https://raw.githubusercontent.com/sbg/icr-workshop/master/img/CGC-hasAccessLevelFilter-step6.png)

## Selecting Data Format Node
![Selecting Data Format Node](https://raw.githubusercontent.com/sbg/icr-workshop/master/img/CGC-hasDataFormat-step7.png)

## Selecting only MAF files
![Selecting only MAF files](https://raw.githubusercontent.com/sbg/icr-workshop/master/img/CGC-dataFormatFilter-step8.png)

## How the whole query looks like
![How the whole query looks like](https://raw.githubusercontent.com/sbg/icr-workshop/master/img/CGC-queryCompleted.final.png)


# Import the CWL description of the tool

To import the CWL on your project, Go on the `Apps` and click on `add new tool`.
Then click on Import Json, and import from URL: https://raw.githubusercontent.com/sbg/maftools/cwl-desciption/maftools.cwl.json


![Import Json](https://raw.githubusercontent.com/sbg/icr-workshop/master/img/CGC-editor-import.png)

# Plots produced by the visualizeMaf application

After the application is launched, you can expect two main outputs:

- [SummaryPlot](https://github.com/sbg/icr-workshop/blob/master/img/example_summaryPlot.pdf)
- [OncoPlot and TiTv](https://github.com/sbg/icr-workshop/blob/master/img/example_oncoplot_and_titv.pdf)


