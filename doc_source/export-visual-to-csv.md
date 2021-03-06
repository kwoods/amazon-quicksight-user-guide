# Exporting Data from an Amazon QuickSight Visual to a CSV File<a name="export-visual-to-csv"></a>

Use the following procedure to export data from a visual to a file with the comma\-separated value \(CSV\) format\.

1. Choose or create an analysis or dashboard that contains one or more visuals\. 

1. Choose the visual you want to export\. 

1.  Choose the on\-visual menu, at the upper right of the visual\. Then choose **Export to CSV**\.   
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/quicksight/latest/user/images/export-visual-to-csv.png)

1.  Depending on your browser settings, one of the following happens: 
   +  The file automatically goes to your default **Download** location\. 
   +  A dialog box appears so you can choose a file name and location\. 
   +  A dialog box appears so you can choose to open the file with the default software or to save the file\. If you choose to save, you can choose a file name and location\. 

   By default, the CSV file name is the name of your analysis or dashboard\. To make the file name unique, it has a sequential timestamp \(a Unix epoch data type\) or a date in the format `yyyy-MM-dd_THH_mm_ss.SSSZ`\. You can choose rename the downloaded file, for example to include the name of the visual\. 

   The CSV contains the fields and filtered data appearing in the visual\. 

1. To export data from additional visuals in the same analysis or dashboard, repeat this process for each visual\. 

**Tip**  
If you have difficulty getting the download to start, try a different browser\.