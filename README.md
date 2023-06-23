# ANTI-ROOT-AND-SSL-PINNING2
https://codeshare.frida.re/@vicsanjinez/anti-root-and-ssl-pinning2/

Based on the project https://codeshare.frida.re/@limyout/root-detection-and--ssl-pinning/ with a little modification for an error with "Error: getPackageInfo(): has more than one overload, use .overload(&lt;signature>) to choose from: .overload('android.content.pm.VersionedPackage', 'int') .overload('java.lang.String', 'int')"

```bash
$ frida  -U -l ANTI-ROOT-AND-SSL-PINNING2.js -no-pause -f YOUR_BINARY
```
or
```bash
$ frida  --codeshare vicsanjinez/anti-root-and-ssl-pinning2 -f YOUR_BINARY
```


