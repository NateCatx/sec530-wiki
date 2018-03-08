Welcome to the SANS SEC455 Wiki
----------


![Cyber Defense](CyberDefense_logo.jpg)
### **`SEC455 Portal Version: 1.0.0`**

---

The goal of the SEC455 wiki is to provide knowledge to the security community. As one gets better we all get better! As such this is a free source of cyber defense information primarily around Security Information Event Management (SIEM) systems.

The other goal is for (**SEC455: SIEM with Tactical Analytics**)[https://www.sans.org/course/siem-with-tactical-analytics] students and is to increase the **in-class**, and, most importantly, **after-class** value of the course material. It is also designed as a method to give back to the security community by providing free information. This wiki is, and likely always will be, very much a work in progress.

Contained in the wiki, you will find:

- Tool and technique cheat sheets
- Reference guides
- Information about 455 instructors
- Electronic Copies of the Lab Guides (**copy and paste, FTW!!!**) (**Digital labs are only available on student VM - SEC455 course attendees only**)
...and more

Note: If you are using the student VM included when taking SEC455 you have the capability of turning on automatic wiki/lab updating.

Recommendations - PLEASE READ
----------
There are two things that are **highly recommended** to do before diving in.

1. **Discover how to use the Smart Player**. Videos are played using Smart Player and there are some features you may not know exist without checking [out this guide](/Resources/SmartPlayer.md). The videos created in the wiki took a tremendous amount of time to put together due to adding many features that Smart Player allows such as searching for any word spoken by the presenter and jumping to that section of the video.
2. If you are a SEC455 student, **enable automatic updates of the wiki and lab content**

Enable Automatic Updates
----------

This section only applies to students of SEC455 using the wiki within the SEC455 course provided student virtual machine. In order to enable automatic wiki/lab updating run the following command:

```bash
sudo crontab -e
```

Then uncomment the cron job for either the 9 AM automatic update or the update after reboot (or both):

```bash
# Uncomment the below entry to automatically update the SEC455
# wiki. The default check occurs at 9 AM but can be changed.
#0 9 * * * pwsh -file /scripts/wiki_update.ps1

# Uncomment the below entry to automatically update the SEC455
# wiki after each reboot.
#@reboot pwsh -file /scripts/wiki_update.ps1
```

When finished the cron entry should look similar to this:

```bash
# Uncomment the below entry to automatically update the SEC455
# wiki. The default check occurs at 9 AM but can be changed.
0 9 * * * pwsh -file /scripts/wiki_update.ps1

# Uncomment the below entry to automatically update the SEC455
# wiki after each reboot.
@reboot pwsh -file /scripts/wiki_update.ps1
```

---


Course/Lab/Wiki Bugs or Suggestions
----------

---

Please let us know if you find any bugs in the courseware/labs/wiki we need to squash. Also, reach out if you have suggestions to improve the course (e.g. content/labs/tools that should be added, removed, or updated). The easiest way to submit these improvements is by sending an email to **<justin@hasecuritysolutions.com>**

---

Alumni Mailing List
----------

---

Join the 455 alumni mailing list:

[http://SEC455.com/455group](http://SEC455.com/455group)

---