############################
#README
#==========================
#Minority Action Project
#Divya Veerapaneni, Arundeep Singh, Steve Kim
#==========================
############################
#Objective1_data.ipynb
#———————————————
#Used to parse through businessesinboston2018 file and create a
#list of locations (parsed.csv) based on longitude and latitude 
#as well as property type and property value using Google's API
#NOTE: can only parse through 1250 data points at a time per 24 
#hours due to restrictions set by Google.
#dependencies: geopy package, businessesinboston2018.csv
#
############################
#Objective1_graphs.ipynb
#———————————————
#Creates graphs and runs k-means clustering algorithms based on
#on property type and property value using the list created in
#Objective1_data.ipynb
#dependencies: parsed.csv
#
############################
#Objective2.ipynb
#———————————————
#Creates demographic graphs using 2015 KIEA data
#NOTE: information on codes in kieacodebook_v7.xlsx
#dependencies: kieadata15.csv
#
############################
#Objective3.ipynb
#———————————————
#Creates graphs to measure change in entrepreneurial growth
#throughout full KIEA dataset
#dependencies: kieadataset*.csv
#
############################
#Objective4.ipynb
#———————————————
#Runs linear regressions, creates linear classification models,
#and creates graphs using full KIEA dataset
#dependencies: kieadataset*.csv
#
############################