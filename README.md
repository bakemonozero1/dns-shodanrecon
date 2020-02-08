# dns-shodanrecon
A automated dns solver and shodan recon tool

**Version:** 0.9

## prerequisites
A shodan API Key, without a key this tool only solves the ip address for a given domain / domainlist

## Installation
This tool is build in Python3 and requires the shodan module.
pip install shodan

## Usage
**dns-shodanrecon**

**-h:** Displays help text
**-u:** Parses a single domain to url ans returns shodan results
**-l :** Parses a list of domains to url and returns al shodan results
**-f:** Outputs to file, this option created a directory in the home folder and save one file per domain

## Example of domain file

    google.com
    facebook.com
    github.com
    instagram.com

## Future

 - Duplicate check 
 - Verbose output
