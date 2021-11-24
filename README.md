# Date-to-gene-converter
The automatic conversion of genes to dates in Excel can be problematic, as the converted dates are not recognised in pathway databases. This web tool thus serves to convert the old gene names or dates back into the updated gene names as recommended by the HUGO Gene Nomenclature Committee (HGNC). The running instance of the app is deployed at: " .... "

# Instructions for using web tool
Users can upload their .csv or .xlsx file, and ensure that the first column contains the gene names. Checkbox is provided for users to inspect their data. If no data is uploaded, a demo dataset consisting of a restricted list of genes are pre-loaded. Users may use the pre-loaded demo dataset to explore the features and functionalities of the web tool.

If the first column contains the old gene names, they will be updated using the webtool. If the first column contains dates, they will be converted to the updated gene names, with the exception of Mar-01 and Mar-02 as these terms can be mapped to more than one gene.

When there are duplicate Mar-01 values, Mar-01 will be annotated as Mar-01_1st and Mar-01_2nd. Users will have to manually assign the corresponding gene names to the values. If gene description is provided in the dataset, users will just need to match the gene name to the gene description. Same goes for Mar-02 values as well.

# Checking converted dataframes
Users can key in the genes of interest to query if the gene expression data has been updated with the new gene names. 
