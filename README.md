# Adventkalender

#dag1

def masse(filename):
    f=open(filename, "r")
    liste=f.readlines()
    sum_tall=0
    for element in liste:
        x=int(element)
        tall1=(x//3)-2
        sum_tall+=tall1
    return sum_tall

print(masse("mass_fuel.txt"))
