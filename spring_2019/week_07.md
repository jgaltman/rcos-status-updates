## Last Week's Accomplishments

Last week we finally have a running website at flom.ml
The site is far from complete but it is functioning currently. We have two rooms that display occupancy changes based on fake data. This past week we increased the speed of the site by adding to the cache and pull from postgres less. We pass the waiting time onto the RaspPi rather than the user. Additionaly UI improvements have been made this past week too. Security Keys for each room were added in the code this week too. 


## This Week's Plan

This weeks plan is to implement a login for user to help with secutity. We also want to authenticate users with email and possibly the cas authentication that professor Turner mentioned. We will also track user analytics to help improve the site. Tests still need to be made on the site, both manually and automated. We would like to integrate with the hardware as soon as possible so part of the team may try to help the hardware team this week as well. Lastly this week we will fix bugs we found in the DB and improve upon the UI further.


## Anything Blocking?

Security still is a concern for RPI and thus deployment may be hindered but development is fine currently.

## Notes
Changing timezones in Django is proving difficult