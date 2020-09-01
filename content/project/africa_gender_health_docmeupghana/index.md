+++


title = "DocMeUp"

# Date this page was created.

date = 2017-11-27T00:00:00

# Project summary to display on homepage.

summary = "Improving maternal mortality outcomes in **Ghana**"

# Tags: can be used for filtering projects.

# Example: `tags = ["machine-learning", "deep-learning"]`

tags = ["Africa", "Health", "Gender"]

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

url_pdf = "africa_gender_health_docmeupghana.pdf"
url_slides = ""
url_video = "https://www.youtube.com/watch?v=dH3LVvjIRBo"
url_code = ""

# Custom links (optional).

# Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.

# url_custom = [{name="Photos", url = ""}]

# Featured image

# To use, add an image named `featured.jpg/png` to your project's folder. 

[image]

# Caption (optional)

caption = "*Women at a session for DocmeUp. Photo credit: DocmeUp Project*"

# Focal point (optional)

# Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight

focal_point = "Smart"

+++


Executive Summary 
==================

Since 2013, the DocmeUP project has implemented pilot programs to offer
better prenatal healthcare to pregnant women in rural Ghana. Their first
project involved providing mobile ultrasound scans that reached nearly
400 Ghanian women. Their current project, launched in June 2017, also
focuses on prenatal care. This time, however, instead of ultrasounds,
DocmeUP is providing glucometers to test for diabetes in pregnant women.
DocmeUP is an example of a public health intervention impeded by lack of
funds and an overzealous bureaucracy.

*Keywords: mobile phones, mhealth, antenatal care, portable ultrasound,
rural, Ghana*

Context
=======

Since 2008, all women in Ghana are eligible to receive free maternal
health care. The Free Maternal Health Care Initiative, which receives
funding from the National Health Insurance Fund, provides subsidized
health insurance to pregnant women. The initiative gives them access to
various insurance benefits, including antenatal care (ANC), childbirth,
caesarean section, management of emergency obstetric conditions, and
postnatal care, with some exceptions such as ambulance services and
postpartum family planning counseling offered by UNICEF.

Despite those benefits, the maternal mortality rate (MMR) in Ghana in
2015 was 319 per 100,000 live births, much higher than the world's
average of 216 according to the World Bank. Poor quality of ANC is
suggested as the major contributing factor for this issue. Moreover,
hemorrhaging is the largest single cause of maternal death in Ghana,
leading to almost 24 percent of deaths.

Research suggests that most Ghanaian women are not receiving the full
benefits of ANC. Although most women visited a health facility at least
once during pregnancy, not all of them visited four times or more as
recommended by the World Health Organization (WHO), and only a fourth
received all nine ANC services across all visits. Little is known about
whether they are informed of, have access to, and utilize the available
prenatal care applications.

# Ghana
|                                                      |                     |                                                            |      |
|------------------------------------------------------|---------------------|------------------------------------------------------------|------|
|**Population (UN, 2015)**                             |26,984,328           |**Fixed broadband subscriptions (%) (ITU, 2016)**           |  0.31|
|**Population density (people per sq.km) (UN, 2015)**  |113.13               |**Mobile cellular subscriptions (%) (ITU, 2016)**           |139.13|
|**Median household income (Gallup, 2006-2012)**       |US$ 2,050            |**Individuals using the Internet (%) (ITU, 2016)**          | 34.70|
|**Education  (Mean years of schooling)  (UNDP, 2013)**|Male: 8.1 Female: 5.9|**Individuals using the Internet by Gender (%) (ITU, 2016)**|N/A   |

Project Description
===================

DocmeUP pilot project was initiated by a group of academics at ETH
Zurich, African Institute for Mathematical Sciences, and Instituto
Italiano di Technologia with the aim of increasing number of ANC visits,
reducing home deliveries, and supplementing care given by ANC clinics
through low-cost mobile phones and portable ultrasound scan machines.
The pilot project aimed to address the problem that most pregnant women
in rural communities in low-income countries do not fulfill the minimum
recommended visits by The World Health Organization and deliver without
skilled attendants.

Between April 2014 and February 2015, DocmeUP ran its pilot program in
the Central Region of Ghana. The communities were chosen among those
between the city of Cape Coast and Accra to facilitate the trips of the
ultrasound technicians. Each community was located to a clinic at
varying distances, ranging from none to 5 or 10 km. In addition, while
some were well connected to major cities, some were isolated.

It deployed remote ultrasound technology and an online managing system
for the ultrasound and patient data, to rural communities. Two
ultrasound technicians from a local teaching hospital were trained over
a two-month period. In addition, the pilot included five community
health workers (CHW) -- a trusted woman in each served community -- who
acted as a liaison between the pregnant women and the medical
professionals at the remote site. The CHWs were given low-cost, general
packet radio service (GPRS)-enabled mobile phones (Nokia ASHA 206). As
they were in direct contact with the women, their responsibilities were
extensive. Some of these duties included making community members aware
of the deployment, explaining the utility of this prenatal care and the
importance of hospital birth delivery, registering pregnant women and
sending information via the mobile application to a centralized online
location. CHWs were also expected to check on the women every two weeks
and track whether or not they were keeping to the agreed upon prenatal
schedule.

