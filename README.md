# doraemon

Collect a random item from your [Pocket](https://getpocket.com) List.
Simple Bash script built with [curl](https://curl.haxx.se/) and
[jq](https://stedolan.github.io/jq/).

## Usage

1. Ensure you have the `POCKET_CONSUMER_KEY` and `POCKET_ACCESS_TOKEN`
   environment variables set (follow the
   [Pocket API documentation](https://getpocket.com/developer/)
   to get yours).

2. Put the script somewhere in your `PATH`.

3. Run the utility as normal:

   ```console
   $ doraemon
   13 Minutes to the Moon
   ----------------------
   https://app.getpocket.com/read/2590525260

   $ doraemon -h
   Usage: doraemon [OPTIONS]

     doraemon 0.3.0, el gato cosmico.
     Collect a random item from your Pocket List.

   Options:
     -b, --browser     Open item in your preferred $BROWSER.
     -h, --help        Show this message and exit.
   ```
