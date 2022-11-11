# quiz
Miguel = 0
Robby = 0
Johnny = 0
Daniel = 0
Tory = 0
Sam = 0


choice = input("what is your favoirte color? (g)reen, (b)lue, (p)urple, blac(k), (r)ed, (w)hite")
if choice == 'g':
  Tory=Tory+1 
elif choice == 'b':
    Robby +=1
elif choice == 'p':
    Sam +=1
elif choice == 'k':
    Johnny +=1
elif choice == 'r':
    Miguel +=1
elif choice == 'w':
    Daniel +=1 
else:
    print ("sorry not an option bri ish accent")
  
choice = input("What kind of friend would you like? (l)oyal, (h)umor, (e)mpathy, (c)reative, (a)dventurous, confiden(t)")
if choice == 'a':
    Tory=Tory+1 
elif choice == 't':
    Robby +=1
elif choice == 'c':
    Sam +=1
elif choice == 'h':
    Johnny +=1
elif choice == 'l':
    Miguel +=1
elif choice == 'e':
    Daniel +=1 
else:
    print ("sorry not an option aussie accent")
  
choice = input("Choice your favorite 80's movie! (b)ack to the future, (g)oonies, (f)erris buller's day off, beetle(j)uice, (s)carface, (d)irty dancing)")
if choice == 'f':
    Tory=Tory+1 
elif choice == 'b':
    Robby +=1
elif choice == 'd':
    Sam +=1
elif choice == 's':
    Johnny +=1
elif choice == 'j':
    Miguel +=1
elif choice == 'g':
    Daniel +=1 
else:
    print ("sorry not an option countray accent")
  
choice = input("How will you spend your saturday night? (g)oing to mexico, (d)rink coor's beer at home by yourself, (r)eading a book in your house, (l)ooking for a job, (j)uvie, (n)ot being the center of attention")
if choice == 'l':
    Tory=Tory+1 
elif choice == 'j':
    Robby +=1
elif choice == 'r':
    Sam +=1
elif choice == 'd':
    Johnny +=1
elif choice == 'g':
    Miguel +=1
elif choice == 'n':
    Daniel +=1 
else:
    print ("sorry not an option african accent")

if Tory >= Robby and Tory >= Sam and Tory >= Johnny and Tory >= Miguel and Tory >= Daniel:
  print("you are Tory")
elif Robby >= Sam and Robby >= Johnny and Robby >= Miguel and Robby >= Daniel:
  print("your Robby!")
elif Sam >= Johnny and Sam >= Miguel and Sam >= Daniel:
  print("you are Sam :(")
elif Johnny >= Miguel and Johnny >= Daniel:
  print("YOUR JOHNNY!!!!!")
elif Miguel >= Daniel:
  print ("eres Miguel")
else:
  print("your Daniel")
