schedule:
    - cron: "0 6 * * *"  # 📅 Scrape once a day at 6AM

This piece of code in scrape.yaml is responsible for runing GitHub actions at
The initial cron expression 0 6 * * * means my job runs at 6:00 AM UTC every day. The five fields are minute, hour, day of month, month, and day of week.
