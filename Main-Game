def yes_or_no(string):
    new_string=input(string+ ' ')
    if ((new_string == 'yes') or (new_string == 'Yes') or \
        (new_string == 'YES') or (new_string == 'y') or (new_string == 'Y')):
        return (True)
    elif ((new_string == 'no') or (new_string == 'No') or \
          (new_string == 'No') or (new_string == 'n') or (new_string == 'N')):
         return(False)
    else:
         print('''Your answer is not recognized as "yes" \
or "no", but I will assume that you intended to \
answer "no".''')
         return('?')
      
def survival_game():
    intro="You are stranded on a deserted island."
    intro_2 = "The only way to escape is by finding the portal to teleport back to NYU."
    start="Do you wish to proceed?"
    lake="Would you like to start at the lake?"
    pocket="In your pocket is a pouch with a dagger, cheese, and a stick"
    lake_1="Will you use the dagger?"
    lake_2="Will you use the cheese?"
    frog="A frog is sitting on a box. Make him move. You can use the dagger or cheese."
    frog_g="Good job! The frog loves cheese, he thanks you and hops off."
    frog_b="Wrong! This frog has unpierceable skin. He eats you."
    box='''In the box is a message: "Go to the land where the tall trees grow."'''
    forest="Would you like to go to the forest?"
    forest_1="Will you use the dagger?"
    forest_2="Will you use the stick?"
    wolf="A wolf is guarding a door. Make him move. You can use the dagger or stick."
    wolf_g="The wolf admires your bravery. He  opens the door to the portal."
    wolf_b="It's a wolf, not a dog. He's offended and eats you."
    desert="Would you like to go to the desert?"
    desert_b="You are wiped out by a sandstorm."
    sea="Would you like to explore the sea?"
    sea_b="You are attacked by the kraken."
    game_o="GAME OVER"
    game_d="YOU  WIN!! Time to go back to Washington Square Park!"
    print(intro)
    print(intro_2)
    while True:
        if not yes_or_no(start):
            print("Very well. You are stranded for life.",game_o)
            break
        else: 
            print(pocket)
            if yes_or_no(lake):
                print(frog)
                if yes_or_no(lake_1):
                    print(frog_b,game_o)
                    break
                else:
                    if yes_or_no(lake_2):
                        print(frog_g)
                        print(box)
                        if yes_or_no(forest):
                            print(wolf)
                            if yes_or_no(forest_1):
                                print(wolf_g,game_d)
                                break
                            else:
                                if yes_or_no(forest_2):
                                    print(wolf_b,game_o)
                                    break
                                else:
                                    continue
                        else:
                            if yes_or_no(desert):
                                print(desert_b,game_o)
                                break
                            else:
                                continue
                    else:
                        continue
            else: 
                if yes_or_no(sea):
                    print(sea_b,game_o)
                    break
                else:
                    continue

