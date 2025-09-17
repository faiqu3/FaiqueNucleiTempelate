# FaiqueNucleiTemplate
Bug bounty template to test HTTP callback based vulnerabilities

```
nuclei -c 300 -l subdomains.txt -bulk-size 50 -retries 3 -timeout 20 -t /Users/faiqueraza/Pentest/ssrf/ -var "MY-DOMAIN=qoix59dchpz888x067u7ls60oruii96y.oastify.com"
```
