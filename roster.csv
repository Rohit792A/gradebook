import csv

header = ['s.no', 'Name', 'Roll no', 'CT 1 Marks','CT2 Marks']
data = [
    ['1', 'Amit sharma', '30001132', '32','54'],
    ['2', 'Srikant Naidu', '30001133', '21','23'],
    ['3', 'Aditi Thakur', '30001134', '12','35'],
    ['4', 'Virat Singh', '30001135', '24','45'],
    ['5', 'Arya Mishra', '30001136', '36','38'],
]

with open('countries.csv', 'w', encoding='UTF8', newline='') as f:
    writer = csv.writer(f)

    # write the header
    writer.writerow(header)

    # write multiple rows
    writer.writerows(data)
