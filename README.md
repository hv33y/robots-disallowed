# RobotsDisallowed

Welcome to RobotsDisallowed, a unique project that compiles the robots.txt disallowed directories from the world's top websites, focusing on the Alexa 100K and the Majestic 100K lists.

## Overview

This project is a valuable resource for enhancing content discovery during web security assessments or bug bounty programs. By examining the directories that websites explicitly disallow in their robots.txt files, you gain insight into potential high-value targets where sensitive information might be stored.

## The Project

We've extracted and cleaned up the disallowed directories from the robots.txt files of the Alexa Top 100,000 websites. Our aim is to provide a curated and useful list for web assessments.

## History and Updates

- **2017:** Initial creation using the Alexa 100K list.
- **2019:** Last update using the Majestic Million top 100K. Transitioned from Alexa to Majestic due to Alexa's shift to a pay model. Switched user-agent to Chromium, simplified file structure, and added an /archive directory for preserving older versions. Removed actual robots.txt files for efficiency.

## How to Use

1. **Clone the Repository:** Copy the directory to your system.
2. **Choose Your List:** Select a file based on the scale of your assessment. Larger top-N lists provide more options but require more time.
3. **Recommended Option:** Consider using `curated.txt`, a concise list of around 500 items. It focuses on directories containing strings like "admin," "user," "account," "password," "forgot," "login," "backup," and the top 25 entries from the full list. Optimal for time efficiency and relevant targets.

### TL;DR

For the best use of your time, go with `curated.txt`.

## Acknowledgements

Thank you for exploring RobotsDisallowed! Happy hacking!
