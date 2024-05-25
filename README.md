# WSO2-2021-1258: Zip Slip vulnerability in the WSO2 ESB

A ZIP file based directory traversal (Zip Slip) vulnerability was identified in the WSO2 Management Console. Remote code execution may be obtained by writing/overwriting specific files.

### Vendor Disclosure:

The vendor's disclosure and fix for this vulnerability can be found [here](https://security.docs.wso2.com/en/latest/security-announcements/security-advisories/2021/WSO2-2021-1258/).

### Why no CVE?

Neither me nor the vendor requested a CVE for this vulnerability.

### Requirements:

This vulnerability requires:
<br/>
- Valid user credentials

### Proof Of Concept:

More details and the exploitation process can be found in this [PDF](https://github.com/mbadanoiu/WSO2-2021-1258/blob/main/WSO2%20ESB%20-%20WSO2-2021-1258.pdf).

