# Quiz of Ten Question

print('Welcome to my computer quiz!')
playing = input('Do you want to play? ')
print(playing)

if playing.lower() != 'yes':
    quit()

playing = input("Please enter you name ")
print(playing)

print('Okay! Lets play :) ' + str(playing))
score = 0

##1
answer = input("Which planet has the most moons? ")
if answer.lower() == "saturn":
    print('correct!')
    score += 1
else:
    print('incorrect')
    
##2
answer = input("How many minutes are in a full week? ")
if answer.lower() == "10080":
    print('correct!')
    score += 1
else:
    print('incorrect')
    
##3
answer = input("What company was originally called Cadabra? ")
if answer.lower() == "amazon":
    print('correct!')
    score += 1
else:
    print('incorrect')
    
##4
answer = input("How many ghosts chase Pac-Man at the start of each game? ")
if answer.lower() == "4":
    print('correct!')
    score += 1
else:
    print('incorrect')
    
##5
answer = input("What game studio makes the Red Dead Redemption series? ")
if answer.lower() == "rockstar games":
    print('correct!')
    score += 1
else:
    print('incorrect')
    
##6
answer = input("What country drinks the most coffee per capita? ")
if answer.lower() == "finland":
    print('correct!')
    score += 1
else:
    print('incorrect')
    
##7
answer = input("Which planet in the Milky Way is the hottest? ")
if answer.lower() == "venus":
    print('correct!')
    score += 1
else:
    print('incorrect')
    
##8
answer = input("What is the 4th letter of the Greek alphabet? ")
if answer.lower() == "delta":
    print('correct!')
    score += 1
else:
    print('incorrect')

##9
answer = input("How many bones do we have in an ear? ")
if answer.lower() == "3":
    print('correct!')
    score += 1
else:
    print('incorrect')

##10
answer = input("In what country is the Chernobyl nuclear plant located?  ")
if answer.lower() == "ukraine":
    print('correct!')
    score += 1
else:
    print('incorrect')

print("You got " + str(score) + " questions correct! out of 10")
print("You got " + str((score / 10) * 100) + "%" "out of 100%")



