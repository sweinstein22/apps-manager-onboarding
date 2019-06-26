# Apps Manager Onboarding

## Usage
### Import stories to Tracker (from source)
The stories in this repo are divided by section. They are provided in .[prolific](https://github.com/onsi/prolific) format. To grab the most recent versions of stories from master or another branch:

1. Clone this repo
1. Run `./build all` (requires Docker)
1. Import your newly created csv file (`onboarding-tracker.csv`) to a new Tracker project
1. WARNING: concatenating CSVs is a risky/inadvisable business, so stories generated by this script are slightly buggy in inconsequential ways (e.g. the first letter or two of a single story title goes missing).

## Contributing
Depending on personal preferance, either edit stories in the .prolific text files themselves or convert the prolific file to a CSV and upload it to a temporary Tracker project, reverting back to .prolific format once you're ready to make a PR. The second one takes more time, but removes the risk of accidental prolific syntax errors.
