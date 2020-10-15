## Features to be added

#### General
- Proxy support
- Telethon auto-update
- ~~Check follower limit before joining group~~
- ~~Adding groups dynamically to 'group_template.json' and 'quickstart.py'~~
- After liking the posts that have been missed during first liking batch, it does not find the newly missed ones. Minor issue. Noticable in fast-pacing groups
- Some useful features needed
- Gets funny after midnight (dumb timing in run.py) - e.g. do not use with timing from 23 to 4 (it does not like day switch)
- Probably some other mess. Been stress-testing it for several weeks, no major issues

#### Reporting/control
- Start/stop by sending message in Telegram (either from another account or in 'Saved Messages')
- Daily report (sent to Telegram) - how many times each group was taken, which group failed etc.

#### Functionality/failsafes
- Catch the moment when there is no network (if network gets cut off mid program, session file is blocked and program throws you out)
- Arguments (targeted link, random link, silent mode, account, session name etc.)
- ~~If blocked/banned from group - add to 'groups.json' to avoid entering the group~~
- ~~Check if login has been made on Instagram~~

#### Groups
- ~~Comment groups. Example program: read comments from the post, pick one, check if it is not spam (links and spam phrases), add something and post comment (so it does not appear as spammy with pre-defined comments)~~
- Add functionality for groups which are doing 'rounds'


## Optional features

- Log follower count for analysis (alternative to Socialblade)
- GUI? In first phase this program was set up using PySimpleGUI, might be useful for some

## Other

- ~~Like feed posts~~
-- ~~Restrict from liking own post~~

#### Nam's experiences

- Use scikit-learn ver >= 0.22.2 to avoid error from import profanity_check lib
- **Press** Enter to continue when cmd suddenly suspend

