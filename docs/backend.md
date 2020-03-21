# Backend 

###### tags: `Brainstorming`, `Research`, `Development`

## Platform
* AWS Lambda
* AWS Aurora
* GitHub: https://github.com/vinzBad/Bee2Bee_backend
* Python
* REST-API, spec'd with https://swagger.io/

## Research
### (Backend) Skills in Team
* Node.js ✓✓
* AWS ✓✓✓
* GCloud ✓✓
* MySQL ✓✓
* PostgreSQL ✓✓
* C# ✓
* Java ✓✓
* Scala ✓
* JavaScript ✓✓
* Cassandra ✓
* Python ✓✓✓
* C++ ✓
* Kotlin ✓
* Go ✓
## Design Considerations
* Fast onboarding for new users
    * Good documentation
* Frontend needs an easy way to interface with Backend
* Hosting on Linux Server or some other AWS Product
* Need atleast one person with experience in chosen backend technology
    * Help with onboarding
    * Best Practices
*  


## Proposals
### Python Backend - Vinzenz Sinapius
[Django REST](https://www.django-rest-framework.org/) with [drf-yasg](https://github.com/axnsan12/drf-yasg)

Pro:
* established framework
* lots of features included -> faster prototyping
* With openapi spec from drf-yasg we can auto generate the frontend code for the app

Con:
* Not much experience
* Performance?

## API Def Ideensammlung


### Endpoints
#### V0
* User [Register, Login, ]
* Unternehmen [Create, ]
* Bedarf [Create(PLZ, Ort, AnzPersonen, freitext Skills); ]
* Bestand [] 
* Location [GetBedarfe(lon,lat,radiusInKM,type(angebote/bedarfe),)]

#### V1
* User+Auth (tbd api key): Client hat festen API Key, User bekommt nach login session Key
* Skill


## Database Relations
Unternehmen <-> User
User <-> Skill