The online management system used by the program was divided into server
and client sides. The server side gave access to aggregated and
individual data and could collate reports. The client side was based on
an application called DocmeUP, which had two main modules: "Register a
Pregnancy" and "Visit and Case." The former is self-explanatory; the
second module allowed CHWs to report health concerns faced by the women,
and gave three possible solutions -- "recommend counseling," "requires
assistance within 24 hours," or "requires emergency referral
immediately." Ultrasounds from women in the program were transmitted to
gynecologists for analysis and immediate feedback.

The first pilot cost approximately US\$ 20,000 to conduct, which was
funded through a grant. In 2017, DocmeUP has initiated a second pilot,
which is similar to the previous iteration with the exception of
replacing ultrasounds with glucometers due to cost constraints. This
pilot also costs approximately US\$ 20,000.

# Project Details
|                        |                                                                     |                            |                                                                                                          |
|------------------------|---------------------------------------------------------------------|----------------------------|----------------------------------------------------------------------------------------------------------|
|**Technology**          |Low-cost mobile phones connected to portable ultrasound                            |**Training**                |Several hours over three months                                      |
|**Year program started**|2013                                                                |**Cost to users**           |Free                                                                                                      |
|**Geography**           |Rural  districts in central Ghana                                                         |**Total cost of program**   |Fixed cost: US$ 40,000 Operational cost: US$ 5200 ; 5 regular volunteers|
|**User profile**        | 323 pregnant women |**Associated organizations**| Institute of Mathematical Sciences, ETH-Zurich, African Network Information Center, AMS Ghana            |

Progress and Results
====================

In the first pilot, CHWs registered and followed 323 pregnancies. They
used the client side of the DocmeUP module to inquire about danger signs
339 times. Ultrasound exams were conducted on 122 women, including 60
who gave birth during the project. In some cases, these ultrasounds were
able to make the women/healthcare providers aware of issues such as
ectopic pregnancies and breech-births. Also, following the instructions
of the mobile phone app, some women were encouraged to take Hepatitis B
tests. Three of these tests were positive.

Overall, data from the pilot shows that the deployment lessened the
signs of dangerous pregnancy to levels lower than before the
implementation. Furthermore, there was a statistically significant
increase in the number of women taking advantage of prenatal care and
the number of hospital deliveries. DocmeUP had a successful pilot, but
was unable to receive enough governmental and funding interest to
initiate a countrywide rollout. Their current pilot, which replaces
ultrasound technology with glucometers, is expected to have more support
due to the significantly lower cost of a national rollout.

Challenges
==========

**Social norms --** Some of the women in the community where the pilot
was deployed refused to enroll in the program due to pressure from their
husbands or the local traditional herbalist.

**Community resistance --** Receiving ethical approval from the
requisite bodies to run the pilot project in Ghana was complex. Similar
projects should expect as long as a year to go through necessary
paperwork and get permissions from the officials to initiate such a
project.

**Lack of transportation infrastructure --** Many women live a far from
a location where they could receive suitable prenatal care. In addition,
because many family members rely on their income, travelling far
distances for care is unrealistic because they simply cannot afford to
miss a day of work.

**Lack of sustained funding --** The pilot could only include a
relatively small number of participants due to the general lack of
funding for the deployment. In addition, the only institutional support
DocmeUP has received has come from universities. No other bodies have
been willing to contribute to expand the size of the pilot, apart from
support and a monetary prize from the African Network Information Center
(AFRINIC) and the African Internet community. The cost of the ultrasound
project is quite high, which is why DocmeUP's second initiative switched
to glucometers.

DocmeUP's Suggestions for Future Projects
=========================================

**Engagement with community members helps build trust --** When DocmeUP
was interested in launching its first pilot, they met with local
community leaders to receive their blessing, which encouraged women to
take part in the program. By training trusted, local women as CHWs, the
project was able to dispel some of its outsider quality. Moreover,
because these women worked on a voluntary, no-pay basis (their duties
were seen as contribution to their own community), a nationwide rollout
may not be very costly.

**Sustained funding source required for long-term viability --**
DocmeUP's experience indicates that without the support of the
government, any type of wide-scale implementation of this project is
difficult. Similarly, without a considerable funder, launching larger
pilots is also a challenge.

Sources
=======

Crimi, A. (2017, August 2) Personal Interview.

Project website: [www.docmeup.org](http://www.docmeup.org/)

Project videos:

<https://www.youtube.com/watch?v=dH3LVvjIRBo&feature=youtu.be>

<https://www.youtube.com/watch?v=pR7B-KSaUWc>

Amoah, B., Anto, E. A., Osei, P.K., Pieterson, K., & Crimi, A. (2016).
Boosting antenatal care attendance and number of hospital deliveries among pregnant women
in rural communities: A community initiative in Ghana based on mobile phones applications and portable ultrasound scans. BMC Pregnancy and Childbirth,16(1), 141. Available at: <https://www.ncbi.nlm.nih.gov/pubmed/27301244>.
