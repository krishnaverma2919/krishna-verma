#from selenium import webdriver
#from selenium.webdriver.common.keys import Keys
#from selenium.webdriver.common.by import By
#import pandas as pd
#import time
#driver = webdriver.Chrome()
#driver.get("https://www.instahyre.com/python-jobs")
#time.sleep(5)
#x_path_next_page = '//*[@id="job-function-page"]/div[2]/div/div[1]/div[1]/div[21]/li[12]'
#x_path_job_title = '//*[@id="employer-profile-opportunity"]/div[1]/div'
#x_path_location = '//*[@id="employer-profile-opportunity"]/div[2]/span/span'
#x_path_founded = '//*[@id="employer-profile-opportunity"]/div[3]/span[1]/span'
#x_path_employess ='//*[@id="employer-profile-opportunity"]/div[3]/span[3]/span'
#x_path_skill ='//*[@id="employer-profile-opportunity"]/div[5]/ul'
#x_path_discription='//*[@id="employer-profile-opportunity"]/div[4]'
#idx1 = 1
#idx2 = 1
#idx3 = 1
#idx4 = 1
#idx5 = 1
#idx6 = 1
#title_arr = []
#location_arr = []
#founded_year_arr = []
#employees_arr = []
#skills_arr = []
#description_arr = []

#for i in range(5):
   # if idx1!=idx2 or idx2!=idx3 or idx3!=idx4 or idx4!=idx5 or idx5!=idx6:
       # print(i)
       # break
   # elements_job_title = driver.find_elements(by=By.XPATH, value = x_path_job_title)
   # for ele in elements_job_title[::2]:
      #  temp = ele.get_attribute('innerHTML')
       # temp = temp.strip()
       # title_arr.append(temp)
      #  print(f'{idx1}. ', temp)
      #  idx1 +=1
   # print()

   # element_founded= driver.find_elements(by=By.XPATH, value = x_path_founded)
    
    #for ele in element_founded[1::2]:
       # temp = ele.get_attribute('innerHTML')
       # temp = temp.strip()
       # location_arr.append(temp)
       # print(f'{idx2}. ', temp.strip())
       # idx2 +=1
  #  print()
    
   # for ele in element_founded[::2]:
        #temp = ele.get_attribute('innerHTML')
       # temp = temp.strip()
       # founded_year_arr.append(temp)
        #print(f'{idx3}. ', temp)
        #idx3 +=1
   # print()
   # element_employess = driver.find_elements(by=By.XPATH, value = x_path_employess)
    #for ele in element_employess:
        #temp = ele.get_attribute('innerHTML')
        #temp = temp.strip()
        #employees_arr.append(temp)
       # print(f'{idx4}. ', temp)
        idx4 +=1
   # print()
   # element_skill= driver.find_elements(by=By.XPATH, value = x_path_skill) 
   # for ele in element_skill:
        #temp = ele.get_attribute('innerHTML')
       # temp = temp.strip()
        #skills_arr.append(temp)
       # print(f'{idx5}. ', temp)
        #idx5 +=1
   # print()
    #element_discription= driver.find_elements(by=By.XPATH, value = x_path_discription)
    #for ele in element_discription:
        #temp = ele.get_attribute('innerHTML')
       # temp = temp.strip()
       # description_arr.append(temp)
        #print(f'{idx6}. ', temp)
       # idx6 +=1
  #  print()
   # element_next_page = driver.find_element(by=By.XPATH, value = x_path_next_page)
   # element_next_page.click()
   # time.sleep(5)            

#driver.close()

#d = {
   # "Job title": title_arr,
   # "Location": location_arr,
   # "Founded Year": founded_year_arr,
   # "No of Employees": employees_arr,
   # "Skills": skills_arr,
   # "About": description_arr
}

