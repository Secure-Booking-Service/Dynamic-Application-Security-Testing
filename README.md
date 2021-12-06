<div align="center">
    <img src="https://raw.githubusercontent.com/Secure-Booking-Service/Dynamic-Application-Security-Testing/main/logo.svg" alt="Check-All Icon by Bootstrap" width="100">
    <br>
    <h2>Dynamic Application Security Testing</h2>
    <br>
</div>
[![Badge](https://img.shields.io/badge/project-Secure%20Booking%20Service-blue)](https://github.com/Secure-Booking)

[![ZAP - Full Scan](https://github.com/Secure-Booking-Service/Dynamic-Application-Security-Testing/actions/workflows/full-scan.yml/badge.svg)](https://github.com/Secure-Booking-Service/Dynamic-Application-Security-Testing/actions/workflows/full-scan.yml)

[![ZAP - API Scan](https://github.com/Secure-Booking-Service/Dynamic-Application-Security-Testing/actions/workflows/api-scan.yml/badge.svg)](https://github.com/Secure-Booking-Service/Dynamic-Application-Security-Testing/actions/workflows/api-scan.yml)

This repository contains workflow files for GitHub Actions. These workflows performs either a [Full scan](https://www.zaproxy.org/docs/docker/full-scan/) or an [API scan](https://www.zaproxy.org/docs/docker/api-scan/).

Message from the OWASP ZAP Team:
> **WARNING** [these actions] will perform attacks on the target website [or api]. You should only scan targets that you have permission to test. You should also check with your hosting company and any other services such as CDNs that may be affected before running this action. ZAP will also submit forms which could result in a large number of messages via, for example, 'Contact us' or 'comment' forms.

## Setup
To setup this project it is required to define the following repository secrets:

### `ZAP_FULL_SCAN_TARGET`
Target url for the ZAP full scan.

### `ZAP_API_SCAN_FILE`
Target API definition as local file or URL like https://www.example.com/openapi.json

### `ZAP_API_SCAN_FILE_FORMAT`
The format of the defintion `openapi`, `graphql` or `soap`.

### `ZAP_GLOBAL_CMD_OPTIONS`
Additional command lines options for the scan script

---
<div align="left">
    Icon by <a href="https://github.com/twbs/icons">Bootstrap</a> published under <a href="https://github.com/twbs/icons/blob/main/LICENSE.md">MIT licence</a>.
</div>