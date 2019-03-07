# spdx-license-namespaces-registry
A prototype public registry for SPDX license namespaces beyond the standard SPDX license list. 

There are two levels of "registration":

1. Just register a namespace that you use to name your SPDX LicenseRef-<namespace>-<some id>
   For this just submit a PR to be added to this file.

2. Register a namespace and register your licenses.
   For this submit a PR with your registration and one or more PR with your licenses.
   
   The license could be provided (TBD) as:
   * one SPDX document for each license
   * one summary JSON listing all licenses and one detail JSON for each licenses


## Registered namespaces:

 * scancode
   * homepage_url: https://github.com/nexB/scancode-toolkit
   * email: pombredanne@nexb.com

 * foobar
   * homepage_url: https://example.com/foobar
   * email: jame@example.com