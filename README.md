# Get-ShodanNetIP
Allows for the quick querying of Shodan results from a list of IPs and/or subnets.  The results are returned in CSV format.  A Shodan API key is required to use this service.

## Usage
### Example 1
Import a list of IPs and/or subnets (one per line) and use the Shodan API to query the results.

`.\Get-ShodanNetIP.ps1 -NetworkInput <ip_list.txt>`

### Example 2
Import a list of IPs and/or subnets (one per line) and use the Shodan API to query the results and customize the output CSV file name.

`.\Get-ShodanNetIP.ps1 -NetworkInput <ip_list.txt> -OutFile <output_file_name.csv>`

## Credit
This code implements Shodan API code written by Carlos Perez (@darkoperator) from his `Posh-Shodan` PowerShell module.  It includes the required license agreement for reuse.

https://github.com/darkoperator/Posh-Shodan
