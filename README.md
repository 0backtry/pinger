# Pinger

Tool for pinging hosts/ip adresses from a .txt file.

## Usage:
`
	kali@kali:pinger (master)> ./pinger
	Error: File or output file argument is missing.
	Usage: /usr/local/bin/pinger -f <file> [-t <threads>] -o <output_file> [-v]
	Options:
	  -f <file>         File containing IP addresses or subdomains
	  -t <threads>      Number of threads (default: 10, max: 100)
	  -o <output_file>  Output file for up IPs
	  -v                Verbose mode (optional)
	  -h                Display this help message
`