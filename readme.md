## General
mass follow people under hashtags like "photography" or "film" etc. some portion will follow back... wait a week or two and unfollow all

## scratchpad
- https://github.com/ping/instagram_private_api
    - ensure this is up to date and working
- steps:
    1. get "tag feed" with specified hashtag
    2. follow the creators of the first X posts
        - add a sleep() time, instagram is rate limited
    3. save users followed through this script in a text file
    4. wait y amount of time and unfollow all those users
    5. repeat
