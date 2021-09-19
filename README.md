# Whatcha Watchin? A tool to keep track of... whatcha watchin

## What and why?
Most of us consume media recreationally, but it seems like the more we consume it, the more that already boundless pool expands. What have I already seen, and what have I dropped? When did I watch it, and what did I think of it? What new (or old) movies or shows look interesting, and how can I keep track of them? Whatcha Watchin (working title, somewhat tacky I know) aims to be a web application that helps its user keep track of the answers to all those questions, helping them develop a collection of their past, present, and future media consumption. Now we can at least document the time we've ~~wasted~~ invested!

## For whom?
Anyone who watches anything ever: movies, TV shows, documentaries, YouTube series, Korean dramas, anime, you name it. I believe that includes you!

## How?
Anime watchers might recognize that this idea seems a lot like MyAnimeList. Users will be able to create accounts in the system, where their personal records are stored in an entry per piece of media. These records include:
- The name of a piece of media.
- Its genre.
- The user's watching status, such as currently watching, completed, dropped, on hold, or plan to watch.
- The user's own rating of it.
- The average rating/ranking by the general public, though we'd have to decide where to pull this from.
- Optionally, any notes or impressions the user has about it.
- Any other features that are equal parts useful and feasible to implement.

Once logged in, the user will be able to create, view, manipulate, and delete entries. Additionally, the user will be able to filter and sort their list based on genre, watching status, genre, and rating. They'd also be able to search for other users, view their lists, and fume about that other user's terrible tastes.

Ideally, we'd pull datasets (such as lists of [Netflix shows](https://www.kaggle.com/shivamb/netflix-shows) or [anime](https://www.kaggle.com/marlesson/myanimelist-dataset-animes-profiles-reviews)) scraped from reputable sources online; these could be useful for providing suggestions/autofill when a user is making a new entry, providing synopses and useful metadata, or maybe even providing suggestions if we can observe patterns in the user's watching behavior.

## Scope
The core concepts of this project like a simple website interface, a login system, and managing the required databases are about par for the course - this course. Whatcha Watchin will offer great utility even if there is only one user, but the existence of many opens up a lot of possibilities. If there is extra time, there are plenty of additional features to add (for example, images or a chat system), and there's no doubt that there will be a lot of ways to streamline the system for better user interpretability. 
