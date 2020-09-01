+++

# Project title.

title = "Jakarta Smart City"

# Date this page was created.

date = 2016-11-27T00:00:00

# Project summary to display on homepage.

summary = "Providing E-Government services in Jakarta, Indonesia"

# Tags: can be used for filtering projects.

# Example: `tags = ["machine-learning", "deep-learning"]`

tags = ["Asia", "E-Government"]

# Optional external URL for project (replaces project detail page).

external_link = ""

# Slides (optional).

# Associate this project with Markdown slides.

# Simply enter your slide deck's filename without extension.

# E.g. `slides = "example-slides"` references 

# `content/slides/example-slides.md`.

# Otherwise, set `slides = ""`.

slides = ""

# Links (optional).

url_pdf = "asia_egov_jakartasmartcityindonesia.pdf"
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).

# Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.

# url_custom = [{name="Photos", url = ""}]

# Featured image

# To use, add an image named `featured.jpg/png` to your project's folder. 

[image]

# Caption (optional)

caption = "*Smart city data analysis cener in Jakarta.. Photo credit: Jakarta Smart City.*"

# Focal point (optional)

# Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight

focal_point = "Smart"

+++

Executive Summary 
==================

Jakarta Smart City (JSC) is a government initiative to develop a
multi-use, crowdsourced big data platform to close the digital divide
and facilitate data transparency and citizen communication with
government officials in Jakarta. The initiative includes a website,
smartcity.jakarta.go.id, as well as smartphone applications Qlue for
residents and CROP Jakarta for civil servants and officials.
Smartcity.jakarta.go.id uses the Google Maps engine and data from the
traffic application Waze. Qlue is a smartphone application through which
users can report incidents such as flood, crime, fire, or waste. City
officials respond to situations through the CROP Jakarta smartphone
application.

*Keywords: e-government, Indonesia*

Context
============

Indonesia signed the Open Government Partnership (OGP) Declaration as a
co-founder of the organization in 2011 and played a leading role in the
United Nations Sustainable Development Goals (SDGs), which reemphasized
the need for effective, accountable, and inclusive governance.

The country's National Long-Term Development Plan (2005-2025) set a goal
toward a "just and democratic, and peaceful and united" country, with a
"clean, effective, democratic, and reliable" government in the National
Medium-Term Development Plan of 2015-2019. In 2013, the Indonesian
government introduced the "One Data" initiative as a way to improve data
governance. A national data portal was established with 1,200 datasets
from various government agencies that the public can easily access.
Indonesia established the National Open Government Secretariat in 2015,
along with 694 Documentation and Information Management Offices to
handle request for information across the country, and a national online
complaint management tool that has attracted 300,000 users as of
September 2015 (OECD).

Several issues related to open data and open government hinder
Indonesia's progress. The underdeveloped open data ecosystem -- which
includes regulations on how data should be produced and managed, and the
limited open data advocacy that still focuses on "opening up data" only
without expanding to utilizing data to solve problems -- are two of the
major concerns.

# Indonesia

|                                                        |                       |                                                              |        |
| ------------------------------------------------------ | --------------------- | ------------------------------------------------------------ | ------ |
| **Population (UN, 2015)**                              | 255,708,785           | **Fixed broadband subscriptions (%)  (ITU, 2016)**           | 1.89   |
| **Population density  (people per sq.km) (UN, 2015)**  | 134.26                | **Mobile cellular subscriptions (%)  (ITU, 2016)**           | 149.13 |
| **Median household income (Gallup, 2006-2012)**        | US$ 2,199             | **Individuals using the Internet (%)  (ITU, 2016)**          | 25.40  |
| **Education  (Mean years of schooling)  (UNDP, 2013)** | Male: 8.1 Female: 6.9 | **Individuals using the Internet by Gender (%)  (ITU, 2016)** | N/A    |

Project Description
===================

Jakarta Smart City, started in 2015, provides new space for the
community to participate in the Jakarta's development through
applications and websites accessible via mobile phones. Through the Qlue
application, people can report problems for response by relevant
government agencies. Communities can also monitor the performance of
government officials through the website performance.jakarta.go.id or
report directly to the government via Short Message Service (SMS). In
addition to applications that provide reporting services to the
public, JSC also provides a platform for government officials to manage
all forms of community participation called Citizen Relationship
Management (CRM).

The Jakarta Smart City portal displays data that can be accessed by the
community. This portal is one of the government\'s efforts to realize
verified transparency by centralizing and integrating all data. It also
provides data for developers through api.jakarta.go.id, and works in
cooperation with start-ups such as Go-Good, Zomato, Trafi, and Google
Transit.

IBM Global Business Services helped the JSC team design a solution to
provide a big data hub for integrating information from the citizen
feedback application and social networks, as well as government services
such as transportation, healthcare, water distribution, and other
services. The solution uses IBM InfoSphere DataStage to extract,
transform, and load data from all these sources into a central data
platform, built on IBM BigInsights, and a powerful data warehouse, which
runs on IBM PureData System for Analytics. IBM InfoSphere Information
Governance Catalog provides a robust data governance framework, making
it easier to align the technical systems with the business requirements
and processes. As analysis tools, the solution provides IBM Cognos
Analytics for reporting and dashboarding, IBM SPSS Modeler for advanced
analytics and predictive modeling, and IBM Text Analytics for
categorization and sentiment analysis of unstructured text.

