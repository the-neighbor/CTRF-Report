# CTFR-Report

This uses react and webpack in order to generate a webpage that displays jest and playwright test reports for various branches of a repository generated by that repo's github actions workflow runs.

The webpage just needs to be in the same folder as a branches.json file with information on each branch's workflow run, and an artifacts folder for each branch containing the artifacts from that workflow run for jest and playwright.