Class project tutorial for CS123 at Harvey Mudd College \
Made with [Ananya Purwar](https://github.com/apurwar4) and [James Duffy](https://www.linkedin.com/in/james-duffy-6651aa2a8/)

## Overview
This tutorial teaches users how to generate a "Goodreads Aura", a colorful image based on the genres of the books they read, 
based on the [Spotify Aura](https://engineering.atspotify.com/2021/12/the-audio-aura-story-mystical-to-mathematical/). They follow the general outline:

- Build and train an NLP classification model, which takes in a book description and outputs a genre
- Import the user's Goodreads data (sample data provided)
- Webscrape the Goodreads websites to get descriptions for each book
- Compute the genres of each book using the NLP model
- Creating an "aura" visualization based on the most frequently read genres
