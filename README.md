# Microsoft Service Domains

**SysAdmin whitelist for domains used by Office 365, Windows, Azure, and other Microsoft services**

Files are formatted as follows:

- [**RAW**](raw.txt) — good old Plaintext with each domain on a new line
- [**Augmented BNF**](abnf.txt) — compatible with AdGuard DNS, uBlock, AdBlockPlus, etc.

> Included ABNF syntax allows all subdomains; important since MS uses subdomains for service endpoints

## License

[MIT License](LICENSE)
