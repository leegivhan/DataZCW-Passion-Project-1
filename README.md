# DataZCW-Passion-Project-1
## Mutual Musical Match
#### Predictive analytics tool for musicians to find mutual contacts that will like their music.

Friends inviting friends to concerts has been a great way for musicians to grow their audiences. Now that concerts are not happening due to Covid, artists need new ways to connect to grow their fan base. My passion project is a predictive analytics tool for musicians to see friends of friends that are potential fans. The algorithm works in the following steps:

1. The model uses API’s from social media websites like Instagram and Twitter to see who is following a specific musician. 
2. The algorithm looks at who else the people that are following the musician are following. 
3. Of people that those following the musician are also following, the algorithm creates a list of commonalities ordered by their frequency.
4. The software then looks for mutual acquaintances of the musician and their friends who share the most commonalities from that list
5. Lastly, it sends a list of these mutual acquaintances to the musician. (The idea being that the musician would ask their friends to reach out to this person.)

Tools: 
* Kafka
* Spark
* Python
* Pandas
* Airflow
* AWS