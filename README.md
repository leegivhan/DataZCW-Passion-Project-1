# DataZCW-Passion-Project-1
## Mutual Musical Match
#### Predictive analytics tool for musicians to find mutual contacts that will like their music.

Friends inviting friends to concerts has been a great way for musicians to grow their audiences. Now that concerts are not happening due to Covid, artists need new ways to connect to new fans. My passion project is a predictive analytics tool for musicians to see friends of friends that are potential fans. The algorithm works in the following steps:

1. Gathers data about who is following a specific musician using the Twitter API. 
2. Gathers data about the target user’s followers to find other common accounts followed by the target user’s followers. These commonly followed accounts are put into a list of "common interests." 
3. Finds mutual acquaintances of the target user (friends of friends) who share the most commonalities from the list of common interests. 

Tools: 
* Python
* Pandas
* AWS