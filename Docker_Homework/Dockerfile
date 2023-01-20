FROM risserlin/bcb420-base-image:winter2023

# Install pheatmap package from CRAN
RUN install2.r \
 -d TRUE \
 -r "https://cran.rstudio.com" \
 pheatmap 

# Install DESeq2 package from Bioconductor
RUN R -e 'BiocManager::install("DESeq2")'

