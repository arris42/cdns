# Temporary files

Alternative direct link generator

**How To**
- Using curl :<br/>
`curl https://raw.githubusercontent.com/<username>/<repo>/master/<filename> --output <filename>`

- Using wget :<br/>
`wget -O <filename> https://raw.githubusercontent.com/<username>/<repo>/master/<filename>`
&nbsp;

- Using aria2c :<br/>
`aria2c https://raw.githubusercontent.com/<username>/<repo>/master/<filename>`

**Examples**
- `curl https://raw.githubusercontent.com/arris42/cdns/master/unzip.exe --output unzip.exe`
- `wget -O unzip.exe https://raw.githubusercontent.com/arris42/cdns/master/unzip.exe`
- `aria2c https://raw.githubusercontent.com/arris42/cdns/master/unzip.exe`
