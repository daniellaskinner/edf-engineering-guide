// to-do: make this less detailed and less EDFfy

# Hi from the Small Business Acquisition and Retention Team

We reside within the Small Business Tribe in the Solutions and Automation area at EDF. We currently have three sibling teams in the Small Business and Commercial Tribe, which are:

- Small Business Service
- Propositions & Commissions
- Data Enablement

## Purpose

- We take care of two applications that help EDF sell energy to small business customers. I tend to think of independent pubs, hairdressers and MMA gyms :D
- Those two applications are:
  - [Midas](https://prod-sme-quote.pri.cus-sme-common.aws.edfcloud.io): an internal web app that salespeople at EDF use to ring up small businesses to sell them energy quotes
  - [Quote and Buy](https://www.edfenergy.com/quote-small-business): a public facing web app that the small businesses themselves use to generate an energy quote

### Current Work

- We're currently focussing on creating a shared serverless API for both applications, as they have a lot of the same domain concerns. For example, both apps need to enable the user to run a credit check on the small business in question by leveraging a third party credit checking service called Experian.
- Midas-side, we're also enabling our salespeople to make quotes to small businesses who are already existing EDF customers. This is called retention quoting and enables EDF to continue generating revenue from the same customers.

## Products & Services

- Midas
  - [Front end repo](https://github.com/edfenergy/cus-sme-common-quote-front-end)
  - [Back end repo](https://github.com/edfenergy/cus-sme-common-quote-back-end)
- Quote and Buy
  - [Front end repo](https://github.com/edfenergy/cus-chnnls-sme-common-acquisition-web)
  - [Back end repo](https://github.com/edfenergy/cus-chnnls-sme-common-acquisition-api)

## Tech Stack

![React](https://img.shields.io/badge/React-100000?style=flat&logo=react&logoColor=lblue)
![TypeScript](https://img.shields.io/badge/TypeScript-100000?style=flat&logo=typescript&logoColor=blue)
![GraphQL](https://img.shields.io/badge/GraphQL-100000?style=flat&logo=graphql&logoColor=yellow)
![Jest](https://img.shields.io/badge/Jest-100000?style=flat&logo=jest&logoColor=green)
![Playwright](https://img.shields.io/badge/Playwright-100000?style=flat&logo=playwright&logoColor=blue)
![Terraform](https://img.shields.io/badge/Terraform-100000?style=flat&logo=terraform&logoColor=lpurple)
![DynamoDB](https://img.shields.io/badge/DynamoDB-100000?style=flat&logo=dynamodb&logoColor=lblue)
![AWS Lambda](https://img.shields.io/badge/Lambda-100000?style=flat&logo=awslambda&logoColor=orange)
![AppSync](https://img.shields.io/badge/AppSync-100000?style=flat&logo=appsync&logoColor=lblue)

## Ways of Working

- We currently use Scrum and have a 90 minute refinement twice a week.
- We inspect our ways of working both on an ad-hoc basis, and regularly in a once per fortnight ways of working session and sprint retrospectives.
- We rotate who's the scribe for each refinement
- We start a new sprint fortnightly on a Tuesday
- Anyone can add a story, bug or spike to the sprint backlog as long as it's ok with Claire the Product Owner
- We do quizzes and brain teasers during the daily scrum
- We have a weekly social call on a Friday afternoon just to hang out!

### How we Point Tickets in Refinement

We give story points to user stories and bugs, but not spikes. The pointing system we use is Fibonnacci numbers.

**1** - a change involving no logic like a text change.
**2** - a small change in one area of the codebase (i.e just the back end) involving some logic
**3** - a smallish feature involving both front end and back end.
**5** - medium feature involving both front end and back end.
**8** - complex feature involving both front end and back end.
**13** - break it down into smaller stories

## Communication

### Team Members and their Favourite Foods

- [Evie Skinner: software engineer](https://www.linkedin.com/in/evie-skinner-0bb389127/) `eveline.skinner@edfenergy.com` :curry: :goat:
- Claire Wadey: product owner `claire.wadey@edfenergy.com` :chocolate_bar:
- Ashleigh Jones: scrum master `ashleigh.jones@edfenergy.com` :turkey: (roast dinner!)
- Will George Stevens: solution specialist `will.georgestevens@edfenergy.com`
- Ben Chipperfield: product specialist `ben.chipperfield@edfenergy.com`
- Jon Earl: senior software engineer `jon.earl@edfenergy.com`
- Phil Duffy: software engineer `phil.duffy@edfenergy.com` :taco:
- Gus Charles: software engineer `gus.charles@edfenergy.com` :hamburger:
- Anne-Laure Figer: software engineer `anne-laure.figer@edfenergy.com` :rice: :cake:
- Leslie Isah: UX desginer `leslie.isah@edfenergy.com`
- Alan DeBell: lead software engineer `alan.debell@edfenergy.com` :wine_glass: :spaghetti: :cake:
- Daniel Waddington: software engineer (Accenture) `daniel.waddington@accenture.com` :spaghetti:
- Ajay Viswanathan: software engineer (Accenture) `ajay.viswanathan@accenture.com` :dumpling: (dosa!)
- Alex Roberts: software engineer (Accenture) `a.a.roberts@accenture.com`
- Rajen Saha: solution specialist (Accenture) `rajen.b.saha@accenture.com`

### How To Interact

Don't hesitate to drop any one of us a line via Slack or email. You can also find several of us active in the [Sustainability in Tech CoP](https://edfuk.atlassian.net/wiki/spaces/CSG/pages/941949525/Sustainability), [Security CoP](https://edfuk.atlassian.net/wiki/spaces/CSG/pages/557616291/Cyber+Security+Community+of+Practice), [Women+ in Data and Tech Network](https://edfenergynnb.sharepoint.com/sites/Diversity-and-Inclusion/SitePages/EDF-Women+-Data-and-Tech-network-%E2%80%93-relaunch-event-EDF-Women+-Data-and-Tech-network-%E2%80%93-relaunch-event-Manz,-Bev.aspx), and [LGBT+ Supporters' Network](https://edfenergynnb.sharepoint.com/sites/Diversity-and-Inclusion/SitePages/Diversity-and-Inclusion---The-LGBT-Supporters-Network.aspx).

## Organisation

### Company Structure

Put simply (hopefully!):

    EDF  > Customers > 
        Retail > Solutions and Automation (Mark Askew) > 
            Small Business and Commercial Tribe (Gemma Willcocks) >
             our team

### Teams We Work With

- Propositions & Commissions (AKA "The Teller Team") - contact Tim Bishop `tim.bishop@edfenergy.com`
- Small Business Service (AKA "The Service Team") - contact Abdi Ahmed `abdisamed.ahmed@edfenergy.com`

## Documentation

- [Midas and Quote and Buy interaction](https://edfuk.atlassian.net/wiki/spaces/NS/pages/1174078499/Midas+Access+to+Quote+Buy)
- [Midas (also known as SME Quote) Confluence page](https://edfuk.atlassian.net/wiki/spaces/SQNS/overview?homepageId=513967555)
