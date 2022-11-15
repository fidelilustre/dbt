1. install homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
2. install virutalenv
brew install virtualenv
3. create folder
4. create virtual environment in the folder
virtualenv venv
5. activate virtual environment
. venv/bin/activate
6. install snowflake dbt
pip install dbt-snowflake
7. create project
dbt init

Random terminal commands 
- open profiles.yml
open /Users/computer_user/.dbt
- activate virtual environment
. venv/bin/activate
- single model run
dbt run --select folder_name
- publish csv
dbt seed
check source freshness. warnings are set in sources.yml
dbt source freshness