The project requires cooperation across the Department of
Communications, Informatics, and Public Relations, the Unit Manager
(local neighborhood government), and the Smart Governance system. JSC is
a linking system that facilitates community participation and government
responsiveness. The concept of a smart city in Jakarta is based on six
pillars: smart governance, smart people, smart living, smart mobility,
smart economy, and smart environment.

# Project Details

|                          |                                                              |                              |                                                              |
| ------------------------ | ------------------------------------------------------------ | ---------------------------- | ------------------------------------------------------------ |
| **Technology**           | Website and mobile/web applications for public reporting     | **Training**                 | N/A                                                          |
| **Year program started** | 2015                                                         | **Cost to users**            | Free                                                         |
| **Geography**            | Urban                                                        | **Total cost of program**    | Undisclosed                                                  |
| **User profile**         | 200,000 users Active social media users with high literacy levels,  20-40 years old | **Associated organizations** | Department of Communications, Informatics, and Public Relations IBM Go-Food Google Transit Trafi Waze Zomato |

Progress and Results
====================

Jakarta is a district of 10 million people divided into five cities, 44
sub-districts, and 267 villages. The city government receives an average
of 1,400 messages per day via its custom-built Qlue mobile application,
which allows users to submit feedback about public services. Citizens
send an average of 130 SMS messages per day to the governor's mobile
phone, and many more via other channels such as email and Twitter. JSC
also provides a big data platform that analyzes an average of 40,000
items of feedback per month.

Users of JSC's services typically tend to be well educated, actively
engaged with social media, and are between the ages of 20 and 40. JSC
has tried to reach a larger audience in a variety of ways. The
application developers regularly provide training and engage in media
outreach. Online, the JSC Implementing Unit publicizes through social
media channels using articles, photos, infographics, audio and video.
Offline, the team raises awareness through public figures and
participation in events and exhibitions. The public reporting system
incentivizes participation by gamifying the application, in which users
create avatars and score "points" for making reports, but still not many
people participate.

Self-monitoring and evaluation systems are in place within the project.
A major component of JSC is data analytics, which is used by the
government to make policy recommendations and by third-party application
developers. Monitoring and identifying the sustainability aspects of the
complaint information layer in the Jakarta Smart City portal through the
Monitoring Room is one form of community complaints management. JSC also
collects and analyzes the aspirations and complaints from the other six
channels by utilizing the social media functions of the Jakarta
Provincial Government. The management of community complaints was
conducted with effective coordination between the Jakarta Smart City
team and various government departments. The Jakarta Smart City
Management Unit conducts studies to monitor the performance of the
bureaucracy. 

Despite the technological and bureaucratic infrastructure in place, the
use of the application has fallen off sharply in the last year (there is
much less public reporting currently compared to a year before), and it
is not clear why. Some reasons for non-adoption may include lack of
awareness and lack of trust toward the government.

Challenges
==========

**Lack of interdepartmental communication --** Data management is
difficult because of the relative lack of communication between of the
different government departments, with a low degree of cooperation and
compatibility across them.

**Limited outreach --** The government tried to incentivize digital
reporting by neighborhood managers, but this quid pro quo model
incentivized false or irrelevant reports. The government used social
media to publicize and raise awareness, but this does not reach users
who do not already use social media.

**Limited familiarity by government officials** **--** The conventional
management styles of the government generate a resistance to innovation
and to new technologies to learn. Some government officials are still
not keen on using the application, and even though there are training
programs that target government officials, resistance still persists.

**Political change --** There is uncertainty over continuity of the
system owing to a change in local government in Jakarta. It is also
challenging to balance the provision of basic infrastructure and high
capacity infrastructure simultaneously, as political priorities often
dictate fund allocation.

**Citizen reluctance --** Citizens do not trust the government to be
responsive to their reports, and some officials do not trust public
reporting because they do not think citizens have any business directly
interfacing with the government.

JSC's Suggestions for Future Projects
=====================================

**Creating communication strategies to improve awareness --** In JSC's
experience, it is difficult to attract new users who are not ICT
literate by advertising exclusively online. The challenges faced by JSC
indicate a positive outreach strategy includes diverse channels and ways
to publicize the initiative and educate users.

**Providing more training to government officials --** JSC notes that
Government officials often require training in preparation for a new
style of interaction with the citizens, how to handle the reports that
users generate, and how to handle the new technologies used to generate
the reports.

**Enhancing communication for effective data management --** For optimum
data management, open communication between government departments,
between citizens and government, and with third-party developers (in
this case Qlue and IBM) is useful.

Sources
=======

Putri, D.A (2017, September 9) Personal Interview.

Project website: <http://www.smartcity.jakarta.go.id/>
