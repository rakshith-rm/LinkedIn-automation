# LinkedIn-automation
  A python web automation project for automating LinkedIn with functionalities like liking, connecting to people, personalised 
  messaging, search for people and search for people in a specific entity.

# Requirements
1. Python and Jupyter notebook for the same
2. Selenium web driver (for python)
3. BeautifulSoup (bs4)
4. Chrome driver (.exe)

All the above installations are recommended to be done using pip for your scalability.

# Portability
  Tested and working OK on jupyter notebook for python 64 bit on a windows machine.
  
# How to use
1. The directory should contain 3 files, python script, text file and a .csv file named as Profile_details.csv.
2. Setup your chromedriver.exe application path in the .py file. (use a prefix r"..../chromedriver.exe" if raw)
3. Go on feeding your credentials and input data below asked by the hardcoded text in the text file.
4. You should see your LinkedIn profile open up in a saperated chrome browser window after you press 'RUN' on the .py file in jupyter notebook.

# References
1. https://selenium-python.readthedocs.io/
2. https://www.pythonforbeginners.com/beautifulsoup/beautifulsoup-4-python (It has very meagre usage in our case)
