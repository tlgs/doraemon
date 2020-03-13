# doraemon

Collect a random item from your [Pocket](https://getpocket.com) List.

Simple wrapper Bash script around [curl](https://curl.haxx.se/) and
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
   How I write backends
   --------------------
   https://app.getpocket.com/read/2859972659

   $ doraemon -h
   doraemon 0.2.0, el gato cosmico
   Collect a random item from your Pocket List

   Usage: doraemon [-hb]

       -h, --help        display this help message and exit
       -b, --browser     open item in your preferred $BROWSER

   ```

Tip: on most terminal emulators, you can <kbd>Ctrl</kbd> + click on URLs to
open them on your browser.
