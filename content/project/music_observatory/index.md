+++
# Project title.
title = "Music Observatory"

# Date this page was created.
date = 2019-07-30T12:00:00

# Project summary to display on homepage.
summary = "Collaborative reproducible research in the music industry"

# Tags: can be used for filtering projects.
tags = ["ceemid", "surveys", "music-industry", "observatory", "reprodubile-research"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/georgecushen"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = ""
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

An **observatory** is a location used for observing terrestrial or celestial events. The European Commission and the Council of Europe are supporting numerous data observatories to support research and development and evidence-based policymaking. (See: Observatories.)
We are creating automated observatories following the best practices of reproducible research.

Satellite Report grew out of a such an observatory, [CEEMID](https://ceemid.eu/). CEEMID is aiming to transfer thousands of indicators and a verifiable, open-source software that creates them to the European Music Observatory to give Europe-wide acces timely, reliable, actionable statistics and indicators for the music industry, policymakers and music professionals. (Read more about our [data coverage](https://documentation.ceemid.eu/index.php?title=Main_Page#Data_Coverage))

Satellite Report is aiming to support this transition, and at the same time, create new data products for other creative industries. See [our call for partners](http://demoobservatory.ceemid.eu/).

## Open source, open data, open collaboration

We believe that the European Music Observatory must rely on open-source statistical software written in the R statistical language like CEEMID. (Read [why](https://documentation.ceemid.eu/index.php?title=Open-source_software).)

In the EU, open data is governed by the [Directive on open data and the re-use of public sector information - in short: Open Data Directive (EU) 2019 / 1024](https://eur-lex.europa.eu/legal-content/EN/TXT/?qid=1561563110433&uri=CELEX:32019L1024). It entered into force on 16 July 2019. It replaces the [Public Sector Information Directive](https://eur-lex.europa.eu/legal-content/en/ALL/?uri=CELEX:32003L0098), also known as the ‘PSI Directive’ which dated from 2003 and was subsequently amended in 2013. The founder of CEEMID, Daniel Antal has been involved in Open Data and PSI since 2008.

CEEMID uses the open source [statistical programming language R](https://documentation.ceemid.eu/index.php?title=R_(programming_language)), and various open source R programs.  CEEMID also releases some of its customary program code developed to create its indicators (See [open data](https://danielantal.eu/project/opendata/) on this site). This allows an open collaboration with statisticians working in national statistics authorities and in independent research institutions in the EU and globally.  For example, this allowed us to compare test results on calculating economic impact indicators for the creative industries and other industries with the [UK statistical office](http://iotables.ceemid.eu/articles/united_kingdom_2010.html).

The use of open source software and the open source R statistical language allows a continuous peer-review of data ingestion, processing, corrections and indicator creation by statisticians, data scientists and academics.  Statistical products of national statistical offices, sometimes Eurostat itself, not to mention data providers that are not part of the system of national statistical offices, such as the European Audiovisual Observatory, are plagued with data errors that are corrected and amended relatively slowly.

## Data integration instead of centralisation

From the originally envisioned, centralized, permission-based data structure, due to practical considerations, CEEMID switched to a more flexible, decentralized approach. This approach is based on continuous [data integration](https://documentation.ceemid.eu/index.php?title=Main_Page#Data_Integration), which requires permissions to use business confidential information only in use. This allowed a rapid extension of CEEMID to the whole of Europe and go even beyond.  As a result of continous data integration it already includes hundreds of indicators foreseen in all pillars of the planned European Music Observatory. 

While CEEMID is aware of and uses the metadata of CISAC's, IFPI's, EAO's, and other industry sources' data, it does not contain this data, only when a user with permission for the use of these industry sources requires the integration of such data with other CEEMID data, or user-specific data.  While this approach makes sharing results more cumbersome, it provided a path to increase the number of useful indicators from a few dozens to around a thousand. Furthermore, it exponentially increases the value of CISAC's, IFPI's or EAO's data, especially when designing better royalty rates, or creating economic evidence for litigation. Take a look at a simple, non-confidential example [blog post](https://danielantal.eu/post/cee_mini_17/).

We will integrate data into open data products and music industry intelligence apps from the following sources:

* Nationally representative [CAP surveys](https://danielantal.eu/usecase/cap/) of music users and film viewers.

* Anonymous [CEEMID Music Professional Surveys](https://danielantal.eu/usecase/musicians/) and *CEEMID Audiovisual Professional Surveys* about their work, incomes and costs. See example [blog post](https://danielantal.eu/post/career_path/).

* Big data sources from various geolocational applications about events and location visits [small video](https://www.youtube.com/watch?v=3lW8bhQ2fbY).

* Automatic data retrieval from open data sources, including statistical data and EU-funded research. See example [blog post](https://danielantal.eu/post/how_many_ever_pay/)