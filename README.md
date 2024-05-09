
# WP-SecureScan - Check for Malware

WP-SecureScan is a script designed to check for Malware inside your Wordpress Installation. It uses specific pattern which were used by Malware recently and is updated for Malware from 2014 to 2024. 
## Up-to-date(?)

Even if this script is up to date with the recent Malware I am not a witch! If you have any further information about Malware in Wordpress instances or need updates for some kind of code please tell me within a issue! 
## Running


```bash
Usage: ./malware_scanner.sh [--perms, -p] [--verbose, -p] [--help, -h]

Options:
--perms, -p      Fix file permissions
--verbose, -v    Enable interactive reporting
--help, -h       Display this help message
```

To run it directly within the download you can use the following bash line in the directory you want to scan: 

```bash
  wget -O - https://raw.githubusercontent.com/haupt-pascal/WP-SecureScan/main/malware_scanner.sh\?token\=GHSAT0AAAAAACRBSWFRLIGOJ2NRYYV3VEOQZR5F7GQ | sh -s -- -v

```
\
If you don't want to download it directly and start you just can do the following in the directory you want to scan: 

```bash
wget https://raw.githubusercontent.com/haupt-pascal/WP-SecureScan/main/malware_scanner.sh\?token\=GHSAT0AAAAAACRBSWFRLIGOJ2NRYYV3VEOQZR5F7GQ

sh malware_scanner.sh -v
```
## Contributing

Contributions are always welcome! The project is only open-source to create a huge tool which is only possible with you as a contributor.

You can create a pull request inside the issues tab as well as feature requests and bugs you've found. After a review I'll give you a feedback.  
## License

[MIT](https://choosealicense.com/licenses/mit/)

