# DSCapstone2
### SpringBoard DS Career Track - Capstone 2

#### Basic File Structure within DSCapstone2:

data/raw/ 
<br>--> for raw data from:
<br>--> https://collegescorecard.ed.gov/data/
<br>--> Json files downloaded from https://api.data.gov.
<br>--> Design for queries: https://www.postman.com/louis-fortunato/workspace/8fb65eb5-3826-4258-92f7-fd1474949256/overview
<br>--> API key for data.gov College Scorecard is available at https://api.data.gov/signup

data/interim/ 
<br>--> for clean data to be preprocessed and preprocessed data

data/processed/ 
<br>--> for final cononical data set(s) for modeling

references/ 
<br>--> for data documentation files
<br>--> The CollegeScorecardDataDictionary.xlsx file found in this folder provides deeper information about how variables are coded, and provides insight into why certain variables were dropped, or how the imputation methods for certain missing values was selected. See sheet named Institution_Data_Dictionary or visit https://collegescorecard.ed.gov/assets/InstitutionDataDocumentation.pdf

notebooks/ 
<br>--> for jupyter notebooks

models/ 
<br>--> models
reports/ 
<br>--> reports including project proposal (to be added when finalized)

#### Referenced:

Cookiecutter Data Science Model used for reference:
<br>--> https://drivendata.github.io/cookiecutter-data-science/
<br>College Scorecard:
<br>--> https://collegescorecard.ed.gov/data/
<br>Postman API
<br>--> https://web.postman.co/

#### See in references/

Certain modifications made to code missing values
<br>--> endowment_begin = 0 (school not receiving endowment)
<br>--> endowment_end = 0 (school not receiving endowment)
<br>--> ownership_peps = 0 (unknown)
<br>--> school.carnegie_undergrad = -1 (unclassified NOT graduate only)
<br>--> accreditor_code = 'NONE' (not accredited)
<br>--> locale = 1 (unknown)


