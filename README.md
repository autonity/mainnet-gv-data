# Mainnet GV Data
This repository contains the Genesis Validator data that will be used to create the validator set for launch of the Autonity Mainnet.

# Important notes

- Please do not use existing keys/addresses from previous genesises, instead generate new ones.
- You have been issued with a new Mainnet UUID, which you should use for this submission (*not* the UUID that was used for submitting your Bakerloo data).
- Please avoid using Hetzner IP addresses to prevent clustering with a single cloud provider (this will be checked too and you may be asked to resubmit your enode).
- Please submit your data by no later than **Wednesday, 23rd July 2025**.

# Step-by-step guide
The steps below outline how selected Genesis Validators should submit the required data for a successful launch of the Autonity Mainnet. Please:

1. Clone this repo locally and branch off the ***master*** branch. Name your own branch in the following format ***[UUID]-genesis-validator-data***. Please use your **Mainnet UUID**, not your Bakerloo one (if you don't know what it is please reach out to @spencercoll1ns on Telegram).
2. On your own branch, navigate to the `genesis-validator-data` folder.
3. Inspect the `template.json` file that shows the format in which you should submit your own json file, and contains reference documentation for each field.
4. Create a new json file called `[UUID].json`, containing your validator info as per the `template.json` file.
5. Open a pull request against the ***master*** branch and add ***"[UUID]-genesis-validator-data"*** as the PR title.
6. The team will review your PR, verify your ownership proof and merge it if all checks pass. You have now successfully submitted your genesis validator data for Mainnet!

⚠️ Please ensure any data you submit here will still be correct for genesis of Mainnet. Specifically, ensure that any IP address/port number you submit here will still be available to you at genesis. Modifying your supplied information later may result in delays.

If you have any questions, please reach out on Discord in the [#genesis-validators](https://discord.com/channels/753937111781998605/1293533625815535646) channel. 

Continue to monitor Discord/Telegram for instructions on next steps. Thank you for helping launch Mainnet!

