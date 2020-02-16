### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.
```ruby

class CardGame

# CardGame has not be defined

# The below code is wrong as it is not a good practice for the name of the
# definition includes a capital letter.CheckforAce would be better if the name is
# check_for_ace. In the if statement the card.value should be card.value==1 instead of
# card.value=1.
  def checkforAce(card)
    if card.value = 1
      return true
    else
      return false
    end
  end

  # The below code is wrong as dif should be def. Also a comma is required between
  # the card1 and card2. Also, there is an extra unnecessary end on the below code.

  dif highest_card(card1 card2)
  if card1.value > card2.value
    return card
  else
    return card2
  end
end
end

# The below code is wrong as total does not include anything.
# Also, string interpolation is required to the total in the return line to make sure that total would get the necessary value after the loop.
#Finally, there is no need for the self in the below function.
def self.cards_total(cards)
  total
  for card in cards
    total += card.value
    return "You have a total of" + total
  end
end
```
