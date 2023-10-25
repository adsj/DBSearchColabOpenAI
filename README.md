# DBSearchColabOpenAI
Natural Language Search to return pdf using OpenAI embedding model.  <br />
Requires OpenAI API key.  
Create a file in GoogleDrive called PDFs.  
Put PDFs in file MyDrive/PDFs.  
Creates a Vector database MyDrive/VecDB.  
On each run, it will check if any new pdfs have been added to the PDFs file, and if so, will add them to the database.  
It does not check if PDFs have been deleted. Currently, if the number of pdfs is small, easiest is to delete the VecDB file and it will rebuild the database from new.  
It returns an excerpt to help you choose which pdf you should choose (but would recommend the user then get the full pdf to ensure they get the full context to answer their query)
