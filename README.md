# Race Countdown

This repository tracks upcoming races and displays a countdown to the next event in your schedule. The countdown will update daily (cron job runs at midnight UTC) to show the number of days left until your next race, and on race day, it will display "Race Day!".

## Badges

Here’s the countdown to your next race, including the race distance:

<a href="https://github.com/harrychallis/racecountdown">
  <img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fharrychallis%2Fracecountdown%2Fmain%2Fcountdown.json&style=for-the-badge&logo=running&logoColor=white" alt="Race Countdown" />
</a>

### How It Works
- The countdown automatically updates every day, showing the number of days left until the race.
- When the race day arrives, it will display "Race Day!".
- After the race, the countdown switches to the next race on the schedule.

## Setup

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/harrychallis/racecountdown.git
