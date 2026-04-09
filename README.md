# Bunnybook 

## A Social Network Website (for bunnies), built with FastAPI and React+RxJs.

<kbd>
  <img src="https://user-images.githubusercontent.com/19171248/131324206-1f97c51b-7192-4e62-8619-abde46aea5b6.png"/>
</kbd>

<div>&nbsp;</div>

Included features:
- :speech_balloon: chat
- :red_circle: online/offline friends status
- :abcd: "Is typing..." indicator
- :two_men_holding_hands: friend requests and suggestions
- :bell: notifications
- :postbox: posts
- :pencil: comments
- :scroll: conversations history
- :rabbit2: random profile picture generation
- :lock: authentication

Tech stack:
- :snake: Python 3.8 + FastAPI
- :notebook_with_decorative_cover: PostgreSQL 13 + async SQLAlchemy (Core) + asyncpg driver
- :link: Neo4j graph db for relationships between users and fast queries
- :dart: Redis for caching and Pub/Sub
- :zap: Socket.IO for chat and notifications
- :key: Jwt + refresh tokens rotation for authentication
- :whale: Docker + docker-compose to ease deployment and development  

<br/>


## Scope of the project
**What Bunnybook is**: I created Bunnybook to have the opportunity to experiment with some technologies I wasn't familiar with . I love learning new ways to solve problems at scale and a small social network seemed a very good candidate to test a few interesting libraries and techniques.  
<br/>
**What Bunnybook isn't**: a production-ready social network with infinite scaling capabilities. Building a "production-ready social network" would require way more testing and refinement (e.g. some features scale while others don't, test coverage is not complete, chat is hidden in mobile-mode and the entire project is not particularly responsive etc.), but this is out of the scope of this small experiment.




