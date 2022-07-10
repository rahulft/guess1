# guess1
#my codes are copied
Secretword="rahul"
guess=""
guess_limit=0
guess_count=2
out_of_guesses=False
while guess!=Secretword and not(out_of_guesses):
    if  guess_count<guess_limit:
      guess=input("enter the secret word :")
      guess_count+=1
    else:
      out_of_guesses=True
      
      
if out_of_guesses:
    print("you fail")
else:

 print ("you guess correct")
