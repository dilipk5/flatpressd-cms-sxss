# CVE - XSS in FlatPress CMS

## Vulnerability
Cross-site scripting (XSS) in the comment form and contact form of FlatPress CMS
via the ensure_https_url() function allows remote attackers to inject arbitrary 
web script or HTML.

## Affected Version
FlatPress CMS (before commit 10be83c)

## Fixed Version
Master branch, commit 10be83c — April 15, 2026

## Discovery
Dilipkumar Choudhary

## Vendor Contact
Frank (FlatPress maintainer) — acknowledged and patched

## Fix Reference
https://github.com/flatpressblog/flatpress/commit/10be83c
