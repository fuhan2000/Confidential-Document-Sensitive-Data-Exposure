# Confidential-Document-Sensitive-Data-Exposure

## What I have learned from Hacksplained’s Confidential Document Sensitive Data Exposure

- In OWASP Juice Shop, if you click on About Us:

<img src="https://i.imgur.com/rIBu1DU.png" height="400" />

*Ref 1: About Us*

- And then click on “Check out our boring terms of use if you are interested in such lame stuff”

<img src="https://i.imgur.com/kEsdYkN.png" width="400" />

*Ref 2: Check out our boring terms of use if you are interested in such lame stuff*

- You will get “Legal Information” in the browser. In Burp, if you check out #56, you will see GET /ftp/legal.md:

<img src="https://i.imgur.com/Jwuc1kC.png" width="400" />

*Ref 3: Legal Information*
