# DBSearchColabOpenAI
Natural Language Search to return pdf using OpenAI embedding model
Requires OpenAI API key
Put PDFs in file MyDrive/PDFs
Creates a Vector database MyDrive/VecDB
On each run, it will check if any new pdfs have been added to the PDFs file, and if so, will add them to the database.
It does not check if PDFs have been deleted. Currently, if the number of pdfs is small, easiest is to delete the VecDB file and it will rebuild the database from new
