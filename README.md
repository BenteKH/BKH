# Computational Musicology
*Bente Klein Hazebroek*  **I**  *11863226*  **I**  *February 2019*

## My Corpus
I am looking at Spotify's 'Coffeehouse' and 'On the Road' playlists. A coffeehouse is a pleasant place where you can talk, work or read while enjoying a cup of coffee; you will probably listen to easy, mellow songs here. But, when you're on the road, you have to kill time while going from A to B (whether you're alone or with friends; you go to work or are on a holiday). Since the car is a private place, you might listen to uplifting, sing-along songs. What are the characteristics of these playlists and in what way do they differ? I am using the following playlists for this research, composed by Spotify and Digster Nederland:

  **Coffeehouse:**
  
    1. Coffeehouse - Feel the vibe of the Coffeehouse playlist, full of relaxing singer-songwriter an pop music.    
    2. 't Koffiehuis - 'n Bakkie en gemoedelijke muziek op de achtergrond.    
    3. Your Favorite Coffeehouse - Curl up in your favorite spot with some sweet, mellow tunes...
  
 **On the Road:**
 
    1. Classic Road Trip Songs - The ultimate playlist to fuel your good mood while on the road.
    2. Onderweg - Met deze playlist heb je altijd de beste hits bij de hand voor onderweg.
    3. Road Trip - Go on a weekend getaway with your barkada and your favorite hits!
    
This results in a total of 281 Coffeehouse songs and 168 On the Road songs.

## Findings

###### *Track popularity*
The Coffehouse playlists have a mean track popularity of 52.38 (SD = 25.751), whereas the On the Road playlists have a higher mean track popularity of 61.68 (SD = 29.766). This makes sense, since the On the Road playlists contain more songs that everyone can sing along to, and are thus familiar to a large audience. 

##### *Energy*
I expect that energy of the On the Road playlists is much higher than for Coffehouse playlists. While on the road, you need to stay awake, so most songs have a loud beat. Coffeehouse songs, on the other hand, sound more quiet and peaceful. Spotify measured that the average energy in On the Road songs is 0.6131 (SD = 0.295) and 0.3596 (SD = 0.262) in Coffehouse songs. Indeed, energy seems to be much higher in On the Road playlists. 

##### *Danceability*
Since the energy is higher in On the Road playlists, I thought danceability would be higher as well. There is indeed a difference, but this difference is smaller than I thought it would be: 0.6051 (SD = 0.191) On the Road vs  0.5495 (SD = 0.237) Coffeehouse. Energy  does not seem to play a role in the danceability of songs, so I'm not sure what danceability it based on then.

##### *Acousticness*
Characteristic for mellow Coffeehouse songs is their high acousticness (0.6589, SD = 0.347). The playlists contain mostly easy, soft songs that are accompanied by piano or guitar without much of electronic sounds. The acousticness of these playlists is thus, as expected, much higher than for On the Road playlists (0.2932, SD = 0.353). 

#### *Instrumentalness & Speechiness*
The instrumentalness does not really differ for Coffeehouse playlists (0.0319, SD = 0.243) and On the Road playlists (0.0253, SD = 0.322). The standard deviation is also quite high for both kinds of playlists, so I don't think that high/low instrumentalness is a characteristic of either playlist. The same goes for speechiness. 



summary(TOTALCOFFEEHOUSE$speechiness)
   Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
0.02360 0.03030 0.03440 0.04317 0.04030 0.39000 
> summary(TOTALCOFFEEHOUSE$speechiness) %>%
+ sd()
[1] 0.1453607
> summary(TOTALONTHEROAD$speechiness) %>%
mean = 0.06675
+ sd()
[1] 0.1710481

  
