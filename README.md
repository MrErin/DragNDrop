# Project:

## Requirements:

The user should be able to drag one of the middle cards into either the top box, or the bottom box. However, there's a problem with the way the code currently works. There's also a couple changes you need to make.

## Currently Working On:

## Remaining Features:


## Stretch Goals:

## Completed features:

1. The user should only be able to drag one card into either box. Use the childNodes property to ensure that, if a card is already in the box, another can't be added.
1. If you drag one of the cards into the top/bottom box, and then drag another card into the first one, you get a nested card. You need to prevent this from happening.
1. The user should be able to move a card from the top/bottom box back to the middle.

## Structure:

* .stage refers to a card
* .target is one of the two boxes (finished and current)
