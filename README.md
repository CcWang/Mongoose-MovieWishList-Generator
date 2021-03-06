# Mongoose-MovieWishList-Generator
also refer to https://github.com/BitTigerInst/Mongoose-MovieWishList-Generator
# Screenshot  
![alt tag](https://raw.githubusercontent.com/BitTigerInst/Mongoose-MovieWishList-Generator/master/screen.png)  
# live on  
[CHECK IT OUT!](http://52.11.63.40/) 
# Update report on Feb 26, 2016  
Since douban.com has set cralwer-prevent technology, so we had to switch to use APIs from TMDb (The Movie Databases) to get info of movies.  
We use React as the view and rails as our backend framework.
Demo viedo is available on https://youtu.be/oTXdoxWeIZo
#Updated features:  
1. User login and registeration with validation.  
2. User pick up some top rated movies from lists and the system determines his favorite genre. 
3. System renders some movies based on user's taste. User can pick up movies and add to his own wishlist.  
4. User can click "I am feeling lucky" to change movie recommend list.  
5. User can click "Discover More" to see recommended movies from other genres.  
6. User can remove movies from his wishlist whenever he wants.
7. System updates user's taste dynamically when user changes his wishlist.

#Future plan  
1.Compare users' wishlists and suggest friends to user with high similarities.    
2.Display movie details in a new page or pop-over.  
3.Let user discover movies on show in theatres nearby.  
4.Let user add comments to movies.  
# Description  
Movie is one of the hottest entertaiment for people nowadays. However,in most cases, it's not easy to find the right movie to watch. And people are usually not active to build their own movie wish list. So we are going to make one for them. Based on the analysis of movie databases from douban.com, we can generate the proper wish list for one particular user. It can be developed further to be a promotion for other movies.

# Architecture
First, we are going to make use of python scrapy to make our crawler scripts. The crawler downloads the information of the hottest movies(sorted by release date) as a json file. The file includes the basic info of the movie and the references of the users who are interested in it. Then we imported the json files into MongoDB for analysis.  
  
Second, we will do analysis on the movie databases and select top 5 movies that a particular user are most likely interested in. The selection algorithm may consider factors/parameters as user ratings, release date and whether it is popular. After the selection, we will add the 5 movie references to that particular user.  
  
Third, we will use react to render the movie wish list for users. In this way, our application covers full stacks.  
# Plan
[2016/02/01 - 2016/02/07] Project Selection, Plan Discussion, and Proposal Draft Writing  
[2016/02/08 - 2016/02/24] System Design, Resource Discovery, Project Implementation, Document Writing  
[2016/02/25 - 2016/02/29] User Manual Writing and Video Presentation Making  
Details of each schedule and task will be added later.  
 
# Language & Framework  
Ruby on Rails
JavaScript  
Postgresql  
React  
# Owner
@Team: Mongoose  
@Contributers: xinyzhang9,CcWang
