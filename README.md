======================================================================

||---->> Instructions for Hands On - PDF <<----||

======================================================================

The "Hands On" is a Python script developed in the Google Colab environment, which implements functions for reading and analyzing data from PDF format files, such as ".CSV" files. The script processes the data extracted from these files to generate statistical charts based on the tables. Before running it, some preliminary checks need to be done. Therefore, follow the procedure described below.

[ 1 ] - Check if the table was created correctly.

	[1.1] - Verify if the table was saved in table format (.csv).
	
	[1.2] - Verify if two tables were created, one for the content (table_path.csv).
	
	[1.3] - Verify if the tables were assembled correctly based on the example below:

		"| tags                                                           |"
		
		 | information you want to search for (words, phrases or symbols) |
		 
[ 2 ] - After downloading the "Hands On - PDF" file from GitHub, do the following:

	[2.1] - Locate the file on your computer, usually in the "Downloads" folder.
	
	[2.2] - Right-click on the "Hands On - PDF.zip" file and click "Extract Here".
	
	[2.3] - Locate the table created for use in the script and the ".pdf" file you want to mine.
	
	[2.4] - While holding the "CTRL" key, select both the table and the ".pdf" file.
	
	[2.5] - With both files selected, use the command "CTRL + X" to move both at once.
	
	[2.6] - After using the command to move the files, open the folder that was extracted earlier, the "Hands On - PDF" folder.
	
	[2.7] - With the folder open, paste both files into the folder using the command "CTRL + V".
	

[ 3 ] - With all necessary files ready for upload to Google Drive, do the following:

	[3.1] - Open the browser and log in with the desired email.
	
	[3.2] - Once logged in, open Google Drive.
	
	[3.3] - On the Google Drive page, click on "+ NEW".
	
	[3.4] - After a small window opens in the corner of the page, click on "Folder Upload".
	
	[3.5] - Locate the "Hands On - PDF" folder on your computer and click "Upload".
	

[ 4 ] - With the folder uploaded and the Google Drive page open, do the following:

	[4.1] - Open the "Hands On - PDF" folder in Google Drive.
	
	[4.2] - With the folder open, click on the "Hands On - PDF.ipynb" file to open it in the browser via Google Colab.
	
	[4.3] - With the file open, look for step 3 titled "Step 1: Import, read, and analyze training and validation data files, with file paths specified for each dataset".
	
	[4.4] - Once you find this step, look for the phrases highlighted in red to change the file path addresses.
	
		"pdf_path = ('/content/drive/My Drive/Hands/livro.pdf')"
	
		"table_path = ('/content/drive/My Drive/Hands/livro.csv')"
	
	[4.5] - When you find these lines, simply delete the end of the path (e.g., ".../Hands/livro.pdf") and replace it with ".../Hands On-PDF/(file_name)".
	
	[4.6] - Once the paths are updated, use the "CTRL + 9" command to execute the entire script.
