# REGDOCS_Tolls_Group1_FeaturedInformation
Documents in Tolls Feature Information for CER regulate Group 1 companies.

Code generates CSV file with all documents in CER REGDOCS for Tolls Group 1 Featured Information and their attributes.

REGDOCS links: 
OilGroup1Tolls_url = 'https://apps.cer-rec.gc.ca/REGDOCS/Item/LoadResult/92835'
GasGroup1Tolls_url = 'https://apps.cer-rec.gc.ca/REGDOCS/Item/LoadResult/92833'

Receipts excluded by default. Updated 13 February 2023.

CSV file includes 14 document attributes:

['folder_name_url', 'document_name', 'document_download_link',
       'document_date', 'doc_submitter', 'folder_name',
       'featured_information_type_url', 'featured_information_type', 'f1_url',
       'company_name', 'company_name_url', 'commodity', 'year_url', 'year']
       
High level overview of this dataset available on this dashboard saved on Tableau Public:

'get requests' are pooled to decrease run time.
