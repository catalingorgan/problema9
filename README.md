import datetime

secunde = input("Dati numarul de secunde: ")
d = datetime.datetime(2020, 10, 20, 00, 00, 00)

sDate = datetime.datetime.fromtimestamp(int(secunde))
#datetime.datetime.fromtimestamp(your_timestamp / 1e3)
print(sDate)
