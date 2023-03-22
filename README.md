# pythonProject27



#virus!!! (can be endless)

x=0
while x <= 1000:
    f = open("welcome.txt", "w")
    print(f.write("i am here!!!")*10000)
    f = open("welcome.txt", "r")
    print(f.read())
    x += 1

    f.close()
