Each year, approximately 6.3 million companion animals enter U.S. animal shelters nationwide (ASPCA, 2022). Of those 6.3 million shelter animals, approximately 920,000 are euthanized annually (although, this number has declined within the past eleven years). While myriad shelters are not no-kill (and therefore, do euthanize animals past a certain time point), there are shelters in existence that are no-kill shelters and actively seek to try to do all they possibly can for an animal outside of euthanizing the animal.

One of these shelters is the Austin Animal Center (AAC) in Austin, TX. This shelter provides care and shelter to more than 18,000 animals annually and is also heavily involved in various activities and initiatives for the protection and care of abandoned, at-risk, or surrendered animals. The Austin Animal Center works with county, city, and state-wide parties on these efforts in an endeavor to better the lives and outcomes for those animals in need of care and a home.

Given the large number of animals residing in shelters, alongside the large number of those animals euthanized, finding rehoming solutions for animals and shelter pets in need is a critical and key issue for animal shelters across the nation. Even more so for those shelters that are no-kill shelters - given that they keep animals until they can be moved on to that next step of their lives, whether that be adoption, rehoming, shelter transfer, etc. Of course, and unfortunately, even at no-kill shelters, certain instances may exist in which an animal is euthanized due to being extremely sick or in extreme pain. Generally, however, this method is only proceeded with once all other potential methods have been considered or exhausted.

Solving this problem is imperative, and those who would most likely benefit from such an endeavor include the animals, people, facilities, structures, and institutions in the animal care sector/industry. Keeping pets off the streets and in good homes is imperative for the health and well-being of these animals. Additionally, their health and well-being has a ripple effect outwards towards all communities and institutions that serve animals or may be impacted (veterinary offices, animal control offices, animal shelters, public health offices, etc.).
Data, Data Dictionary, and Variables:

As a part of Austin, Texas's Open Data Initiative efforts, the AAC has made its data available for public use. To obtain the data, there are a few components: the data itself (collected and managed by the AAC), extracting that data (via the Open Data Portal's API and the use of a Socrata script, which is what the API is powered by), and then structuring that data in such a way within a Python pandas dataframe for usage.

The various tools and resources I will be utilizing to obtain the data for this project include:

    https://data.austintexas.gov/
    https://data.austintexas.gov/Health-and-Community-Services/Austin-Animal-Center-Outcomes/9t4d-g238
    https://gist.github.com/aschleg/54bf7ed55c2383f3ba1f338b8116a77b
    https://data.austintexas.gov/resource/hcup-htgu.json
    SODA - the Socrata Open Data API (SODA), which provides programmatic access to the dataset for use (https://dev.socrata.com/consumers/getting-started.html).

The analysis methods for this project include EDA as well as a machine learning model to predict animal shelter outcomes.
