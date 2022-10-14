# def myFunc(e): 
    return e['year'] 
cars = [ 
{'car':'Volvo', 'year': 2015}, 
{'car': 'Toyota', 'year': 2020}, 
{'car': 'BMW', 'year': 2019}, 
{'car': 'VW', 'year': 2021} 
{'car': 'Hyundai', 'year': 2021}
] 

cars.sort(key=myFunc)
print(cars)
#pēc katras rindas pievieno skaidrojumu, ko nozīmē rinda kodā
#kodā pievieno informācīju par Hyundai, ražotu 2021. gada 
#koda izpildes rezultātu iekopē atbilžulogā
