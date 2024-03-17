# getAzureSaKeys
This script will get the storage account keys for each storage account in the sa_accounts.txt file and export them to a CSV file.

## Description

This script will get the storage account keys for each storage account in the **sa_accounts.txt** file and export them to a CSV file.

## Requirements

- PowerShell 5.1 or higher
- Azure PowerShell module

## Usage

1. Create a text file named sa_accounts.txt in the same directory as the script
2. Populate the sa_accounts.txt file with the storage account names with one per line
3. Run the script `./cvps_get_azure_sa_keys.ps1`
