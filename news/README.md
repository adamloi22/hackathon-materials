# news data

This folder contains current affairs data.

## Terrorism

This dataset contains information about global acts of terrorism since 1970. `[gtd.zip]`

Fields:
- eventid
- iyear
- imonth
- iday
- approxdatw
- extended
- resolution
- country
- country_txt
- region
- region_txt
- provstate
- city
- latitude
- longitude
- specificity
- vicinity
- location
- summary
- crit1
- crit2
- crit3
- doubtterr
- alternative
- alternative_txt
- multiple
- success
- suicide
- attacktype
- targtype
- groupname
- motive
- nperps
- claimed
- weapontype
- nkills

## Global Database of Events, Language and Tone (GDELT)

This dataset is part of the GDELT project: 
    
    "The GDELT Project monitors the world's broadcast, print, and web news from nearly every corner of every country in over 100 languages and identifies the people, locations, organizations, themes, sources, emotions, counts, quotes, images and events driving our global society every second of every day, creating a free open platform for computing on the entire world." 
    
    `[gdelt_events.csv.zip]`

Fields:
- id
- date
- actor
- actorCountry
- actorGroup
- actorCode
- quadClass
- goldsteinScale
- numMentions
- numSources
- numArticles
- avgTone
- lat
- long


More information on fields: https://bigquery.cloud.google.com/table/gdelt-bq:gdeltv2.events
Source: https://www.gdeltproject.org
