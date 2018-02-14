# Kaijudo for Cockatrice

## Introduction
Welcome to Kaijudo on Cockatrice! This repository contains everything you'll need to play [Kaijudo](http://kaijudo.wikia.com/wiki/Trading_Card_Game) on the program [Cockatrice](https://cockatrice.github.io/). Cockatrice is a program developed in C++ and QT5 for playing Magic: the Gathering by 
a set of awesome developers. The documentation for their program is very robust, and you can learn everything you need to know about it by following the provided link. Thus, I'll only be giving the basic instructions and some tips and tricks in this guide.

Have an issue with this page or the Kaijudo-specific parts of the implementation *(incorrect card text, etc.)*? [Submit a ticket!](https://github.com/DeadeyeN/Kaijudo/issues/new)

*Special thanks to my friends Mattaiyah and Enhaloed for helping to re-teach me Python, and to my friend Deixis for helping with downloading all of the images.*

## Installation instructions
This installation guide assumes basic computer literacy and a system without Cockatrice installed.

1. Install Cockatrice for your given system, following all on-screen prompts. 
2. Download this repository and unzip it to a location of your choice.
3. In your file explorer, navigate to AppData/Local/Cockatrice/Cockatrice. *(Hint: If you don't know how to find your AppData folder, go to the address bar of your file explorer and type %AppData%. This takes you to AppData/Roaming. Go up one level and you'll find yourself in AppData, and you should be able to navigate from there.)*
4. Drag the `customsets`, `themes`, and `pics` folders of the unzipped repository into the Cockatrice folder. If you already have these folders created, merge the contents.
5. Open Cockatrice and follow any prompts that it gives to enable sets. If you don't see any Kaijudo cards in the card list, restart Cockatrice.
6. In the settings menu (Cockatrice -> Settings), in the "Appearance" tab, select Kaijudo in the theme dropdown.
7. In the Edit Sets menu (Card Database -> Edit sets), make sure that the Kaijudo set is enabled. If you don't like the artwork that has been provided, you can place your own artwork in the CUSTOM folder following the Cockatrice instructions.

You're done! Restart Cockatrice if needed, then start building and playing!

## Using Cockatrice for Kaijudo
Here are some gameplay tips and tricks to help your game go smoothly and effectively.

1. To place a card facedown on the field, hold `Shift` as you drag the card from whatever zone it's in to the field. For example, as you place orbs at the beginning of the game, hold `Shift` and drag seven cards to the bottom row of your field.
2. Double-clicking a card will usually get it to where you want it to go. For example, double-clicking a creature will automatically put it in your stack area, and doubleclicking it from there will place it into your battlefield *(the top row of the play area)*, and double-clicking a spell card will put it in the stack area.
3. To break a shield, **always use the "peek at card face" command on that card before moving it to your hand!** If you don't, you won't know whether that card has a Shield Blast ability or not until it's already in a private zone. Every facedown card is numbered, so make sure you keep track of both your and your opponent's facedown cards.
4. If you can't figure out how to manipulate the cards to do what you want them to do, explore the rightclick menu on all sorts of objects in the window. It has tons of useful options for interacting with the GUI if you can't remember the keyboard shortcuts.
5. I realize that the power can't be displayed normally; that's an unfortunate feature of Cockatrice. I've divided the numbers by 100 so that they can still fit on the card, and they work functionally the same way. Just pretend they're the full X000 if you need to.

## List of Included Sets
* Quest for the Gauntlet
* Horde Onslaught
* Vortex
* Eye of the Storm
* Gauntlet Promos
* Vortex Promos
* Clash of the Duel Masters
* Shattered Alliances
* Invasion Earth
* Booster Brawl
* The 5 Mystics
* Year 2 Promos
* Tatsurion vs. Razorkinder
* The Dojo Edition
* Rise of the Duel Masters
* Evo Fury
* Dragon Master Collection Kit
* DragonStrike Infernus
* Year 1 Promos
* Triple Strike

All provided card images are whatever image appears latest on the Kaijudo Channel database. Likewise, all set info is scraped directly from that source.

#### Disclaimer
I do not own Kaijudo or contribute to Cockatrice. This is only a text document containing publicly available information. I do not gain anything from this project other than the personal satisfaction that I was able to help spread an awesome game.
