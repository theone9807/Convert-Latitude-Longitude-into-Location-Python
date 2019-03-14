# Convert-Latitude-Longitude-into-Location-Python

#we will use reverse geocoder module to perform this task of conversionimport reverse_geocoder as rg #pprint is used for the pretty printing formate( As dictionary)
import pprint 
  
def reverseGeocode(coordinates):     """This function will do our job of conversion"""
    result = rg.search(coordinates) 
      
    # result is a list containing ordered dictionary. 
    return result
    
    
 #testreverseGeocode((19.246, 145.616))[0]['cc']    
 #here [0]['cc'] used to print country name , You can avoide this #output obtained'MP'Also read: FEATURE-ENGINEERING-EARTHQUAKE-DATASET
