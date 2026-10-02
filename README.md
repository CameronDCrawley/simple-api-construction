# 🏗️ Project: Simple API 1 - Construction

### Goal: Build a simple front-end app that displays data returned from an api that would be beneficial to someone in the trades (construction, hvac, plumbing, ect)

### How to submit your code for review:

- Fork and clone this repo
- Create a new branch called answer
- Checkout answer branch
- Push to your fork
- Issue a pull request
- Your pull request description should contain the following:
  - (1 to 5 no 3) I completed the challenge
  - (1 to 5 no 3) I feel good about my code
  - Anything specific on which you want feedback!

Example:
```
I completed the challenge: 5
I feel good about my code: 4
I'm not sure if my constructors are setup cleanly...
```
# Blue Collar Job Board

A simple web application that allows users to search for job listings in skilled trades across the US using the Adzuna Job Search API.

---

## Features

- **Trade Search:** Select a skilled trade from a dropdown menu to find relevant job openings.
- **Job Details:** Displays the job title, maximum estimated salary, and location for up to 10 job listings.
- **Dynamic Updates:** Populates the page with job results when the user clicks the search button.

---

## API Used

- **Adzuna Job Search API:** `https://api.adzuna.com/v1/api/jobs/us/search/1`

---

## How It Works

1. The user selects a trade category from a `<select>` dropdown and clicks the trade search button (`#tradeBtn`).
2. The application fetches job results matching the selected trade from the Adzuna API.
3. It parses the top 10 job listings, retrieving each job's title, maximum salary, and state/area location.
4. The title, salary, and location details are updated in the corresponding DOM elements on the page.

---

<img width="2837" height="1565" alt="image" src="https://github.com/user-attachments/assets/037e8266-0530-4da6-8540-b65ab788a365" />
