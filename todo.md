# HackerNews-Podcast

Need to find a better name man

# Idea

- The user will be able to list to hacker news
- Python script
- [x] Scraps hacker rank posts including their articles
- [x] Then we feed it to an AI agent that will convert the posts to a podcast-like format where it summarizes the entire thing. (This is done to all posts within a week)
- [x] Then we send all the posts along with their podcasts into a mongo db database
- [x] The react application will then use this database to display the posts to the users.

## Improvements (High to Low Priority)

- [] Allow a summary of the articles instead of the entire article
- [] Use OPENAITTS
  - [] Store uuid with the python script
  - [] in the backend, when we receive a post request, download the MP3 file the store it in mongodb gridfs collection where the id is the UUID
  - [] Do something similar in the python backend
- [] Autoplay and stuff?
- [] Improve UI (Least priority)

### Deployment

- [] Create CRON JOB for agent (After the agent has been perfected)
