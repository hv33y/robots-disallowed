~ RobotsDisallowed

The RobotsDisallowed project is a harvest of the robots.txt disallowed directories of the world's top websites---specifically those of the Alexa 100K and the Majestic 100K.

This list of Disallowed directories is a great way to supplement content discovery during a web security assessment or bug bounty, since the website owner is basically saying, 

"Don't go here; there's sensitive stuff in there!

In other words, it's a list of potential high-value targets.

~ The project

So what we did is take the Alexa Top 100,000 websites, download their robots.txt files, extracted all Disallowed directories, and then performed a bunch of cleanup on them (they are a mess) to make the lists as useful as possible during web assessments.

~ History and updates

- This project was initially created in 2017, and used the Alexa 100K.
- This project was last updated in March of 2019, and used the Majestic Million top 100K. In addition to using the Majestic list instead of Alexa (Alexa went to a pay model), we also switched to Chromium as the user-agent (instead of curl), simplified the file structure, and created an /archive directory so that older versions of the files can persist. The old code directory is also in there. Finally, we removed the actual robots.txt files because…well, they're big and worthless.

~ How to use the project

1. Clone the directory to your system.
2. Pick the file you want to use based on the assessment you're doing. If you have lots of time, maybe use one of the bigger top-*N* lists---vs. using a smaller one if you have less time.

*My personal favorite option, however, is to go with the ``curated.txt`` list, because it's only around 500 items, and it is a collection of directories containing the following strings and content:*

- "admin"
- "user"
- "account"
- "password"
- "forgot"
- "login"
- "backup"
- The top 25 entries from the full list

TL;DR: If you want the best use of your time, go with curated.txt.

Thank you, and happy hacking!