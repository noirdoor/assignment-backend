# assignment-backend

> Interview assignment for backend engineers

This project is designed to help you understand what working at [Chords](https://chords.io) is like, with a realistic set of problems that are relevant to our product. It also affords us some common ground to discuss candidates.

The guidelines are relatively open-ended. We want you to use the time to showcase your passions, skills, and experience.

## Goal

You will create a server with a database connection that is robust and self-healing in the face of failures.

## Tools

These are just a few of the things you will use during the project:

**Tool** | **Purpose**
-------- | -----------
[GitHub](https://github.com/) | Source code storage and version control
[hapi](https://hapijs.com/) | Node.js framework for creating web servers
[Inert](https://github.com/hapijs/inert) and/or [Vision](https://github.com/hapijs/vision) | Render pages on the server

**You choose the database.** Some reasonable options are [RethinkDB](https://rethinkdb.com/), [PostgreSQL](https://postgresql.org/), [CockroachDB](https://cockroachlabs.com/), and [Firebase](https://firebase.google.com/docs/firestore/). However, you can use any database you want, as long as you can explain why it is appropriate and how it helps make the system robust.

## Implementation

You will create an API service, using hapi and other tools, to provide data for the Chords frontend. At a minimum, there must be an API endpoint that returns a JSON list of fans and artists, with data for user profile pages (e.g. name, age, location). You may decide what the data looks like from scratch.

Importantly, this service must be extremely resilient to various kinds of failure: network outages, unexpected server reboots, developer mistakes, deployment issues, etc. It must also automatically recover from these situations where reasonable.

Host the service on your favorite cloud provider (e.g. [now.sh](https://zeit.co/now), [AWS](https://aws.amazon.com/), or similar). You can use a tool like [Localtunnel](https://localtunnel.me) to share a local instance for demo purposes, which is useful in case you have any questions early on.

## Optional / Bonus Points

If you want to demonstrate some other skills, here are a few ideas to improve the app.

 - Provide other API routes that might be useful for music streaming, saving/updating data, etc.
 - Make a programmatic API client that could be used to build a frontend GUI
 - Write tests with [AVA](https://github.com/avajs/ava) or similar test frameworks
 - Use other tools from the hapi ecosystem (e.g. [lout](https://github.com/hapijs/lout) generates route documentation)
 - Enforce high-quality code style by using [XO](https://github.com/sindresorhus/xo) and [Tidy](https://github.com/sholladay/eslint-config-tidy)

## Checklist

1. [Create a new repository](https://help.github.com/articles/create-a-repo/).
3. Do the assignment work.
4. Commit your work: `git commit -am 'Add some things'`
5. Push commits to GitHub: `git push origin master`
6. Send us the link to your repository.

## Help & Support

We highly encourage you to reach out to us with questions. We do not expect everyone to be familiar with every facet of the assignment. This is a collaborative effort and discussing it may lead you to new, innovative approaches that we have not considered.

## Feedback

We would love to hear your thoughts about this assignment, both before and after completing it. We embrace change and aim to continually improve.

## License

Copyright © [Noirdoor](https://noirdoor.com "Owner of assignment-backend"). All rights reserved.
