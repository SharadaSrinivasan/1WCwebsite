+++
# Project title.
title = "Progetto Neco"

# Date this page was created.
date = 2016-11-27T00:00:00

# Project summary to display on homepage.
summary = "Connects the citizens of a rural underserved town in **Italy**"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Europe", "Community Network"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = "europe_communitynetwork_progettonecocnitaly.md"

# Links (optional).
url_pdf = "europe_communitynetwork_progettonecocnitaly.pdf"
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.

# url_custom = [{name="Photos", url = ""}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 

[image]
# Caption (optional)
caption = "*Progetto Neco presentation at Vietri di Potenza, Potenza, Italy. Photo credit: Progetto Neco*"

# Focal point (optional)
# Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
focal_point = "Smart"

+++


Executive Summary 
==================

Progetto Neco is a project by a group of private citizens who created a
metropolitan area network (MAN) to bring "entry-level" Wi-Fi
connectivity to the urban center of Vietri di Potenza, Italy since 2008.
Progetto Neco uses 36 nodes on a point-to-point infrastructure network
to connect 230 families. In addition, following the completion of the
necessary infrastructure for the network backbone, Progetto Neco
expanded its services to include file and torrent sharing, voice over
Internet Protocol (VoIP) telephony, and a dedicated gaming server for
local area network (LAN)-type play. Progetto Neco is an example of a low
capital expenditure, nonprofit community network backbone that provides
connectivity and other services whose expansion is impeded by lack of
funds and manpower.

*Keywords: Wireless, community network, rural, Italy*

Context
=======

Potenza is the capital of the Potenza Province, which lies in the
southern Basilicata region of Italy. While there are a few
telecommunications providers in the area, their prices are relatively
high and the connection speeds range from 15-30 megabits per second
(Mbps). In 2015, while coverage of ultrafast 30 Mbps broadband amounted
to 43.9 percent, the coverage of ultrafast 100 Mbps broadband totaled 0.
Ultrafast broadband can be delivered both by fiber-to-the-home (FTTP) or
cable. Ultrafast 100 Mbps broadband is predicted to cover 20 percent of
the region by 2018 and 20.7 percent by 2020, while coverage for 30 Mbps
broadband is expected to reach 100 percent. The number of public Wi-Fi
spots has grown considerably in recent years as well to more than 5,000;
however, high prices and weak speeds leave the majority of households
and businesses with limited Internet use.

# Italy
|                                                      |                      |                                                            |                       |
|------------------------------------------------------|----------------------|------------------------------------------------------------|-----------------------|
|**Population (UN, 2015)**                             |61,142,221            |**Fixed broadband subscriptions (%)  (ITU, 2016)**          |                  25.43|
|**Population density  (people per sq.km) (UN, 2015)** |202.92                |**Mobile cellular subscriptions (%)  (ITU, 2016)**          |                 140.43|
|**Median household income (Gallup, 2006-2012)**       |US$ 20,085            |**Individuals using the Internet (%)  (ITU, 2016)**         |                  61.30|
|**Education  (Mean years of schooling)  (UNDP, 2013)**|Male: 10.6 Female: 9.7|**Individuals using the Internet by Gender (%) (ITU, 2016)**|Male: 65.7 Female: 57.2|

Project Description
===================

Progetto Neco was initiated by six private citizens, who in 2008, came
together to provide a nonprofit wireless network for the urban center of
the Italian city Vietri di Potenza ("Neco" being shorthand for network
community). They created a Metropolitan Area Network (MAN) because there
was no broadband at all when the project began -- the only available
connection was 56 kilobit analog technology. They imported bandwidth
from another city, where there was xDSL coverage (max 7 Mbps). At the
end of 2010, ADSL became available in Vietri di Potenza and they
subscribed, gaining seven xDSL lines and engaged in "channel bonding"
(ML-PPP) in order to get a single logic channel with 48 Mbps to share
with end users. As of late 2017, they received an upgrade in September
2017 from ASDL to VDSL2, so they currently have 250 Mbps connections.

Due the amount of traffic that the network can carry, they opted for
point-to-point infrastructure instead of a point-to-multipoint set up.
Each node has at least two radio interfaces, one to connect to the
network and a second or more to extend it to new nodes.

Technologically, Progetto Neco uses OpenWRT as an operating system for
the nodes, Linux for networking affordances, and OSLR as the routing
protocol. The initial investment and annual cost is approximately US\$
30,000 and in turn, Progetto Neco provides service to customers for US\$
120 a year.

# Project details
|                        |                         |                            |                             |
|------------------------|-------------------------|----------------------------|-----------------------------|
|**Technology**          |Wireless hotspots        |**Training**                |None                         |
|**Year program started**|2008                     |**Cost to users**           |US$ 120 per year per user    |
|**Geography**           |Rural – Vietri di Potenza|**Total cost of program**   |Operational cost:  US$ 30,000|
|**User profile**        |230 households           |**Associated organizations**|None                         |

Progress and Results
====================

Progetto Neco has been successful in its endeavor, and the network
continues to function -- with the organization functioning as a
nonprofit WISP for the community of Vietri di Potenza. In addition to
providing wireless hotspots, 230 households use the network to connect
to the Internet. Due to Progetto Neco's low price-point for service,
consumers save approximately US\$ 600 a year. In cases where a consumer
cannot afford to pay for the service, its nonprofit nature allows for
these customers to receive services for free.

Once the wireless network backbone was in-place, Progetto Neco expanded
its offerings to end users by exploiting the network's capabilities as
much as possible. These expansions include 2 terabytes for storing
files, along with indexes to make them shareable. Through the Ajaxplorer
web interface, users can listen to audio files, run other types of
media, and edit text documents uploaded by themselves or other users.
Users are able to use the Neco server for peer-to-peer (P2P) torrent
downloads, thereby freeing up disk space. In doing so, users can save
some wear-and-tear on their firmware as well as consuming less
electricity overall than in traditional P2P clients. Progetto Neco is
testing VoIP service to its users. When complete, each user will receive
an individual phone number and be able to make free calls.

Challenges 
==========

**Lack of resources --** The primary challenge for Progretto Neco at its
launch was a lack of funds. The organization was able to alleviate this
concern via donations from the founders; however, expansion is
impossible without outside funding or an angel donor. Skilled manpower
is also a challenge. Progetto Neco is unable to create network backbones
in other locations because they lack the voluntary labor needed for
setup and maintenance.

**Limited bandwidth capacity** -- Progetto Neco needs to re-use channels
for optimal spectrum utilization. Most of the channels are already
crowded by other WISPs, and spectrum squatting by other WISPs.

Progetto Neco's Suggestions for Future Projects 
===============================================

**Providing a proof of concept is a first step --** The MAN implemented
by Progetto Neco demonstrates a proof of concept. With a low capital
expenditures and willing volunteers, it is possible to construct and
maintain a nonprofit WISP over a small, metropolitan area. However,
scalability and sustained funding sources are required for long-term
success.

Sources 
========

Pitta, G. (2017, July 1) Personal Interview

Project website: <http://www.progettoneco.org/>
