Python-Conditionals-and-Control-Flow
====================================

This the Conditionals and Control Flow Section of Python (@ Code Academy)


1/15-
def clinic():
    print "You've just entered the clinic!"
    print "Do you take the door on the left or the right?"
    answer = raw_input("Type left or right and hit 'Enter'.").lower()
    if answer == "left" or answer == "l":
        print "This is the Verbal Abuse Room, you heap of parrot droppings!"
    elif answer == "right" or answer == "r":
        print "Of course this is the Argument Room, I've told you that already!"
    else:
        print "You didn't pick left or right! Try again."
        clinic()

clinic()


2/15-
# Assign True or False as appropriate on the lines below!

# Set this to True if 17 < 328 or to False if it is not.
bool_one = True   # We did this one for you!

# Set this to True if 100 == (2 * 50) or to False otherwise.
bool_two = True

# Set this to True if 19 <= 19 or to False if it is not.
bool_three = True

# Set this to True if -22 >= -18 or to False if it is not.
bool_four = False

# Set this to True if 99 != (98 + 1) or to False otherwise.
bool_five = False

3/15-

# Assign True or False as appropriate on the lines below!

# (20 - 10) > 15
bool_one = False    # We did this one for you!

# (10 + 17) == 3**16
# Remember that ** can be read as 'to the power of'. 3**16 is about 43 million.
bool_two = False

# 1**2 <= -1
bool_three = False

# 40 * 4 >= -4
bool_four = True

# 100 != 10**2
bool_five = False

4/15-
# Create comparative statements as appropriate on the lines below!

# Make me true!
bool_one = 3 < 5  # We already did this one for you!

# Make me false!
bool_two = 9 < 7

# Make me true!
bool_three = 3 == 3

# Make me false!
bool_four = 4 > 5

# Make me true!
bool_five = 5 <= 6

5/15-"""
     Boolean Operators
---------------------------
True and True is True
True and False is False
False and True is False
False and False is False

True or True is True
True or False is True
False or True is True
False or False is False

Not True is False
Not False is True

"""

6/15-
bool_one = False 

bool_two = False

bool_three = False

bool_four = True

bool_five = True

7/15-
bool_one = True

bool_two = True

bool_three = False

bool_four = True

bool_five = False

8/15-
bool_one = False

bool_two = True

bool_three = True

bool_four = True

bool_five = False

9/15-bool_one = False

bool_two = True

bool_three = True

bool_four = True

bool_five = False

10/15-
# Use boolean expressions as appropriate on the lines below!

# Make me false!
bool_one = (2 <= 2) and "Alpha" == "Bravo"  # We did this one for you!

# Make me true!
bool_two = (2 <= 3) and "Alpha" <= "Bravo"

# Make me false!
bool_three = (3 <= 3) and "Bravo" == "Charlie"

# Make me true!
bool_four = (4 <= 5) and "Charlie" <= "Delta"

# Make me true!
bool_five = (5 <= 6) and "Delta" <= "Echo"

11/15-
response = 'Y'

answer = "Left"
if answer == "Left":
    print "This is the Verbal Abuse Room, you heap of parrot droppings!"
    
# Will the above print statement print to the console?
# Set response to 'Y' if you think so, and 'N' if you think not.

12/15-
def using_control_once():
    if True:
        return "Success #1"

def using_control_again():
    if True:
        return "Success #2"

print using_control_once()
print using_control_again()

13/15-
answer = "'Tis but a scratch!"

def black_knight():
    if answer == "'Tis but a scratch!":
        return True
    else:             
        return        # Make sure this returns False
    False
def french_soldier():
    if answer == "Go away, or I shall taunt you a second time!":
        return True
    else:             
        return False        # Make sure this returns False
    False
    
    14/15-
    def greater_less_equal_5(answer):
    if answer > 5:
        return 1
    elif answer < 5:          
        return -1
    else:
        return 0
        
print greater_less_equal_5(4)
print greater_less_equal_5(5)
print greater_less_equal_5(6)

15/15-
# Make sure that the_flying_circus() returns True
def the_flying_circus():
    if 9 <= 9:    # Start coding here!
        print "It's true"
        return True
    elif 6 == 8 or 99 < 88:
        return False
    else:
        return False
        
                                      END Conditionals and Control Flow Lesson                                          
