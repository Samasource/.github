Jira story: 

## Description

<!-- Provide a brief description of the changes introduced by this pull request -->

## Security Checklist

- [ ] Verified that all input (HTML form fields, REST requests, URL parameters, HTTP headers, cookies, batch files, RSS feeds, etc) is validated using positive validation (allow lists). 

- [ ] Verified that data selection or database queries (e.g. SQL, HQL, ORM, NoSQL) use parameterized queries, ORMs, entity frameworks, or are otherwise protected from database injection attacks.

- [ ] Verified that output encoding is relevant for the interpreter and context required. For example, use encoders specifically for HTML values, HTML attributes, JavaScript, URL parameters, HTTP headers, SMTP, and others as the context requires, especially from untrusted inputs (e.g. names with Unicode or apostrophes, such as ねこ or O'Hara).

- [ ] Verified that key material is not exposed to the application but instead uses an isolated security module like a vault for cryptographic operations.
