# realPad SDK
A simple script to fetch all data from the realPad Takeout API. The intended usage is to configure it once, then let cron run it as often as required.

## Usage
Clone, replace `LOGIN` and `PASSWORD` in `takeout-download.sh` with credentials you get from us, and run. The script will download the Excel files and store them in the working directory, with unique (timestamped) names.
