print("""___________________________________________________________________
 / \-----     ---------  -----------     -------------- ------    ----\
 \_/__________________________________________________________________/
 |~ ~~ ~~~ ~ ~ ~~~ ~ _____.----------._ ~~~  ~~~~ ~~   ~~  ~~~~~ ~~~~|
 |  _   ~~ ~~ __,---'_       "         `. ~~~ _,--.  ~~~~ __,---.  ~~|
 | | \___ ~~ /      ( )   "          "   `-.,' (') \~~ ~ (  / _\ \~~ |
 |  \    \__/_   __(( _)_      (    "   "     (_\_) \___~ `-.___,'  ~|
 |~~ \     (  )_(__)_|( ))  "   ))          "   |    "  \ ~~ ~~~ _ ~~|
 |  ~ \__ (( _( (  ))  ) _)    ((     \\//    " |   "    \_____,' | ~|
 |~~ ~   \  ( ))(_)(_)_)|  "    ))    //\\ " __,---._  "  "   "  /~~~|
 |    ~~~ |(_ _)| | |   |   "  (   "      ,-'~~~ ~~~ `-.   ___  /~ ~ |
 | ~~     |  |  |   |   _,--- ,--. _  "  (~~  ~~~~  ~~~ ) /___\ \~~ ~|
 |  ~ ~~ /   |      _,----._,'`--'\.`-._  `._~~_~__~_,-'  |H__|  \ ~~|
 |~~    / "     _,-' / `\ ,' / _'  \`.---.._          __        " \~ |
 | ~~~ / /   .-' , / ' _,'_  -  _ '- _`._ `.`-._    _/- `--.   " " \~|
 |  ~ / / _-- `---,~.-' __   --  _,---.  `-._   _,-'- / ` \ \_   " |~|
 | ~ | | -- _    /~/  `-_- _  _,' '  \ \_`-._,-'  / --   \  - \_   / |
 |~~ | \ -      /~~| "     ,-'_ /-  `_ ._`._`-...._____...._,--'  /~~|
 | ~~\  \_ /   /~~/    ___  `---  ---  - - ' ,--.     ___        |~ ~|
 |~   \      ,'~~|  " (o o)   "         " " |~~~ \_,-' ~ `.     ,'~~ |
 | ~~ ~|__,-'~~~~~\    \"/      "  "   "    /~ ~~   O ~ ~~`-.__/~ ~~~|
 |~~~ ~~~  ~~~~~~~~`.______________________/ ~~~    |   ~~~ ~~ ~ ~~~~|
 |____~jrei~__~_______~~_~____~~_____~~___~_~~___~\_|_/ ~_____~___~__|
 / \----- ----- ------------  ------- ----- -------  --------  -------\
 \_/__________________________________________________________________/
 """)
print("Welcome to Treasure Island.")
print("Your mission is to find the treasure.") 
print(' You were given a Quest by the king of your kingdom to find the hidden Treasure which your ancestors hid somewhere in the kingdom for thousands of years. ')
print('You where given a clue to where the treasure might be but there is a problem!!! You have to solve a riddle to find the second clue. ')
print("""__________
  /\____;;___\
 | /         /
 `. ())oo() .
  |\(%()*^^()^\
 %| |-%-------|
% \ | %  ))   |
%  \|%________|
  """)
riddle_1 = input(' The riddle is: "What goes up but never comes down?" ')
if riddle_1 == 'age' or riddle_1 == 'Age':
  print(' Congraulations!!! You have solved the first riddle.')
  print('You then realised that the clue spoke about age so you decided to visit the oldest person in the kingdom to ask questions about the clue. ')
  print("When you finally reached his home, He told you that he was waiting for your arrival and handed you the second clue")
  riddle_2 = input('The second riddle is: "I am something, I have a face but no eyes, hands but no arms. What am I?"')
  if riddle_2 == 'clock' or riddle_2 == 'Clock':
    print('Congratulations !!! You have solved the second riddle.')
    print("You then realise that the clue is points out to the Town's clock which strikes at every 12 noon.")
    print('You quickly rushed to the location of the clock just in time for the clock t strike 12:00pm. Immediately the clocked sriked 12 noon, a box came out of the clock and  when you opened it, there it was, the third and last clue.')
    print('The clue was to find the tesure in the castle.')
    print('You quickly rushed to the castle and you found the treasure in the basement of the castle. Which means CONGRATULATIONS!!!!  you have won the game!!!!!! ')
  else:
    print('You failed the second riddle you were then killed by the King of the kingdom.')
else:
  print('Sorry!!! ou have failed the first riddle. You have to start again.')
 
