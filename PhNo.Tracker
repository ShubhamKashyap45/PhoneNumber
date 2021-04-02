import phonenumbers
from Numbers import number  

# To show the country 
from phonenumbers import geocoder
country_no = phonenumbers.parse(number,"CH") # CH is the country history

# To print the country name
print(geocoder.description_for_number(country_no, "en"))

# To show service provider
from phonenumbers import carrier 
service_provider = phonenumbers.parse(number, "RO")
print(carrier.name_for_number(service_provider, "en"))

