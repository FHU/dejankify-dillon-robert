# Wildcard Deployment Reflection

> **Note:** Rename this file to match the service you used (e.g., `RENDER.md`, `RAILWAY.md`, `NETLIFY.md`, `HEROKU.md`).

**Service Used:** <!-- Railway -->  
**Team Members:** <!-- Robert Smith -->

---

## 1. Deployment Process Overview

Describe the steps you took to deploy the Dejankify app to your chosen platform. Why did your
team choose this service? Walk through the deployment process end-to-end — how did you
configure the project, connect your repository or push your image, handle environment
variables, and verify the app was running correctly?

<!-- Write 1–2 paragraphs here -->

I chose Railway becuase of its high reviews and ratings from others, another reason was becuase it did dockerization on the platform itself, so I thought I wouldnt need to worry about changing the dockerfile. This was the second platform that we had deployed to so I didnt do any of the docker stuff for this project. However I did have to write the dockerfile for the first deployment, and it was here for this one too. The deployment process consistied of connecting my repo, putting in the secrets to Railway and then creating the URL for the site. To verify if it was working I just went throught the app as normal, and all the features were working.

## 2. Pros and Cons

Based on your hands-on experience, what are the strengths and limitations of this platform?
How does it compare to Vercel and your containerized deployment? Consider factors like ease
of use, flexibility, documentation quality, free tier generosity, and whether you would
recommend it to another developer.

<!-- Write 1–2 paragraphs here. You may use a list to organize pros/cons if helpful. -->

Railway was very easy to deploy to I had almost no issues from the platform its self. The only issue that I ran into was giving the app on github permission to my repo, other than that everything else was fine. The UI was a little weird, and sometimes it was hard to find things on the app, but overall nothing too difficult.

## 3. Challenges and Surprises

What did you find unexpectedly difficult, confusing, or interesting about deploying to Vercel?
This could be something that didn't work as expected, a configuration quirk you had to work
around, something that impressed you, or something you wish you had known going in.

<!-- Write 1–2 paragraphs here -->

The only problem that I had was giving permissions to the app on github so it had acess to the repo. There was nothing else that gave me trouble deploying to Railway.