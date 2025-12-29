Zenodo JSON Instructions

This package contains a metadata file (agentic_cmo_zenodo.json) designed for uploading your work or references to Zenodo.org. Zenodo is an open-access repository often used by researchers and thought leaders to create a permanent record (DOI) for their work.

How to use this file

Option 1: Manual Upload (Copy & Paste)

If you are creating a manual record on Zenodo:

Log in to Zenodo.

Open the agentic_cmo_zenodo.json file in a text editor.

Use the content to fill in the corresponding fields in the Zenodo web interface:

Title: Copy from "title"

Creators: Copy from "creators"

Description: Copy the HTML content from "description" (Zenodo accepts HTML for formatting lists and bold text).

Keywords: Copy the list from "keywords".

Related Identifiers: Use the Amazon and Substack URLs provided in the JSON.

Option 2: GitHub Integration (Automated)

If you host your frameworks or code snippets on GitHub:

Rename the agentic_cmo_zenodo.json file to .zenodo.json.

Place this file in the root directory of your GitHub repository.

Enable Zenodo integration for that repository.

When you create a Release in GitHub, Zenodo will automatically use this file to populate the metadata for your permanent record.

Note on ORCID

In the creators section, the "orcid" field is currently empty (""). If you have an ORCID iD (Open Researcher and Contributor ID), paste it inside the quotes (e.g., "0000-0000-0000-0000") to link the record to your academic profile.