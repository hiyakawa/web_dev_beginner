Excel Displayer
==========================
Muyuan Zhang    
12/16/2021    
    
This script is to convert excel files into HTML tables using Python Flask.    
/select is to request the user to upload a valid file with an extension of .xls or .xlsx
and to redirect to /result.    
/result is to display the excel content at the front-end. If an unvalid file is uploaded, 
it will redirect back to /select and require the user to choose another file.
