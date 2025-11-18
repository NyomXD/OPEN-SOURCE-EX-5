# OPEN-SOURCE-EX-5
# Aim:
To configure scheduled tasks (cron jobs) for the user harry so that specific commands are executed automatically at defined times, including daily jobs and jobs running every 2 minutes.
# Procedure:
1. Switch to the user harry or open harry’s crontab.
2. Open the user-specific cron table.
3. Add the required scheduling lines for each job in correct cron format.
4. Save and exit the cron editor.
5. Verify the cron entries to ensure tasks were added successfully.

# Output:
<img width="731" height="524" alt="Screenshot 2025-11-18 104146" src="https://github.com/user-attachments/assets/32bf0ad2-67c9-4c3b-a375-64320421af9b" />

<img width="641" height="258" alt="image" src="https://github.com/user-attachments/assets/f1135dd0-4497-41bc-813e-bd49a8fb57ed" />

# Result:
Using crontab -eu harry, all required cron jobs were successfully created:Cron job at 12:30 daily prints hello.Cron job every 2 minutes prints “Hi I’m Running”.Cron job at 14:23 daily logs “RHCSA EXAM TRAINING”.Cron job at 12:00 noon daily logs “EX200 in Progress”.All cron jobs were verified using crontab -l -u harry.
