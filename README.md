# Glasses-Shop

This time job is to scrape all the available glasses from this website 

'https://www.glassesshop.com/bestsellers'.

We're interested in getting the 'product url', 'product image link', 'product name' and the 'product price'.

Please note, at the bottom we do have the pagination so make sure to handle that too.

Finally, make sure to generate a dataset from all the scraped glasses, you can either generate a JSON file or a XML file.

# I attached the sample of the output where you find the result.

# Make sure you don't confuse on the name of the project and Spider it's really annoying.

I am sharing with you a step by step guide how to scrap the website.

First create virtual Environment
Go to Anaconda Navigator and then environment then create new environment.
after creating environment install 
## ipython package
## then scrapy shell
  
Now creating new Project

## mkdir projects
## cd projects
## scrapy startprojects eyes
## now copy the website link that are mentioned above

## cd eyes
## scrapy genspider eyes website link
(:: remove end in slash & remove http://)
(:: All above command can be post in your virtual environment terminal)

Now go the glasses.py file to write the command in Virtual studio code to execute the command 

Now i am going to tell you how to create a dataseet to get the data in cvs, json, and xml file.

In Virtual Studio go the view panel then select terminal

# conda activate name of your environment workspace
# scrapy crawl eyes -o glasses_dataset.json

Get the dataset in csv 

# conda activate name of your environment workspace
# scrapy crawl eyes -o glasses_dataset.csv

Get the dataset in xml

# conda activate name of your environment workspace 
# scrapy crawl crawl -o glasses_dataset.xml


Now Do above all task if any problem occurs let me know i will help you. Happy Scraping!!!!
