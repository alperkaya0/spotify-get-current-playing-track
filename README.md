Create a new app from spotify developers site, and fill the wanted constants within the code according to this video :</br> 
https://www.youtube.com/watch?v=-FsFT6OwE1A&ab_channel=EuanMorgan </br> **please give his video a thumbs up** </br></br> 
Awesome man that i have taken half of the code is here </br> https://www.youtube.com/watch?v=yKz38ThJWqE&ab_channel=ImdadCodes </br> **please give his video a thumbs up** </br></br> 
You can decrease the sleeping seconds so that it will work better but work more,</br> don't forget to increase 1000 (line 115) so that when counter = 3600/sleeping_factor you will refresh your token BUT since refreshing maybe take longer according to your internet connection i suggest you to making it lower than 3600/sleeping_factor for example if you time.sleep(1) every iteration so 3000 is a nice choice.</br> And it refresh everytime you open the script.(Why 3600 because access token expires after 1 hour)
