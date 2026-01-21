# Redirection to Links for Certificates

The URL links for online Training Certificates are often very long & look unsightly in printed resumes.

This repo creates a simple, reuseable page which uses a JSON array to store (among other things) the URL Link of the certificate and an internal _Redirection short-name_ for certificates.

When the page is opened with a command line parameter("id"), it will search through the JSON array for matching _"Redirection short-name"_, find the corresponding URL Link & redirect to it.

In case the command line parameter is wrong or missing, the page will show the full list of Certificate Description with URL Links as a table.

Access the [Live version here](https://arun-ks.github.io/cert/)

<details>
  <summary>To Do Items</summary>
  
- [ ] Usability: Add tool tip to the headers
- [X] Enhancement: Update default page to show full list of certificates
- [ ] Enhancement: Find way to log access attempts
- [X] Usability: Create category-based sections within the table
- [X] Usability: Allow filtering/search on the table.
- [ ] Usability: Allow sorting on the table.
</details>
