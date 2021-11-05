---
layout: default
title: Existing Dataset
nav_order: 3
---

# Acknowledgements & Introductions
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

Police officers regularly face no consequences for killing members of marginalized communities.   Hundreds have died at the hands of police in the last decade and nothing has been done about it.  Police institutions have a vested interest in maintaining their status a heavily armed domestic military force.  The government has a vested interest in maintaining status quo.  It is not surprising a publicly maintained, publicly accessible record of deaths resulting from police action or inaction does not exist for Canada.  But it is an abject failure on the part of Governance.  Some attempts have been made at compiling records.  But these disparate records are not mutually inclusive and cannot be easily cross referenced.

# Deadly Force

The most comprehensive publicly available dataset on police killings in Canada is the [Deadly Force database](https://newsinteractives.cbc.ca/fatalpoliceencounters/) was collected by the Canadian Broadcast Corporation (CBC).  Initially published in 2018, it was updated July 23, 2020.

## Lack of Access and Transparency

The CBC would not share their original dataset from the 2018 article that had location based information.  However, they had previously shared it with [Pivot Legal](https://www.pivotlegal.org/17_years_of_police_violence_in_canada).  I reached out to Pivot Legal, and they were willing to share it with me.


## The CBC Dataset is Highly Flawed

1) The CBC has not: disclosed the specifics of their methodology, defined what qualifies as a police killing or a police-involved death, or provided sources for their data.

2) The data are not regularly updated.  The dataset was initially published in [2018](https://newsinteractives.cbc.ca/longform-custom/deadly-force), but was not updated again for two and a half years. The updates coincided with media attention surrounding the Black Lives Matter protests in summer 2020, and to date the CBC has no plans of updating it further.

3) There are many missing/incomplete records in their data.

* The CBC database has missing incidents entirely, including: multiple shootings, tazings, and beatings, a death from a police dog, and [starlight tours](https://www.canadaland.com/podcast/the-police-4-starlight-tours/).  A starlight tour is when police abduct Indigenous individuals and drop them off in rural areas.  When done in the winter, some victims freeze to death.

* I asked the CBC why the starlight tour deaths of Rodney Naistus and Lawrence Wegner in January and February 2000 at the hands Saskatoon Police officers were not included in the database.
	* *"While their deaths were very likely a result of starlight tours by the Saskatoon police, they were not added to the database because there is no record of police officers picking them up. The inquests into their deaths were also inconclusive. Because of the lack of definitive proof, it was decided not to include them in the database."*

- Their response highlights why we cannot rely on a news corporation (especially one funded by the government) to collect and disseminate this type of information.

# What Other Information is Available?

## Killer Cops Canada

[Killercopscanada](https://killercopscanada.wordpress.com/) is a word press blog with posts reporting on police killings **and** police-involved deaths.  The blog was started in 2015, but some posts report on historical incidents including a few dating back to the early 1900's.  The blog is run by an anonymous user, thus far we have not reached out to them.  We have however, written some code to download the posts and parse them using keyword searches to compile them into an indexed dataset of records.


## la C.R.A.P

[la C.R.A.P.](https://www.lacrap.org/) is a francophone organization that maintains a list of police involved deaths dating back to 1987.  The list includes victims names and ages, the date of incidents and the "circumstances of the death" (Intervention, In-Custody, Suicide, and Inaction).  The list is grouped by city/province, with only the largest cities (Toronto, Montreal, Ottawa, Edmonton, and Vancouver) listed.  The list is posted on their website, and is not easily downloadable.  However, we have similarly used python to download and parse the list from their webpage.  We have yet to contact this organization either, but intend to reach out shortly.

## Georgia Straight

 ....

# Expanding the Dataset

## Validating and Updating

Using the Deadly Force dataset as a starting point, we have incorporated the killercopscanada data by cross referenced for matching records.  Adding the missing incidents and updating missing records in the CBC data.



, and Google Searches, I have stared compiling a new, more comprehensive database of Police-Involved Deaths.
* I have added all verifiable records from [Killercopscanada](https://killercopscanada.wordpress.com/) occurring after the CBC Deadly Force database ends (June 30, 2020).
* I have begun working backwards through the DeadlyForce database to fill in missing incidents and update missing records.  So far, I have found 53 police-involved-deaths that were left out of the CBC dataset.  
  * I have only just begun this part of the process, there are many more missing records to be added.



# Advocating for Accountability, Attributing Blame

As of 2017 (*2020 update does not include this information*), only 14 officers (3%) had been charged for a killing.  Regardless of whether an officer is charged with a crime, the departments involved are directly responsible for the deaths of these 634 individuals.


# Expanding the Dataset and Filling Gaps

The Deadly Force dataset does not capture the full picture.  We need a broader, more inclusive account of all deaths that are occurring as a result of interactions with police in Canada. 

### 1) Killings by off-duty & ex police officers
* Domestic violence rates among police families are [two to four](https://www.theatlantic.com/national/archive/2014/09/police-officers-who-hit-their-wives-or-girlfriends/380329/) times higher than they are in the general public.
  * At least four Canadian police have killed their partners since 2000 [1](https://www.thestar.com/news/2007/10/31/wills_found_guilty_of_murdering_mistress.html) [2](https://globalnews.ca/news/7643929/former-b-c-cop-granted-escorted-temporary-absences/) [3](https://www.cbc.ca/news/canada/ex-rcmp-officer-convicted-of-murder-1.305479) [4](https://www.cbc.ca/news/canada/edmonton/former-mountie-found-not-criminally-responsible-in-wife-s-death-1.1304062)
  * At least one death from a drunk off-duty officer striking a pedestrian. [1](https://killercopscanada.wordpress.com/2019/10/31/killer-cop-justin-holz-gets-30-months-for-killing-cody-severight-in-2017/)
  

### 2) Deaths from Negligence, Incompetence
* There are multiple incidents of deaths from police-involved car crashes. [1](https://www.cbc.ca/news/canada/montreal/man-dies-police-custody-puvirnituq-1.4091914) [2](https://barrie.ctvnews.ca/pedestrian-struck-and-killed-by-an-unmarked-opp-vehicle-in-midland-1.5124667?cache=) [3](https://www.bei.gouv.qc.ca/actualites/detail/mise-a-jour-concernant-levenement-survenu-a-mont-laurier-le-13-octobre-lidentite-du-civil-decede.html)
  * Including a [five year old boy](https://killercopscanada.wordpress.com/2018/12/15/killer-cop-patrick-ouellet-gets-8-months-for-killing-five-year-old-nicholas-thorne-belance/) who was killed by an officer in an unarmed vehicle going double the speed limit.
* [Falls](https://en.wikipedia.org/wiki/Death_of_Regis_Korchinski-Paquet) or suicides during police encounters are a frequent occurrence.

### 3) Deaths Occurring in Police Custody
* There are many records of individuals in police custody being denied or delayed medical care.
  * In one horrific case, an Indigenous man from [Baker Lake, NU](https://www.cbc.ca/news/canada/north/paul-kayuryuk-baker-lake-inquest-1.4231300) was found unconscious after suffering a stroke.  The police assumed he was intoxicated and kept him in a jail cell overnight.
* Suicides in police custody are [oftentimes preventable](https://www.theglobeandmail.com/news/politics/womans-death-in-custody-exposes-indigenous-policing-issues/article32694835/).
* Two men burned to death in a jail cell while being held for public intoxication at the [Kashechewan First Nation police detachment](https://www.cbc.ca/news/canada/kashechewan-fire-inquest-calls-for-more-funds-for-police-stations-training-1.819764).
