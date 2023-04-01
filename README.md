# InstaLaw

This repo contains the topics of study and timeline
---
## Topics
### Frontend
1. **Tailwind CSS**
2. **React**
3. MixPanel (behavior logging)
4. Hotjar (cursor track heatmap)
### Web Server
1. **NodeJS**
2. ngineX
### Backend
1. **Python**
2. **Django**
  - [Django + Postgres + CLoud SQL](https://dragonprogrammer.com/connect-django-database-cloud-sql/)
  - [Django Backend API + Docker](https://dragonprogrammer.com/dockerized-django-api-angular-tutorial/)
  - [Postgres + Django](https://www.enterprisedb.com/postgres-tutorials/how-use-postgresql-django)
  - [Benefit of Docker for Django](https://www.foadlind.com/articles/benefits-of-using-docker-for-django-projects.html#:~:text=With%20Docker%2C%20not%20only%20are,a%20different%20OS%20than%20you.)
3. **GCP**
4. Presto DB
### Third Party
1. Sendgrid (email API)
---
# Milestone
Topline milestone:
> **2023/5/1 Start testing end-to-end with selected lawyer groups, using MVP**
## Timeline
| Goal                             | Details                                                | Target Date |
|----------------------------------|--------------------------------------------------------|-------------|
| Complete Ramp Up                 | Complete knowledge and ownership transfer from Honglei | 4/9/2023    |
| Finish User Flow                 | See *User Feature* for all items to develop            | 4/16/2023   |
| Finish Lawyer Flow               | See *Lawyer Feature* for all items to develop          | 4/23/2023   |
| Cleanup User Experience          | Fix bugs and hickups from previous two milestones      | 4/30/2023   |
| Onboard Real Lawyer Data         | Add real lawyer data and make sure they can be displayed properly (and accurately if time allows) to users | 5/7/2023    |
| Real user tests and collect data | Launch full service for all users online to test       | 5/14/2023   |
| Improve matching and chat engine | Enhance matching quality and GPT chat quality          | 5/21/2023   |
| Improve metrics and monitors     | Enhance metrics on site interaction and conversion process | 5/28/2023   |
### User Features (Priority order)
- [ ] Change the last info collection step to option view for lawyer selection, based on preference
- [ ] User auth and personalized dashboard (all existing case and lawyer status history)
- [ ] Notify users if lawyer accpets (include quote and message response), ask if they accept

### Lawyer Features (Priority order)
- [ ] Lawyer portal (see all existing leads and status), set preference (price, types of clients) as well
- [ ] Lawyer notification if selected selection
- [ ] Lawyer payment
- [ ] Pass lawyer response to users (accept, rejected, and custom messages)
- [ ] Lawyer metrics weekly update
