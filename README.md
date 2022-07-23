# doraemon

Collect a random item from your [Pocket](https://getpocket.com) List.
Simple Bash script built with [curl](https://curl.haxx.se/) and
[jq](https://stedolan.github.io/jq/).

 ```console
 $ doraemon
 13 Minutes to the Moon
 ----------------------
 https://app.getpocket.com/read/2590525260
 ```

 ## Usage

Set the `POCKET_CONSUMER_KEY` and `POCKET_ACCESS_TOKEN` environment variables
(follow the [Pocket API documentation](https://getpocket.com/developer/) to get yours).

Drop the script somewhere in `PATH` or create a symbolic link
(i.e. `ln -s /full/path/doraemon ~/bin/doraemon`).
