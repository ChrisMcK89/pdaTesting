### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:


  def check_for_ace(self, card):
# == should be used
    if card.value = 1:
      return True
#   ':' missing after else 
    else
      return False
   

# 'dif' should be 'def' and missing ',' between card1 and card2
  dif highest_card(self, card1 card2):
#   missing indentation
  if card1.value > card2.value:
#  should return card1
    return card
  else:
    return card2
  

# needs indentation
def cards_total(self, cards):
# should be = 0
  total
  for card in cards:
    total += card.value
# needs moved out of for loop and changed to string
    return "You have a total of" + total
  
```