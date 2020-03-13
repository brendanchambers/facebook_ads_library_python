# Extended March 13 2020, Brendan Chambers
This project extends the existing Facebook command line tool for fetching ads data through the Ads Library API
I have added functionality for search by impression_condition and a convenience notebook for running the command line tool.
See the original project at  https://github.com/facebookresearch/Ad-Library-API-Script-Repository

An access token is required, stored in a file titled config:
secret_code="<access token>"

Documentation from the original project begins below.
________________________________________________________________________________________________



# Ads-Library-API-Script-Repository
Ads-Library-API-Script-Repository is a set of code examples to help user/researchers understand how the Facebook Ads Library API works. It also provides a simple command-line interface(CLI) for users to easily use the Facebook Ads Library API.

## Examples
Here's an example on how to use the CLI:

    $ python fb_ads_library_api_cli.py -t {access_token} -f 'page_id,ad_snapshot_url,funding_entity,ad_delivery_start_time' -c 'CA' -s '.' -v count

It count the number of active polictical ads that are running in CA(Canada);

Note: please replace the '{access_token}' with your [Facebook Developer access token](https://developers.facebook.com/tools/accesstoken/).

## Requirements
Ads-Library-API-Script-Repository requires or works with
* Mac OS X or Linux or Window
* Python 3.0+


## How Ads-Library-API-Script-Repository works
The script will query the [Facebook Ads library API](https://www.facebook.com/ads/library/api) to get all the Ads Library information on the Facebook platform;

## Full documentation
You can find the full documentation here: (--to-be-added--)

## More about Facebook Ads Library
* Website: https://www.facebook.com/ads/library
* Report: https://www.facebook.com/ads/library/report
* API: https://www.facebook.com/ads/library/api

See the [CONTRIBUTING](CONTRIBUTING.md) file for how to help out.

## License
Ads-Library-API-Script-Repository is licensed under the Facebook Platform License, as found in the LICENSE file.
