# 🛡️ Semgrep OWASP Top 10 Report

- **File:** routes/login.ts
  - **Line:** 34
  - **Rule:** javascript.sequelize.security.audit.sequelize-injection-express.express-sequelize-injection
  - **Message:** Detected a sequelize statement that is tainted by user-input. This could lead to SQL injection if the variable is user-controlled and is not properly sanitized. In order to prevent SQL injection, it is recommended to use parameterized queries or prepared statements.

- **File:** routes/search.ts
  - **Line:** 23
  - **Rule:** javascript.sequelize.security.audit.sequelize-injection-express.express-sequelize-injection
  - **Message:** Detected a sequelize statement that is tainted by user-input. This could lead to SQL injection if the variable is user-controlled and is not properly sanitized. In order to prevent SQL injection, it is recommended to use parameterized queries or prepared statements.

- **File:** server.ts
  - **Line:** 266
  - **Rule:** javascript.express.security.audit.express-check-directory-listing.express-check-directory-listing
  - **Message:** Directory listing/indexing is enabled, which may lead to disclosure of sensitive directories and files. It is recommended to disable directory listing unless it is a public resource. If you need directory listing, ensure that sensitive files are inaccessible when querying the resource.

- **File:** server.ts
  - **Line:** 270
  - **Rule:** javascript.express.security.audit.express-check-directory-listing.express-check-directory-listing
  - **Message:** Directory listing/indexing is enabled, which may lead to disclosure of sensitive directories and files. It is recommended to disable directory listing unless it is a public resource. If you need directory listing, ensure that sensitive files are inaccessible when querying the resource.

- **File:** server.ts
  - **Line:** 274
  - **Rule:** javascript.express.security.audit.express-check-directory-listing.express-check-directory-listing
  - **Message:** Directory listing/indexing is enabled, which may lead to disclosure of sensitive directories and files. It is recommended to disable directory listing unless it is a public resource. If you need directory listing, ensure that sensitive files are inaccessible when querying the resource.

- **File:** server.ts
  - **Line:** 278
  - **Rule:** javascript.express.security.audit.express-check-directory-listing.express-check-directory-listing
  - **Message:** Directory listing/indexing is enabled, which may lead to disclosure of sensitive directories and files. It is recommended to disable directory listing unless it is a public resource. If you need directory listing, ensure that sensitive files are inaccessible when querying the resource.

