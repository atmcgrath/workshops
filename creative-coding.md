---
title: Creative Coding with Bitsy
date: April 22, 2025
author: Alice McGrath
subtitle: Introduction to Digital Humanities
format: 
    revealjs:
        theme: moon
        controls: true
        #embed-resources: true
css: "https://alicemcgrath.digital.brynmawr.edu/pres/a3.css"
editor:
    render-on-save: true
---

# Outline {background-color="indigo"}

1. What is creative coding?
2. Introduction to Bitsy
3. The Bitsy Editor
4. Planning and developing your game
5. Saving and publishing your game

# Creative Coding {background-color="indigo"}

Using code to explore and play: games, artwork, storytelling, experiments.

- Listen: Mark Sample, ["Dream Lab Podcast: Creative Coding"](https://pricelab.sas.upenn.edu/podcast/1/dream-lab-podcast-%E2%80%A2-creative-coding)

# Examples

- Twitter Bots, e.g. [@Pentametron](https://pentametron.com/)
- [The infinite catalog of crushed dreams](https://fugitivetexts.net/pandemicdreams/), Mark Sample (2020)
- [One Hundred Thousand Billion Bryn Mawrs](https://digitalscholarship.brynmawr.edu/100-tbbm/) (2025).  Inspired by Raymond Queneau's [*One Hundred Thousand Billion Poems*](https://en.wikipedia.org/wiki/A_Hundred_Thousand_Billion_Poems) (1962)
- ["The Wilderness Downtown"](https://indoek.com/article/arcade-fire-the-wilderness-downtown/), Chris Milk (2010)

# Tools

- [Twine](https://twinery.org/) - interactive text-based storytelling tool
- [Unity](https://unity.com/) - 3D game engine
- [Processing](https://processing.org/) - software language for visual design
- [Bitsy](https://www.bitsy.org/) - 8-bit game engine
- A much longer [curated list](https://github.com/terkelg/awesome-creative-coding)


# Bitsy {background-color="indigo"}

![](media/bitsy-cat.png) <!-- {.width=10} -->

[bitsy.org](https://www.bitsy.org/)

- A tool for building [8-bit video games](https://en.wikipedia.org/wiki/Third_generation_of_video_game_consoles)
- Open-source, browser-based, and easy-to-learn

# Bitsy examples

- [Chop Suey](https://skwabrynmawr.github.io/SUEY/CHOPSUEY.html) by Shiamin Kwa
- [Under a star called sun](https://haraiva.itch.io/under-a-star-called-sun) by Cecile Richard
- [Kitten-wrangler](https://atmcgrath.github.io/kitten-game/) by Alice McGrath


## {.smaller}

<iframe src="https://skwabrynmawr.github.io/SUEY/CHOPSUEY.html" width="600" height="600"></iframe>

[CHOPSUEY](https://skwabrynmawr.github.io/SUEY/CHOPSUEY.html) a Bitsy game by Shiamin Kwa

## {.smaller}

<iframe src="https://atmcgrath.github.io/kitten-game/" width="600" height="600"></iframe>

[Kitten-wrangler](https://atmcgrath.github.io/kitten-game/) by Alice McGrath. On GitHub: [atmcgrath/kitten-game](https://github.com/atmcgrath/kitten-game)

## Features of a Bitsy game 

::: {.incremental}

- Multiple rooms or spaces to move through
- Simple UI text
- Non-player characters to interact with
- Objects to pick up (can be counted)
- Exits and entrances (can have conditions/require keys)
- Music, sound effects, and simple animation options
:::

# The Bitsy Editor {background-color="indigo"}

A tour of the Bitsy editor interface: [make.bitsy.org/](https://make.bitsy.org/)


## Editor windows {.scrollable .smaller}

- **tools**: show the menu of tool windows, select which ones to toggle on
- **play**: test out your game
- **about**: instructions and documentation
- **game**: load or save your game
- **room**: the main editor for the space of your game
- **paint**: design and add your characters and objects
	- **avatar**: your player
	- **tile**: an obstacle square
	- **sprite**: NPC who can deliver information
	- **item**: objects you collect
- **exits & endings**: what happens when you finish a room
- **colors**: customize colors
- **dialog**: UI text and narrative elements (interaction conditions)
- **tune** and **blip**: music and sound effects
- **find**: search among your game resources
- **inventory**: keep track of items and variables

# Your turn! {.scrollable}

- Give your game a title
- Customize your colors
- Create two rooms and customize them with tiles
- Create an exit to link the two rooms
- Place a sprite and some items (use 'paint')
- Edit and add dialogs
- Play your game to test it out!

## Challenges

- Customize your avatar, sprites, tiles, and items
- Create a locked exit dialog to impose conditions
- Customize music and blips
- Look at your game 'data' (under 'game' window): what do you see? 

# Planning your game {background-color="indigo"}

## Storyboarding

- Who is your avatar character?
- Where are they? 
- What is their mission?
- Who and what will they interact with?

## UX design

- How will your player know what to do?
  - Dialogs and Sprite interactions
- What are the spaces/levels/narrative beats?
  - Rooms, dialogs
- Set up challenges and conditions
  - Locked exits, dialogs, variables

# End-game {background-color="indigo"}

## Saving and loading your game

- Select 'game' to open the export-import menu
- Select 'save game' to download your game as  `.html`
- When you want to work on it again, it may have been saved in your browser session. Otherwise, you can select 'load game' and upload the same html file

## Publishing your game

You have two options for publishing your game on the web: 

- [GitHub](https://github.com/) offers free webhosting through GitHub Pages
- BiCo folks can get a webhosting account through [Domain of One's Own (BMC)](https://digital.brynmawr.edu) or [Haverford Sites (HC)](https://sites.haverford.edu/)

## GitHub instructions {.scrollable .smaller}

### 1. Create a new repository

- Log in to [GitHub.com](https://github.com/) and create a new repository called "bitsy-game"
- Upload the html file for your game to the repository
- Rename the html file `index.html`

### 2. Publish your repository

- From your repository, go to the 'settings' tab and scroll down to pages
- Under 'Source' select 'deploy from a branch' and select "main" branch, then "save"
- Wait for a few minutes for the deployment to finish
- Your site's url: `username.github.io/bitsy-game`

NB: [this GitHub deployment guide](https://atmcgrath.github.io/intro-dh/resources/deployment.html) has step-by-step instructions and screenshots

## Domain of One's Own {.scrollable .smaller}

- Navigate to [digital.brynmawr.edu](https://digital.brynmawr.edu/) or [sites.haverford.edu](https://sites.haverford.edu/)
- Click 'Get Started' and sign in with your username
- Select a personal subdomain name (this will be part of your URL)
- Locate the "File Manager" (in the "Files" section) on the list of tools
- Navigate to the "public_html" folder
- Create a subfolder called "game" 
- Renaim your game file `index.html`
- Upload it to the "game" folder
- Your site's url: `yourdomain.digital.brynmawr.edu/game`

## Making changes

- Load your Bitsy game file back into the editor
- When you are done, export the html file and replace the old one on GitHub or DoOO
- Don't forget to change the filename to 'index.html'

## Resources

- This [Bitsy Handout](https://rahji.github.io/bitsy-handout/web/) has lots of tutorials and resources
- Read the [Bitsy documentation](https://make.bitsy.org/docs/)
- Check out [other Bitsy games](https://itch.io/games/made-with-bitsy)

## Return to [Intro DH Site](https://atmcgrath.github.io/intro-dh/)