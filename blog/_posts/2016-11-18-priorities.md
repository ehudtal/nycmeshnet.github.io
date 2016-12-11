---
layout: post
title: "Priorities"
author: Brian
---
Here is my list of priorities for the mesh in order of importance. I'll keep this updated.

**Supernode**

The supernode at 375 Pearl St. is our first install on a tall structure. Here is our remaining todo list:

Configure BGP
Install VPN software
lay more ethernet or dc cable
Get tax-exemption status with suppliers  
Pick up donated AirFiber pair  
Decide best P2P points to extend backbone  
Get P2M users (up to 2 miles) via mailout etc.  
Install and test P2P and sector P2M antennas   
Turn it on  

**Tall structure installs**

Tall structures are the only way we can expand the wireless mesh. This is by far our biggest priority. There are a few different types in the city and we need to try them all- NYCHA buildings, skyscrapers, churches, schools, libraries, existing antenna masts and building coops. We need specific presentations and handouts for each of these types of structures. We are currently approaching libraries and [churches](../../leaflet/church.pdf). We need to build presentations for coop boards and others.  

Once we have a tall structure in a neighborhood we can link to apartment building rooftops.

**Public Access Points as gateways**

Apart from the supernode, we need more internet gateways. Another kind of gateway is a public wifi access point. By using directional routers we can extend the range of public access points very easily. We have discussed this with some city infrastructure people and we think it is important to pursue this method. It will help us expand very quickly. Here are some instructions- [how to connect to a kiosk.](../public-access-points)

**Monitoring team**

We need a small team that is dedicated to monitoring and maintaining the network. Monitoring, alerts and maintenance are hugely important. We are using Nagios, Icinga2 and custom software. We need to keep every node active.

**Cheap 2GHz and dualband routers**

TP-Link locked down its 5GHz routers so we no longer have dual-band support. The 842ND is discontinued and the 841 has poor OpenWrt support. We are currently compiling new firmware so we can start adding support for more routers. Suggestions of cheap, off the shelf hardware are welcome. We are looking at the GL-AR150 and ZBT Ape522.

**Collaborations**

We are just starting some exciting collaborations with Zoetic Networks and Brooklyn Microgrid, and we are in talks with Chinatown B.I.D and NYCHA. This is essential to our growth and we should have more of this. 

**Donations**

The supernode has a monthly rental and we need to get monthly donations to cover this. So far we have over $4000 donated, mostly from a few generous people, which will cover most of the install. You can donate via our [donate page.](../../donate)

**Work and storage space**

We need a place to store our install gear and also work on routers etc.

**Software services**

The mesh network has around 5 small servers that can be accessed using our ".mesh" domain. This has been difficult to maintain. We do have IRC installed and running across three servers but it is rarely used. We need distributed software that will still work when servers are down or part of the network is not accessible. Guifi has a package called [Cloudy](http://cloudy.community/) that I would like to try.

**Automating the website**

The "join" form, map and monitoring software could all be integrated. We have worked on this but never implemented anything.



