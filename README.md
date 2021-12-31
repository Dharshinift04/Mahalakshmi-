# Mahalakshmi-
Worddic={}
ch='y'
while ch is 'y':
    Print("1.insert new phone no.")
    Print("2.Search Name")
    X=int(input("Enter your choice"))
    if x is 1:
      word=input("enter the phone number:").lower()
      meaning=input("enter the name:").lower()
      insertrecord(worddic,word,meaning)

elif x is 2:
   if len(worddic) > 0:
      word=input("enter the phone number").lower()
      searchmeaning(worddic,word)
    else:
      print("is empty")
  else:
    print("invalid choice")

  ch=input("do you want to continue(v/n)")

print("Thank you")
