This package includes tools for more smoothly getting survey responses via Alchemer's API.

Usage:
- Run alchemer_auth() with your API key & secret
- Run alchemer_download() with the ID of the survey you'd like to download
- Pass the raw downloaded responses to alchemer_clean() to get them in a more usable format (similar to what would be downloaded from their web interface)

```
alchemer_auth(my_alchemer_key, my_alchemer_secret)
responses_raw <- alchemer_download(id = 123456)
responses_clean <- alchemer_clean(responses_raw)
```
