# Trakt Lists 65+ Rating
All lists are self updated and maintained by https://listrr.pro/ which was made by TheUltimateC0der https://github.com/TheUltimateC0der/Listrr

## Movies 

- Super Hero
https://trakt.tv/users/porkie16/lists/superhero-65-rating

- Docu Movies
https://trakt.tv/users/porkie16/lists/docu-movies

- Thriller Movies
https://trakt.tv/users/porkie16/lists/thriller-movies-rating-65

- Horror
https://trakt.tv/users/porkie16/lists/horror-movies-rating-65

- Anime 
https://trakt.tv/users/porkie16/lists/anime-movies-rating-65

- Sci-fi
https://trakt.tv/users/porkie16/lists/sci-fi-movies-65-rating

- Animation Kids PG max rating
https://trakt.tv/users/porkie16/lists/animation-movies-kids-only-rating-65

- Action 
https://trakt.tv/users/porkie16/lists/action-movies-rating-65-rating

- Comedy 
https://trakt.tv/users/porkie16/lists/comedy-movies-65-rating

- Musical
https://trakt.tv/users/porkie16/lists/musical-movies-65-rating

- Western
https://trakt.tv/users/porkie16/lists/western-movie-65-rating

- Drama
https://trakt.tv/users/porkie16/lists/drama-movies-65-rating

- Family max PG rating
https://trakt.tv/users/porkie16/lists/family-movie-65-rating-pg

- Romance
https://trakt.tv/users/porkie16/lists/romance-movies-rating-65

- Netflixs
https://trakt.tv/users/porkie16/lists/netflixs-movies-65-rating

- BollyWood
https://trakt.tv/users/porkie16/lists/bollywood-movies-65-rating

- Fantasy
https://trakt.tv/users/porkie16/lists/fantasy-movies-65-rating

- Christmas
https://trakt.tv/users/porkie16/lists/christmas-movies-rating-65

- Disney
https://trakt.tv/users/porkie16/lists/disney-movies

- Disney+
https://trakt.tv/users/porkie16/lists/disney-movies-65-rating

- All Movies 1985+ With Rating 80+
https://trakt.tv/users/porkie16/lists/movies-1985-rating-80

- 2019 Movies 65+ Rating
https://trakt.tv/users/porkie16/lists/2019-movies-65-rating

## Tv Shows

- Docu
https://trakt.tv/users/porkie16/lists/tv-docu-65-rating

- HBO Network
https://trakt.tv/users/porkie16/lists/hbo-network-65

- Discovery Network
https://trakt.tv/users/porkie16/lists/discovery-network-65-rating

- Sky Atlantic 
https://trakt.tv/users/porkie16/lists/sky-atlantic-tv-rating-65

- Comdey
https://trakt.tv/users/porkie16/lists/tv-comedy-65-rating

- Sci-Fi
https://trakt.tv/users/porkie16/lists/tv-sci-fi-65-rating

- Drama
https://trakt.tv/users/porkie16/lists/tv-drama-65-rating

- Animation Kids only
https://trakt.tv/users/porkie16/lists/tv-animation-kids-only-65-rating

- Anime
https://trakt.tv/users/porkie16/lists/tv-anime-65-rating

- Superhero
https://trakt.tv/users/porkie16/lists/tv-superhero-65-rating

- Crime
https://trakt.tv/users/porkie16/lists/tv-crime-65-rating

- Reality
https://trakt.tv/users/porkie16/lists/tv-reality-65

- Soaps
https://trakt.tv/users/porkie16/lists/tv-soaps-65-rating

- Netflixs
https://trakt.tv/users/porkie16/lists/netflixs-tv-shows-65-rating

- BollyWood
https://trakt.tv/users/porkie16/lists/bollywood-tv-65-rating

- Apple TV
https://trakt.tv/users/porkie16/lists/apple-tv-shows-65-rating

- Disney+
https://trakt.tv/users/porkie16/lists/disney-tv-shows-65-rating

- Amazon
https://trakt.tv/users/porkie16/lists/amazon-tv-65-rating

- Hulu
https://trakt.tv/users/porkie16/lists/hulu-tv-rating-65

- Amazon/Netflix/Hulu/Disney+/AppleTv+ Combined 80+ rating
https://trakt.tv/users/porkie16/lists/amazon-netflix-hulu-disney-appletv-tv-show-combined-80-rating

- Amazon/Netflix/Hulu/Disney+/AppleTv+ Combined 65+ rating
https://trakt.tv/users/porkie16/lists/amazon-netflix-hulu-disney-appletv-tv-show-combined-65-rating

## Actors and Directors no ratings applied

- Arnold Schwarzenegger
https://trakt.tv/users/porkie16/lists/arnold-schwarzenegger-movies

- Angelina Jolie
https://trakt.tv/users/porkie16/lists/angelina-jolie

- George Lucas
https://trakt.tv/users/porkie16/lists/george-lucas-movies

- Quentin Tarantino
https://trakt.tv/users/porkie16/lists/quentin-tarantino-movies

- Steven Spielberg
https://trakt.tv/users/porkie16/lists/steven-spielberg-movies

- Anthony Hopkins
https://trakt.tv/users/porkie16/lists/anthony-hopkins-movies?sort=rank,asc

- Jason Statham
https://trakt.tv/users/porkie16/lists/jason-statham?sort=rank,asc

- Robert Downey Jr
https://trakt.tv/users/porkie16/lists/robert-downey-jr-movies

## Custom Python Plexlibrary Recipes

I have added my current recipes I have made for Custom Python Plexlibrary Recipes for some of my lists.

https://github.com/adamgot/python-plexlibrary

These recipes will run out of the box for Cloudbox users, for PTS/PG users you will need to edit the local path in each yml file that plex can see.

For example Cloudbox uses /mnt/local/Media/Movies/Sci-Fi/

For PTS/PG it will be have to be a local path that Plex can see, something like /mnt/movies/recipe_title also PTS/PG users need to change the plex link in the main config from http://plex:32400/ to
http://localhost:32400/

Do one recipe at a time and when it pops up in plex edit the lib and remove from dashboard, disable thumbnails, disable cinema trailers and finally disable collections. When creating new libs with receipes it will trigger a scan but its quite quick and doesnt effect anything else being added with PAS. 

To update your custom libs daily drop the plexlibrary.sh from the scripts folder in the repo into /opt/appdata/python-plexlibrary.
> chmod +x /opt/appdata/python-plexlibrary/plexlibrary.sh

Then open cron with.
> crontab -e

Then add a cron at the bottom of the file
> @daily /opt/appdata/python-plexlibrary/plexlibrary.sh
