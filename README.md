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

    dns-shodanrecon -h

**-u:** Parses a single domain to url ans returns shodan results

    dns-shodanrecon -u google.com

**-l :** Parses a list of domains to url and returns al shodan results

    dns-shodanrecon -l domainlist.txt

**-f:** Outputs to file, this option created a directory in the home folder and save one file per domain

    dns-shodanrecon -l domainlist.txt -f


## Example of domain file

    google.com
    facebook.com
    github.com
    instagram.com
    
## Screenshots
**Terminal Output**
![filescreenshot](https://github.com/bakemonozero1/dns-shodanrecon/blob/master/screenshots/terminal-screenshot.png)

**File Output**
![filescreenshot](https://github.com/bakemonozero1/dns-shodanrecon/blob/master/screenshots/file-screenshot.png)


## Future

 - Duplicate check 
 - Create Better Banner
 - Verbose output
