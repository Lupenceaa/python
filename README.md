# remit_batch_statements

* Removed alternative grey background color for rows.
* Made negatived numbers display like ($202.18) with red color.
* One page wide when printing.
* .zip on download from BackOffice, .xlsx files get moved to /gfs
* Run: python remit_batch_statements.py '{"filename" : "phi.zip", "remitID" : "9136"}'


# remit_batch_coke_statement 

* Same as above, all request have been implemented.
* Run: python remit_batch_coke_statement.py '{"filename" : "coke.zip", "remitID" : "11183"}'


# remit_batch_sleepmed_statement

* Generates one .xlsx report, name: remit_batch_sleepmed_statement.xlsx on download
* Makes a copy to /gfs, name: 8045-Watermark-20161107.xlsx
* Same styles and formatting.
* Run: python remit_batch_sleepmed_statement.py '{"filename" : "watermark.xlsx", "remitID" : "8045"}' 
