# Search-for-a-Name
CS-104 searching for a name using python

names = []
keepSearching = True
for i in range(0,10):
    i= input("enter name: ")
    names.append(i)
while keepSearching:
    search = input("enter search name: " )
    if search == ('End'):
        break
    if search in names:
        print(search, "was found")
    else:
        print(search, "was not found")
