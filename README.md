# Dynamic-Application-Security-Testing
This repository contains workflow files for GitHub Actions. These workflows performs 

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