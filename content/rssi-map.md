Title: Mapping radio signal strength 
Date: 2016-3-06 10:20
Category: projects 
Slug: my-super-post
Author: pvos 
Summary: Mapping radio signal strength 

<a href="https://github.com/p-v-o-s/rssi-map"><img src="|filename|/assets/signalStrength.png" width=300></a>

This project involved logging sensor data to a file on a computer (in this case, remotely, via radio transmission) while simultaneously recording GPS location using a smartphone app. Because GPS recording devices (like smartphones) are common, and generate KML or GPX files, the resultant problem may fairly common: how to easily combine GPS data (recording at some logging rate, on e.g. a smartphone) with a separately-recorded sensor data file (which may have been logged at some other rate, but overlaps in time with the GPS data).

See the associated <a href="https://github.com/p-v-o-s/rssi-map">github repo</a> for a description of all the steps, with accompanying code.  
