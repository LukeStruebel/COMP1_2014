#Task Sheet One Answers:

##Question 3(a):

1. Which function is responsible for getting the name from the user?
The GetPlayerName() function is used to get the users name.

2. How will you ensure that the user is asked for the name repeatedly?
A while loop will repeatedly ask the User for their name until they enter a Name longer than 0 characters.

3. What additional variable will you need and what will its datatype be?
The variable NameValid will be needed for the while loop to work, this is a Boolean DataType

4. Write the function identified above in pseudo-code with the improvements necessary to prevent the user leaving their name blank.

NameValid <- False
WHILE NOT NameValid:
	OUTPUT("Please enter your Name: ") <- PlayerName
	IF LEN(PlayerName) = 0 THEN:
		OUTPUT("Please enter a Valid Name.")
		NameValid <- False
	ELIF LEN(PlayerName) > 0 THEN:
		OUTPUT("Name Valid")
		NameValid <- True
		RETURN PlayerName
	