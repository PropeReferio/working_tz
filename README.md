# working_tz - CLI for local working hours

Hey folks. It's simple. Make the script executable by adding it to your path and using `chmod +x working_tz`. Then call it like this:

`working_tz --work -6 --living +2` if your company is in CST but you're working in Croatia.

Optionally, you can set an environment variable `UTC_OFFSET_WORK` if you don't want to pass that in as an option.
