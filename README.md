# bkk_network

Imagine, that a group of travelling salesman wants to visit all public
transport stations in Budapest. They want to accomplish this task
as quickly as possible. So they hook up the map of Budapest, locate
the stations and start to plan their visits. They can use only public
transport to reach the stations except in the first step, where they
can start at any station. In the first planning round they build the
network of the stations by connecting that ones where at least one
public transport line connects the two stations.
The people int the group try to make a station-visiting plan,
which results the shortest overall time, which is needed to visit all
the stations for the group! Try to minimise the time,
which is needed for the group! Here you should take into account the
timetable as well for the lines!

A salesman visits a station by getting off the vehicle and staying at least 5 seconds on the station. Note, that
in this case you should play with the optimal starting time as well!
Compare your results with a randomised version of timetable, where
you randomly redistribute the starting time on the nodes but keeping
the time difference statistics intact.
In this reference work you and a good description of the time randomisation: https://arxiv.org/pdf/1006.2125.pdf

The time table and the public transport database for Budapest is available from the BKK website: https://bkk.hu/apps/gtfs/ 
https://bkk.hu/en/developers/
