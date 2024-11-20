# Data Dictionary

MoMA data from [Kaggle](https://www.kaggle.com/datasets/ugowda/the-museum-of-modern-art-moma-collection)

Art History Textbook data from [Kaggle](https://www.kaggle.com/datasets/joebeachcapital/art-history?select=artists.csv)

## MoMA Raw Data

| field | type | description |
| ----- | ----------- | -------------- |
| Title | object | title of artwork |
| Artist | object | name of the artist (multiple artists listed for some artworks) |
| ConstituentID | object | ID number for artwork |
| ArtistBio | object | the artist's birthplace and birth year/year of death |
| Nationality | object | the artist's nationality |
| BeginDate | object | the artist's birth year |
| EndDate | object | the artist's year of death |
| Gender | object | gender of the artist (multiple genders listed for artworks by multiple artists) |
| Date | object | date of the artwork |
| Medium | object | medium used to complete the artwork |
| Dimensions | object | the dimensions of the artwork |
| CreditLine | object | who funded or gifted the artwork |
| AccessionNumber | object | the cataloged number for the artwork |
| Classification | object | the classification of the artwork |
| Department | object | the department for the artwork |
| DateAcquired | object | the acquisition date for the artwork |
| Cataloged | object | Y/N for whether or not the artwork is cataloged |
| ObjectID | int64 | the object id for the artwork |
| URL | object | the URL for artwork and corresponding information |
| ImageURL | object | the image URL for the artwork |
| OnView | object | the location of the artwork in the museum |
| Circumference (cm) | float64 | the circumference of the artwork |
| Depth (cm) | float64 | the depth of the artwork |
| Diameter (cm) | float64 | the diameter of the artwork |
| Height (cm) | float64 | the height of the artwork |
| Length (cm) | float64 | the length of the artwork |
| Weight (kg) | float64 | the weight of the artwork |
| Width (cm) | float64 | the width of the artwork |
| Seat Height (cm) | float64 | unknown/blank column |
| Duration (sec.) | float64 | duration of the audio/video/digital artworks |

## MoMA Clean Data
| field | type | description |
| ----- | ----------- | -------------- | 
| title | string | title of artwork |
| artist | string | name of the artist (multiple artists listed for some artworks) |
| date_acquired | datetime64 | acquisition date for the artwork, format is YYYY-MM-DD |
| gender_list | string | the artist's gender (separate rows for artworks by multiple artists) |

## Art History Textbook Raw Data
| field | type | description |
| ----- | ----------- | -------------- |
| artist_name | string | name of the artist |
| edition_number | 

## Art History Textbook Clean Data

| field | type | description |
| ----- | ----------- | -------------- |
| artist_name | string | name of the artist |
| artist_gender | string | gender of the artist |