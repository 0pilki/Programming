city = {
    "Name":"Lübeck",
    "Postal Codes":"23501-23570",
    "State":"Schleiswig-Holstein",
    "Total population":217.061,
    "Total area in km2": 214.13
}

NewCity = city["State"].title()
print(f"Bad Schwartau situated in {NewCity} as well.")

usin = input()
mistake = city.get (f"{usin}", "Dolbaeb? Doesn't exist!") #get "Name", or print "Dolbaeb?".
print(mistake)
if usin 

for key, value in city.items():
    print(f"{key} : {value}")
