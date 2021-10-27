# login




username=input("please enter your username:")
password=input("please enter your password:")

#only two usernames are valid admin, anusha

if(username=="admin" or username=="anusha"):
    print("it's a valid username")
    if((username=="admin" and password=="user") or (username=="anusha" and password=="pass")):
        print("logged in successfully")
    else:
        print("sorry password is incorrect")
else:
    print("invalid usernames")
      
