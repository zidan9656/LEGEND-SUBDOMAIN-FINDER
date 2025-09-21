# LEGEND SUBDOMAIN FINDER
This tool is specifically designed to identify and enumerate the subdomains associated with a given website. By providing a valid link or domain name, the tool systematically analyzes the target and generates a comprehensive list of accessible subdomains. This functionality is particularly useful for security assessments, penetration testing, and general reconnaissance, as it enables users to gain deeper insights into the structure and potential entry points of a web application or online service.

### Overview
<h1 align="center">
  <img src="https://github.com/zidan9656/IMAGE/blob/main/Debian%2012.x%2064-bit%20-%20VMware%20Workstation%2021-09-2025%2012_33_16.png" width="700px">
  <br>
</h1>

# INSTALLATION
```bash
sudo apt update
```

```bash
sudo apt install curl dnsutils ncurses-bin xdg-utils jq parallel getent
```
or

```bash
sudo apt install curl bind9-dnsutils ncurses-bin xdg-utils jq parallel net-tools

```

```bash
git clone https://github.com/zidan9656/LEGEND-SUBDOMAIN-FINDER.git
```


```bash
cd LEGEND-SUBDOMAIN-FINDER
```

```bash
cdmod +x LEGEND_SUBDOMAIN_FINDER.sh
```

```bash
./LEGEND_SUBDOMAIN_FINDER.sh
```

or


```bash
bash LEGEND_SUBDOMAIN_FINDER.sh
```
