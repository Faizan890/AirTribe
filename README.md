# AirTribe
Internship Assignment - Backend
**Problem statement:**

Design database and APIs for application based courses on Airtribe.

Database relations:

- There are multiple instructors on Airtribe.
- Every instructor can start multiple courses.
- Multiple learners can apply for a course using application form (Leads)
- Instructor can add comments against every lead

1. Design the above relationships on any SQL database.
2. Create a server in any of your favourite framework using Node.js and add the following APIs
    1. Create course API
    2. Update course details API (name, max_seats, start_date etc)
    3. Course registration API (A user can apply for a course by sharing their name, email, phone number and LinkedIn profile)
    4. Lead update API (Instructor can change status of the lead (Accept / Reject / Waitlist))
    5. Lead search API (Instructor can search leads by name or email)
    6. Add comment API

**How to submit:**  

- (Good to have) Dockerize your server and database.
- Mention the following steps in README:
    - Docker command(s) or scripts to spin up the environment.
    - A script to load test-data (if any).

**Your submission will be judged based on:**

- Code Quality (Clean, Readable, Easy to follow)
- Language specific best practices
- Modularity
- README and Git commits
