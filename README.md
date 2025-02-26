# Scraping
This scraper is used to scrape the top 5 headlines of the Student section of DP, so prospective, current, or alumni of Penn know about what's happening with the student community at Penn. If they visit Penn campus, they can find the events that's currently happening on campus. I did this by changing the link from dp to dp-student section, and outputting a list of 5 headlines instead of just one headline in script.py.

# Schedule Explanation
The initial cron expression 0 20 * * * means my job runs at 20:00 UTC every day. The five fields are minute, hour, day of month, month, and day of week.