# CVE-2016-0189
Proof-of-Concept exploit for CVE-2016-0189 (VBScript Memory Corruption in IE11)

Tested on Windows 10 IE 11.

### Write-up
https://www.deamwork.com/archives/patch-analysis-of-cve-2016-0189.orz6

### To run
1. Download `support/*.dll` (or compile \*.cpp for yourself) and `exploit/*.html` to a directory.
2. Serve the directory using a webserver (or python's simple HTTP server).
3. Browse with a victim IE to `vbscript_bypass_pm.html`.
4. (Re-fresh or re-open in case it doesn't work; It's not 100% reliable.)
