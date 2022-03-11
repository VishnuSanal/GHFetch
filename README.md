# GHFetch - Discover what your friends are upto on GitHub!

## Working

This script uses the GitHub API to fetch recent activity of the user. Then displays the details after formatting with `jq`

## How to use

- Get the files
```
wget https://raw.githubusercontent.com/VishnuSanal/GHFetch/main/ghfetch
```
- Give permissions
```
chmod +x ghfetch
```
- Run!
```
./ghfetch <GitHub-UserName>
```

## Requirements

 - [curl](https://github.com/curl/curl)
 - [jq](https://github.com/stedolan/jq)

## Credits

 - [@tsjazil](https://github.com/tsjazil/) for the name!
