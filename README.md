# iOS-Tweet-Search
A easy to follow demo of a tweet search using Twitter's new 1.1 REST api.

Overview: This is the basic platform I designed in order to search tweets using iOS Twitter API's. The app has two main functionalities: search and save tweets, view and delete saved tweets. Twitter's previous REST api versions were easy to interact with using various 3rd party RESTful api's such as AFNETWORKING or RESTkit. Recently twitter changed their REST API. Although it is still possible using 3rd party api's, it is much easier using this method.


Description: This app demonstrates using Accounts.h and Social.h to search tweets, and saving information into Core Data. The app perfoms a search of all user tweets for a specify keyword/s. These results are displayed on a table view and the user has the ability to select tweets they like to view later. The saved tweets are stored in Core Data. These saved tweets are then loaded from Core Data and displayed in a table view, where the user has the ability to delete them from the Core Data Stack.

The application of this app is quite powerful. This template sets up a twitter interaction, you can limit the tweet searches to the users friends, you can further parse the JSON that twitter sends to get more information of each individual user the search renders. This app also demonstrates the ease of using Core Data Entity types and how effective they can be when working in a storyboard or with multiple XIB's.

Usage: The app is compatable with all Apple iOS devices. You may use the functions and classes within to your hearts desire! 
