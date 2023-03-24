This is a python code that utilizes Selenium to automatically fill Kampus Merdeka initial assessment. Honestly the code is something I cobbled up together and might not work for your case, but on paper this should work for all path if:
- The students name from the google sheet matched the one from Kampus Merdeka (mine doesn’t match, so I have to manually change the name in google sheet manually)
- The topic name from the google sheet matched the one from Kampus Merdeka

Note: I only verified 25% of the students, but it looks like the result matches with the one from the google sheet.

# Prerequisite
## Python Library
tested on the latest version
- openpyxl
- Selenium (at least Version 4.x)
- Pandas
## Files
- Selenium Chromedriver for your chrome version (tested on Chrome 111)
- your class google scores and comments, saved as excel file

# Instruction
1. Put those files in the same folder with the jupyter notebook
2. Run the jupyter notebook (it will take around 10-20 minutes)
3. Check if it run without any problem
4. Double check the data
5. profit ???


