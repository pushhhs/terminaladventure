# Write code below 💖

scene1 = "Good morning! Welcome to Daily Life. Let's begin the day with..."

#Breakfast scene
brk = False
brkscene1 = "You decide to eat breakfast. When you open the fridge, you find that you've run out of milk! What will you do?"
brkqn1 = '''1. Eat your cereal without milk, it's not that serious.
2. This is a national emergency! Go to your nearest grocery store.

Enter number: '''

brksceneb1 = "You sit down to play video games. You choose to play..."
brkqnb1 = '''1. You were stressed the whole week! Spend a nice relaxing time on Animal Crossing.
2. You're feeling adventurous! Play a new horror game.
3. You're itching for a fight! Get on Counter Strike!
             
Enter number:  '''

brksceneb2 = "You rush to the grocery store for milk. Along the way, you..."
brkqnb2 = '''1. Pick up some snacks on the way. You never know!
2. Just go for the milk. You have to stay strong with the diet!

Enter number: '''

#Dog scene
dog = False
dogscene1 = "You leash Fluffy and head out. At the park, you sit down for a short rest when Fluffy breaks free and starts chasing a cat! You..."
dogqn1 = '''1. Fluffy deserves some play time. Let him be and relax for a bit.
2. Fluffy! No! It's dangerous! Chase after him! 
          
Enter number: '''

#Start game
print(scene1)
choicesqn1 = '''1. Breakfast
2. Walk the dog
3. Go back to sleep
             
Enter number: '''
choices1 = int(input(choicesqn1))
while (choices1 < 1 or choices1 > 3):
  print("That's not an option!")
  print(scene1)
  choices1 = int(input(choicesqn1))

if choices1 == 1:
  print(brkscene1)
  brkchoice1 = int(input(brkqn1))
  brk = True
elif choices1 == 2:
  print(dogscene1)
  dogchoice1 = int(input(dogqn1))
  dog = True
else:
  print("It's too early. It's an off day. You need this. You go back to sleep. The end.")

if brk == True:
  while (brkchoice1 < 1 or brkchoice1 > 2):
    print("That's not an option!")
    print(brkscene1)
    brkchoice1 = int(input(brkqn1))

  if brkchoice1 == 1:
    print("That tasted horrible. You couldn't even finish the bowl. Should've gotten the milk!")

  elif brkchoice1 == 2:
    print(brksceneb2) 
    brkchoiceb2 = int(input(brkqnb2))

    while(brkchoiceb2 < 1 or brkchoiceb2 > 2):
      print("That's not an option!")
      print(brksceneb2) 
      brkchoiceb2 = int(input(brkqnb2))

    if brkchoiceb2 == 1:
      print("You stuff your grocery cart and a mountain forms. You end up spending half your salary...")
      print("You silently cry over money lost, but the snacks were tasty though. You fill your belly with cereal, milk, and Doritos.")
    else:
      print("You ignore the temptations with a laser focus on your mission: milk. You grab your favourite brand and rush to the counter without a second look around.")
      print("You return home with nice, cold milk which you pour into your abandoned bowl of cereal. It is perfect, and you accidentally down two bowls.")
  
  print(brksceneb1)
  brkchoiceb1 = int(input(brkqnb1))

  while(brkchoiceb1 < 1 or brkchoiceb1 > 3):
    print("That's not an option!")
    print(brksceneb1)
    brkchoiceb1 = int(input(brkqnb1))

  if brkchoiceb1 == 1:
    print("You bonded with your islanders and decorated the entire island. That was fun! The end.")
  elif brkchoiceb1 == 2:
    print("You screamed at every corner turned, but the adrenaline kept you wanting for more. You end up finishing the game feeling accomplished! The end.")
  else:
    print("You group up with your friends and play multiple matches of Counter Strike. You guys haven't talked in a week, and today you finally had fun together again! The end.")

elif dog == True:
  while (dogchoice1 < 1 or dogchoice1 > 2):
    print(dogscene1)
    dogchoice1 = int(input(dogqn1))

  if dogchoice1 == 1:
    print("An old lady comes back with Fluffy in her arms. She scolds you for letting your dog chase her poor cat! She lectures you for two whole hours.")
  elif dogchoice1 == 2:
    print("You chase Fluffy all the way to the feet of an old lady. She's hugging a cat in fear. You apologize profusely and she forgives you.")

  print("You go home tired, and decide to sit down to play video games. You choose to play...")
  dogchoice2 = int(input(brkqnb1))

  while(dogchoice2 < 1 or dogchoice2 > 3):
    print("You go home tired, and decide to sit down to play video games. You choose to play...")
    dogchoice2 = int(input(brkqnb1))

  if dogchoice2 == 1:
      print("You bonded with your islanders and decorated the entire island. That was fun! The end.")
  elif dogchoice2 == 2:
    print("You screamed at every corner turned, but the adrenaline kept you wanting for more. You end up finishing the game feeling accomplished! The end.")
  else:
    print("You group up with your friends and play multiple matches of Counter Strike. You guys haven't talked in a week, and today you finally had fun together again! The end.")


