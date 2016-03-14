---
layout: post
category : Reflections
tagline: "Business Canvas Model"
author: Syed Shahzeb Hasnain
tags : [Reflections, Stack Overflow: The Architecture, Nick Craver]
---
# Stack OverFlow Architecture
Nick Craver wrote an informative blog on some of the interesting facts about Stack Overflow's hardware and software architecture. Stack Overflow is run on 4 sql servers, 11 IIS webservers, 2 redis servers and 3 tag engine servers. Now, in the cloud computing world, why hasnt a site thats successfull, has millions of unique hits daily and requires these many servers to run doesnt move to cloud service architecture. This wasnt possible because this would yeild monthly cost of more than millions per month. 
## Interesting Facts
1. Although using .Net as their core architecture, a lot of open source libraries are also incorporated.
2. SQL and NoSQL servers run hand in hand in their architecture.
3. REDIS servers have 256 GB of RAM !!!!!
4. Having such an intense and fault tolerant architecture, they still use CloudFlare service because they have servers across the globe.
5. It takes only 8.8ms average to load the front page and 19.12 ms to load the question pages. This shows how far technology has come in terms of performance to cost ratio.

--->> This post is inspired from http://nickcraver.com/blog/2016/02/17/stack-overflow-the-architecture-2016-edition/ 

--> https://trello.com/b/0zgQjktX/blog-post-queue-for-stack-overflow-topics