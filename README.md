The purpose of this repository is to gather feedback from stakeholders about the feasibility of developing a platform to crowdsource statewide data regarding the availability of social services in local communities. We invite any and all interested parties to share their thoughts using [GitHub Issues](https://github.com/code4sac/social-services/issues) or by sending an email to [health@codeforsacramento.org](health@codeforsacramento.org?subject=Crowdsourcing Social Services Data). 

### BACKGROUND
The California HealthCare Foundation (CHCF) launched the California Health Data Project in March 2015 — a pilot program to encourage local communities statewide to use open health data from the California Health and Human Services Agency (CHHS) in tangible and relevant ways. There are three pilot projects running in Sacramento, Fresno, and Los Angeles.

The project is bringing together CHHS, local governments, and, most importantly, the community — service providers, civic technologists, and advocacy groups — to ensure this valuable information is finding its way into the hands of people and organizations that can put it to good use.

The Sacramento pilot project is led by Joel Riphagen and Ash Roughani, members of the Code for Sacramento Core Team. We held a Sacramento Health Data Roundtable meeting on May 4, 2015 to discuss current uses of health data in the region and explore opportunities to create additional value by leveraging the CHHS data portal. In addition, we’ve collected feedback from the community through two surveys and have met with some stakeholders individually. 

Working with the community, our mandate is to create and deploy at least one web application, visualization, or product using state health data by August 15, 2015 that not only benefits the local community, but can be deployed statewide.

### INTEREST IN SOCIAL SERVICES
A consistent theme that emerged from conversations in Sacramento (as well as Fresno and Los Angeles) pertained to the lack of openly available information regarding social services. Specifically, our communities have expressed strong interest in a web application that would allow users to query information about providers based on their location and specific need ([SMC Connect](https://www.smc-connect.org/) is an example of one possible implementation). It is our understanding that the Department of Social Services does not collect information about social service providers and, therefore, would not be able to publish that data to the state portal. 

While the creation of a statewide database that incorporates the needs of all stakeholders far exceeds the scope of this project, a potential opportunity exists to deploy a lightweight solution to crowdsource this data and publish it upstream to the state portal.

### OUR CONCEPTUAL SOLUTION
We envision a solution that consists of four components:
A web application that allows users to submit new or updated information about social service providers;
A process for approving and rejecting those submissions;
Publication of approved submissions to the CHHS Open Data Portal; and,
A web application for querying data about social service providers.

We believe this is an elegant solution because it leverages existing technology, could be deployed within two months, is a voluntary effort (as currently conceived), and would require minimal additional resources or expenditures. 

#### Web Application for Data Submission
To efficiently crowdsource the data, we believe anyone should be able to submit new or updated information about social service providers without the need to create an account. Form fields should be minimal, representing only the most critical information a user needs to find social services.

#### Approval Process
An approval process will help ensure data quality. Because this would require excessive resources at the state level, we propose that a lead agency within each county (e.g., Human Services Department, 211, United Way, etc.) designate an individual who can approve or reject submissions on a daily basis. This approval process should be quick and primarily is intended to weed out information that is clearly erroneous. Counties are best equipped to make these judgements and approval at the local level is an efficient allocation of the aggregate workload.

#### Publication to the Data Portal
Upon approval, each submission will automatically sync with a social services dataset in the CHHS portal. That dataset should include a disclaimer that the state is not responsible for the accuracy of the data, i.e., the state’s role in this effort is merely to provide a single database where information about local social service providers throughout the state may be stored. 

#### Web Application for Querying Data
To enable a consumer facing experience in accessing the data, we would develop and deploy a client-side web application from which users may query data from the state portal via its application programming interface (API). The web application would help consumers statewide find the services they need based on their location.

### NEXT STEPS 
There are many technical issues that will need to be resolved prior to deployment of this solution. However, we are working to reach consensus with stakeholders on the following principles upon which this project is based:
Data about social services data should be openly and freely available.
The CHHS data portal is an ideal data warehouse for counties store basic information about social service providers.
Participation in this program should be completely voluntary.
Crowdsourcing — while imperfect — is the fastest route to free social services data.
Approval of submissions is most efficiently accomplished at the local level.
Making the information available as quickly as possible is more important than conforming to a particular data standard.
If the project is successful, we can engage stakeholders in the future to conform the solution to a particular data standard.

If you would like to provide feedback on this conceptual proposal to crowdsource social services data, please [create an issue on GitHub](https://github.com/code4sac/social-services/issues) or send us an email at [health@codeforsacramento.org](health@codeforsacramento.org?subject=Crowdsourcing Social Services Data). 




