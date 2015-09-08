# Custom Mapbox style for Veloviewer by Dejan Kamenšek, based on Peter I. Papics [papics.eu] custom style

Custom style for [Mapbox Studio](https://github.com/mapbox/mapbox-studio).

Biggest problem and dissapointment after playing around with this style for mapbox was realisation, that Mapbox doesn't make use of GRADE info of paths, which is (my opinion) one of the most important infos about non-paved tracks.
All the tracks (OSM highway/track/grade 1-5) have the same classification in Mapbox, that is Road/Service/Track, so I can't distinguish them on map!

In reality grade 1 and 2 tracks are easily drivable by car and bike, grade 3 is passably by MTB up and down, grade 4 is passable by bike only down (up would be very hardcore), and grade 5 is hardly passable by MTB even downway (steep also by foot)...

All that unfortunately means, that I can't create a usable style for biking/hiking, because you have no idea if the service road is passably only by feet or even by car :(((  Open Cycle Map also has this limitation, so it is not really very useful :/
At least track grades are differentiated by default Open Street Map style:

https://www.openstreetmap.org/#map=17/46.51954/15.55658

But not (yet?) in Mapbox:
https://api.mapbox.com/v4/kamac.e58a8d34/page.html?access_token=pk.eyJ1Ijoia2FtYWMiLCJhIjoiNmUzZTg3YzMxZTljOTFjOWE3MzhjOWI2ZjhhMzFmOGMifQ.K75z6vkvQUq-Xoj2h8QKtA#17/46.51954/15.55658

This realization was a game killer for my Mapbox adventure which is on hold now until they make grade info accessable... :(((
