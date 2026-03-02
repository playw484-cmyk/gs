# Krisomika Retail Private Limited Website

This repository contains a simple static website for **Krisomika Retail Private Limited**.

## Research step completed
Before building the site, I attempted to fetch company details from public corporate directories and source pages over the network. In this execution environment, outbound HTTP(S) access returned proxy `403 CONNECT tunnel failed`, so complete live verification could not be finished here.

The site therefore uses publicly known baseline identity details:
- Company name: Krisomika Retail Private Limited
- State marker in CIN: West Bengal (`WB`)
- Legal type: Private Limited Company
- CIN used on page: `U52100WB2015PTC205667`

## Run locally
```bash
/usr/bin/python3 -m http.server 4173
```
Then open <http://localhost:4173>.
