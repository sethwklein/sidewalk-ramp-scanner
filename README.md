# Sidewalk Ramp Scanner

Name not final.


## Problem Definition

Sidewalk crosswalk ramps are not cleared well during the winter in
Portland, Maine.


## User Stories

As a wheelchair user, I can find a route that uses only sidewalk ramps
someone has checked.

As a smart phone user, I can get notifications when I'm near a sidewalk
ramp that hasn't been checked.

As a smart phone user, I can report a ramp that hasn't been cleared.

As a smart phone user, I can report a ramp that has been cleared.

As person with spare time, I can find ramps that need checking.

[Some story around being able to report on how well ramps are getting cleared
over time.]


## Features

* map of ramps
    * ramps have "age"
    * or maybe an admin resets when there's a storm
    * or maybe a weather service can provide good enough data to automate
        resetting (a toil reduction feature for later)
* browse old ramps
* route finding that avoids old ramps
* report on ramp (good or bad)
    * bad with photo (required or optional?)
    * maybe require gps (not too tight)
    * these things might help avoid having to require user signup


## Project Status

Some people are thinking about it. No one is seriously working on it. If you'd
like to, feel free to make tons of pull requests.

We have ramp data from the city in `ramps-data/Ramps.gdb.zip`. Using
it is #2 which might benefit from #1.

If you need help figuring out how to make pull requests, the [Code for Maine
Slack]() is a great place to ask, as are any of the [Hack Portland
Meetups](https://www.meetup.com/Hack-Portland), but especially the civic
themed one on the second Tuesday of every month.
