*Used for educational and research purposes only 



How to prepare:: ->

1. Install python of version 3.7.9 or later

2. Clone the git repository onto your system

3. Run "pip install -r requirements.txt" to install the packages for the scrapping

4. Once the installation is finished we are good to go.



How to use:: ->

1. Only keep the queries that you want to search in queries.txt (You can comment out a query by adding a "#" to the start of a query)

2. Once queries are placed perfectly, run the cmd, PowerShell, or other cli on the current directory.

3. Try executing the command "python scrapper_main.py -h" for available options

4. For proper formatting try a command like this -> "python scrapper_main.py --thresh 20 --down_time 10" 
		the threshold number is the number of maximum trying articles from the top options given by google scholar
		the down_time is the number of seconds the browser window will wait to complete the download
				the lower the speed of the internet higher will be the down_time parameter

5. Once the script runs successfully the files will be found in the "deposition" directory placed in a directory each for the query