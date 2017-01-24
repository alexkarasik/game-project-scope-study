# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](https://www.mountaingoatsoftware.com/agile/user-stories)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to the following in this file via a pull request:

-   A wireframe of what your game project will look like.
I don't have an imgur account. I drew the wireframe and know what I want it to look like. 

-   The data structure you plan to use.
-
I am not entirely sure about what to answer with this one. An array is a data structure and I think I can see how a Tic Tac Toe game could be built using arrays.
I know there are some data structures like linked lists and trees, but we haven't learned about those in class yet, so I assume that is not the type of response expected.

-   How you will take the markup of the game board and represent it in JS
In terms of pseudu code, I will be having each space on the game board represent an element that can either be toggled by a click by the X or the O player, as long as nobody has clicked it yet.

-   How you plan to approach this project.
I will make a checklist of the requirements that I will refer to as I build the project. I will start by building the board in HTML, then some very basic CSS. I will work on figuring out how the functionality of the toggling and the rules that come with that in the javascript work out and make that next. Then I will connect it to the API to make sure it works as I expect it to. I will add some CSS to make it look more attractive and then make sure everything has been crossed off the checklist.

-   4-8 user stories for your game project.
As a user, I want to be able to signup, login, logout and play on a single page so that it is a simple user experience.
As a user, I want to be able to choose between playing as X or O, because I have a preference.
As a user, I do not want to be able to click a square that has already been clicked by me or my opponent, because that would not be fair.
As A user, I want to see a display of who the winner is after each game.
As a user, I want to be able to play multiple games, because it is so much fun.
As a user, when a game is finished, I want a button to clearly display how I can play the next game.
As a user, I want new games to be rendered automatically and not have to refresh the page.


-   How you plan to keep your code modular.
I had to look up what it meant to keep my code modular to make sure I understood and it means to break up your code into modules so that it has boundaries. We do not want our code to be co-dependent, because that means that small mistakes can cause big issues and may also be harder to find. We want our code to be reusable.

The tasks and rules of tic tac toe are pretty clear and I will try to break down as much of the game as possible. We start with an empty board. The first player chooses X or O. The first player makes the first move. The next player makes their move in a square element that the first player has not yet chosen. This will continue until there has been some combination of 3 boxes in a row chosen.

-   What creative spin will you add to your project?
A few ideas that come to mind:
Allow players to place fake bets against each other.
Use images to represent X's and O's.
Reward the winner with a randomly chosen meme.


-   How will you use version control to backup / track your project?
I am sure not every idea I have with the actual coding will work or even connecting to the API may present some challenges. As of right now, I find the API aspect to be a  bit intimidating. I will log all my progress and give myself comments on ideas I had that didn't necessarily pan out as I expected to or things that did that I want to make a note of.

I imagine this project is going to take several sessions of coding and I want to be able to track where I struggled and be aware of how I solved issues for the future.


-   Do you plan to attempt any of the bonuses?
I honestly don't think I will. As of now, I think this project is ambitious enough for me and even if I were to complete it sooner than expected, I would be more interested in investigating if I could make my code cleaner or more efficeint and making sure I understood every level of how I was connecting to the API. If I can get it to work, I want to understand why it is working as deeply as possible, so I do not think I will have time for the bonuses.

I will try to understand how I would approach it and possibly save it as a project for the future.

You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur]
(http://imgur.com/).
