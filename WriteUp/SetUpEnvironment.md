# How to set up Environment


Note: If your environment does not contain venv run  
`pip install venv`


`python3 -m venv newenv`   
`source newenv/bin/activate`  
`pip install -r requirements.txt`



> Download Data with Kaggle API  
> 1. In your home directory make a file called `.kaggle`
> 2. Go to your Kaggle Account page and generate a new API Key
> 3. Save the `kaggle.json` file in the `~/.kaggle/` folder
> 4. Open your terminal and change directory to `csv_folder/` of this project 
> 5. Download data by running: `kaggle competitions download -c competitive-data-science-predict-future-sales`
> 6. Unzip the file you just retrieved with: `unzip competitive-data-science-predict-future-sales.zip`
> 7. Delete the zip file: `rm competitive-data-science-predict-future-sales.zip`


