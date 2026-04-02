# PortSwigger Web Security Academy — Full Lab Tracker

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 📊 Progress
<!-- PROGRESS_START -->
Solved: 10 / 0  
Completion: 0%

[░░░░░░░░░░░░░░░░░░░░░░░░░░░░]
<!-- PROGRESS_END -->

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## SQL injection

- [x] SQL injection vulnerability in WHERE clause allowing retrieval of hidden data — *APPRENTICE*
- [x] SQL injection vulnerability allowing login bypass — *APPRENTICE*
- [ ] SQL injection attack, querying the database type and version on Oracle — *PRACTITIONER*
- [x] SQL injection attack, querying the database type and version on MySQL and Microsoft — *PRACTITIONER*
- [x] SQL injection attack, listing the database contents on non-Oracle databases — *PRACTITIONER*
- [ ] SQL injection attack, listing the database contents on Oracle — *PRACTITIONER*
- [x] SQL injection UNION attack, determining the number of columns returned by the query — *PRACTITIONER*
- [x] SQL injection UNION attack, finding a column containing text — *PRACTITIONER*
- [x] SQL injection UNION attack, retrieving data from other tables — *PRACTITIONER*
- [x] SQL injection UNION attack, retrieving multiple values in a single column — *PRACTITIONER*
- [ ] Blind SQL injection with conditional responses — *PRACTITIONER*
- [ ] Blind SQL injection with conditional errors — *PRACTITIONER*
- [ ] Visible error-based SQL injection — *PRACTITIONER*
- [ ] Blind SQL injection with time delays — *PRACTITIONER*
- [ ] Blind SQL injection with time delays and information retrieval — *PRACTITIONER*
- [ ] Blind SQL injection with out-of-band interaction — *PRACTITIONER*
- [ ] Blind SQL injection with out-of-band data exfiltration — *PRACTITIONER*
- [ ] SQL injection with filter bypass via XML encoding — *PRACTITIONER*


## Cross-site scripting

- [ ] Reflected XSS into HTML context with nothing encoded — *APPRENTICE*
- [ ] Stored XSS into HTML context with nothing encoded — *APPRENTICE*
- [ ] DOM XSS in document.write sink using source location.search — *APPRENTICE*
- [ ] DOM XSS in innerHTML sink using source location.search — *APPRENTICE*
- [ ] DOM XSS in jQuery anchor href attribute sink using location.search source — *APPRENTICE*
- [ ] DOM XSS in jQuery selector sink using a hashchange event — *APPRENTICE*
- [ ] Reflected XSS into attribute with angle brackets HTML-encoded — *APPRENTICE*
- [ ] Stored XSS into anchor href attribute with double quotes HTML-encoded — *APPRENTICE*
- [ ] Reflected XSS into a JavaScript string with angle brackets HTML encoded — *APPRENTICE*
- [ ] DOM XSS in document.write sink using source location.search inside a select element — *PRACTITIONER*
- [ ] DOM XSS in AngularJS expression with angle brackets and double quotes HTML-encoded — *PRACTITIONER*
- [ ] Reflected DOM XSS — *PRACTITIONER*
- [ ] Stored DOM XSS — *PRACTITIONER*
- [ ] Reflected XSS into HTML context with most tags and attributes blocked — *PRACTITIONER*
- [ ] Reflected XSS into HTML context with all tags blocked except custom ones — *PRACTITIONER*
- [ ] Reflected XSS with some SVG markup allowed — *PRACTITIONER*
- [ ] Reflected XSS in canonical link tag — *PRACTITIONER*
- [ ] Reflected XSS into a JavaScript string with single quote and backslash escaped — *PRACTITIONER*
- [ ] Reflected XSS into a JavaScript string with angle brackets and double quotes HTML-encoded and single quotes escaped — *PRACTITIONER*
- [ ] Stored XSS into onclick event with angle brackets and double quotes HTML-encoded and single quotes and backslash escaped — *PRACTITIONER*
- [ ] Reflected XSS into a template literal with angle brackets, single, double quotes, backslash and backticks Unicode-escaped — *PRACTITIONER*
- [ ] Exploiting cross-site scripting to steal cookies — *PRACTITIONER*
- [ ] Exploiting cross-site scripting to capture passwords — *PRACTITIONER*
- [ ] Exploiting XSS to bypass CSRF defenses — *PRACTITIONER*
- [ ] Reflected XSS with AngularJS sandbox escape without strings — *EXPERT*
- [ ] Reflected XSS with AngularJS sandbox escape and CSP — *EXPERT*
- [ ] Reflected XSS with event handlers and href attributes blocked — *EXPERT*
- [ ] Reflected XSS in a JavaScript URL with some characters blocked — *EXPERT*
- [ ] Reflected XSS protected by very strict CSP, with dangling markup attack — *PRACTITIONER*
- [ ] Reflected XSS protected by CSP, with CSP bypass — *EXPERT*


## Cross-site request forgery (CSRF)

- [ ] CSRF vulnerability with no defenses — *APPRENTICE*
- [ ] CSRF where token validation depends on request method — *PRACTITIONER*
- [ ] CSRF where token validation depends on token being present — *PRACTITIONER*
- [ ] CSRF where token is not tied to user session — *PRACTITIONER*
- [ ] CSRF where token is tied to non-session cookie — *PRACTITIONER*
- [ ] CSRF where token is duplicated in cookie — *PRACTITIONER*
- [ ] SameSite Lax bypass via method override — *PRACTITIONER*
- [ ] SameSite Strict bypass via client-side redirect — *PRACTITIONER*
- [ ] SameSite Strict bypass via sibling domain — *PRACTITIONER*
- [ ] SameSite Lax bypass via cookie refresh — *PRACTITIONER*
- [ ] CSRF where Referer validation depends on header being present — *PRACTITIONER*
- [ ] CSRF with broken Referer validation — *PRACTITIONER*


## Clickjacking

- [ ] Basic clickjacking with CSRF token protection — *APPRENTICE*
- [ ] Clickjacking with form input data prefilled from a URL parameter — *APPRENTICE*
- [ ] Clickjacking with a frame buster script — *APPRENTICE*
- [ ] Exploiting clickjacking vulnerability to trigger DOM-based XSS — *PRACTITIONER*
- [ ] Multistep clickjacking — *PRACTITIONER*


## DOM-based vulnerabilities

- [ ] DOM XSS using web messages — *PRACTITIONER*
- [ ] DOM XSS using web messages and a JavaScript URL — *PRACTITIONER*
- [ ] DOM XSS using web messages and JSON.parse — *PRACTITIONER*
- [ ] DOM-based open redirection — *PRACTITIONER*
- [ ] DOM-based cookie manipulation — *PRACTITIONER*
- [ ] Exploiting DOM clobbering to enable XSS — *EXPERT*
- [ ] Clobbering DOM attributes to bypass HTML filters — *EXPERT*


## Cross-origin resource sharing (CORS)

- [ ] CORS vulnerability with basic origin reflection — *APPRENTICE*
- [ ] CORS vulnerability with trusted null origin — *APPRENTICE*
- [ ] CORS vulnerability with trusted insecure protocols — *PRACTITIONER*


## XML external entity (XXE) injection

- [ ] Exploiting XXE using external entities to retrieve files — *APPRENTICE*
- [ ] Exploiting XXE to perform SSRF attacks — *APPRENTICE*
- [ ] Blind XXE with out-of-band interaction — *PRACTITIONER*
- [ ] Blind XXE with out-of-band interaction via XML parameter entities — *PRACTITIONER*
- [ ] Exploiting blind XXE to exfiltrate data using a malicious external DTD — *PRACTITIONER*
- [ ] Exploiting blind XXE to retrieve data via error messages — *PRACTITIONER*
- [ ] Exploiting XInclude to retrieve files — *PRACTITIONER*
- [ ] Exploiting XXE via image file upload — *PRACTITIONER*
- [ ] Exploiting XXE to retrieve data by repurposing a local DTD — *EXPERT*


## Server-side request forgery (SSRF)

- [x] Basic SSRF against the local server — *APPRENTICE*
- [x] Basic SSRF against another back-end system — *APPRENTICE*
- [ ] Blind SSRF with out-of-band detection — *PRACTITIONER*
- [ ] SSRF with blacklist-based input filter — *PRACTITIONER*
- [ ] SSRF with filter bypass via open redirection vulnerability — *PRACTITIONER*
- [ ] Blind SSRF with Shellshock exploitation — *EXPERT*
- [ ] SSRF with whitelist-based input filter — *EXPERT*


## HTTP request smuggling

- [ ] HTTP request smuggling, confirming a CL.TE vulnerability via differential responses — *PRACTITIONER*
- [ ] HTTP request smuggling, confirming a TE.CL vulnerability via differential responses — *PRACTITIONER*
- [ ] Exploiting HTTP request smuggling to bypass front-end security controls, CL.TE vulnerability — *PRACTITIONER*
- [ ] Exploiting HTTP request smuggling to bypass front-end security controls, TE.CL vulnerability — *PRACTITIONER*
- [ ] Exploiting HTTP request smuggling to reveal front-end request rewriting — *PRACTITIONER*
- [ ] Exploiting HTTP request smuggling to capture other users' requests — *PRACTITIONER*
- [ ] Exploiting HTTP request smuggling to deliver reflected XSS — *PRACTITIONER*
- [ ] Response queue poisoning via H2.TE request smuggling — *PRACTITIONER*
- [ ] H2.CL request smuggling — *PRACTITIONER*
- [ ] HTTP/2 request smuggling via CRLF injection — *PRACTITIONER*
- [ ] HTTP/2 request splitting via CRLF injection — *PRACTITIONER*
- [ ] 0.CL request smuggling — *EXPERT*
- [ ] CL.0 request smuggling — *PRACTITIONER*
- [ ] HTTP request smuggling, basic CL.TE vulnerability — *PRACTITIONER*
- [ ] HTTP request smuggling, basic TE.CL vulnerability — *PRACTITIONER*
- [ ] HTTP request smuggling, obfuscating the TE header — *PRACTITIONER*
- [ ] Exploiting HTTP request smuggling to perform web cache poisoning — *EXPERT*
- [ ] Exploiting HTTP request smuggling to perform web cache deception — *EXPERT*
- [ ] Bypassing access controls via HTTP/2 request tunnelling — *EXPERT*
- [ ] Web cache poisoning via HTTP/2 request tunnelling — *EXPERT*
- [ ] Client-side desync — *EXPERT*
- [ ] Server-side pause-based request smuggling — *EXPERT*


## OS command injection

- [x] OS command injection, simple case — *APPRENTICE*
- [x] Blind OS command injection with time delays — *PRACTITIONER*
- [ ] Blind OS command injection with output redirection — *PRACTITIONER*
- [ ] Blind OS command injection with out-of-band interaction — *PRACTITIONER*
- [ ] Blind OS command injection with out-of-band data exfiltration — *PRACTITIONER*


## Server-side template injection

- [ ] Basic server-side template injection — *PRACTITIONER*
- [ ] Basic server-side template injection (code context) — *PRACTITIONER*
- [ ] Server-side template injection using documentation — *PRACTITIONER*
- [ ] Server-side template injection in an unknown language with a documented exploit — *PRACTITIONER*
- [ ] Server-side template injection with information disclosure via user-supplied objects — *PRACTITIONER*
- [ ] Server-side template injection in a sandboxed environment — *EXPERT*
- [ ] Server-side template injection with a custom exploit — *EXPERT*


## Path traversal

- [x] File path traversal, simple case — *APPRENTICE*
- [ ] File path traversal, traversal sequences blocked with absolute path bypass — *PRACTITIONER*
- [ ] File path traversal, traversal sequences stripped non-recursively — *PRACTITIONER*
- [ ] File path traversal, traversal sequences stripped with superfluous URL-decode — *PRACTITIONER*
- [ ] File path traversal, validation of start of path — *PRACTITIONER*
- [ ] File path traversal, validation of file extension with null byte bypass — *PRACTITIONER*


## Access control vulnerabilities

- [x] Unprotected admin functionality — *APPRENTICE*
- [x] Unprotected admin functionality with unpredictable URL — *APPRENTICE*
- [x] User role controlled by request parameter — *APPRENTICE*
- [ ] User role can be modified in user profile — *APPRENTICE*
- [ ] User ID controlled by request parameter — *APPRENTICE*
- [x] User ID controlled by request parameter, with unpredictable user IDs — *APPRENTICE*
- [ ] User ID controlled by request parameter with data leakage in redirect — *APPRENTICE*
- [x] User ID controlled by request parameter with password disclosure — *APPRENTICE*
- [ ] Insecure direct object references — *APPRENTICE*
- [ ] URL-based access control can be circumvented — *PRACTITIONER*
- [ ] Method-based access control can be circumvented — *PRACTITIONER*
- [ ] Multi-step process with no access control on one step — *PRACTITIONER*
- [ ] Referer-based access control — *PRACTITIONER*


## Authentication

- [x] Username enumeration via different responses — *APPRENTICE*
- [x] 2FA simple bypass — *APPRENTICE*
- [x] Password reset broken logic — *APPRENTICE*
- [x] Username enumeration via subtly different responses — *PRACTITIONER*
- [x] Username enumeration via response timing — *PRACTITIONER*
- [x] Broken brute-force protection, IP block — *PRACTITIONER*
- [ ] Username enumeration via account lock — *PRACTITIONER*
- [ ] 2FA broken logic — *PRACTITIONER*
- [ ] Brute-forcing a stay-logged-in cookie — *PRACTITIONER*
- [ ] Offline password cracking — *PRACTITIONER*
- [ ] Password reset poisoning via middleware — *PRACTITIONER*
- [ ] Password brute-force via password change — *PRACTITIONER*
- [ ] Broken brute-force protection, multiple credentials per request — *EXPERT*
- [ ] 2FA bypass using a brute-force attack — *EXPERT*


## WebSockets

- [x] Manipulating WebSocket messages to exploit vulnerabilities — *APPRENTICE*
- [ ] Cross-site WebSocket hijacking — *PRACTITIONER*
- [ ] Manipulating the WebSocket handshake to exploit vulnerabilities — *PRACTITIONER*


## Web cache poisoning

- [ ] Web cache poisoning with an unkeyed header — *PRACTITIONER*
- [ ] Web cache poisoning with an unkeyed cookie — *PRACTITIONER*
- [ ] Web cache poisoning with multiple headers — *PRACTITIONER*
- [ ] Targeted web cache poisoning using an unknown header — *PRACTITIONER*
- [ ] Web cache poisoning via an unkeyed query string — *PRACTITIONER*
- [ ] Web cache poisoning via an unkeyed query parameter — *PRACTITIONER*
- [ ] Parameter cloaking — *PRACTITIONER*
- [ ] Web cache poisoning via a fat GET request — *PRACTITIONER*
- [ ] URL normalization — *PRACTITIONER*
- [ ] Web cache poisoning to exploit a DOM vulnerability via a cache with strict cacheability criteria — *EXPERT*
- [ ] Combining web cache poisoning vulnerabilities — *EXPERT*
- [ ] Cache key injection — *EXPERT*
- [ ] Internal cache poisoning — *EXPERT*


## Insecure deserialization

- [ ] Modifying serialized objects — *APPRENTICE*
- [ ] Modifying serialized data types — *PRACTITIONER*
- [ ] Using application functionality to exploit insecure deserialization — *PRACTITIONER*
- [ ] Arbitrary object injection in PHP — *PRACTITIONER*
- [ ] Exploiting Java deserialization with Apache Commons — *PRACTITIONER*
- [ ] Exploiting PHP deserialization with a pre-built gadget chain — *PRACTITIONER*
- [ ] Exploiting Ruby deserialization using a documented gadget chain — *PRACTITIONER*
- [ ] Developing a custom gadget chain for Java deserialization — *EXPERT*
- [ ] Developing a custom gadget chain for PHP deserialization — *EXPERT*
- [ ] Using PHAR deserialization to deploy a custom gadget chain — *EXPERT*


## Information disclosure

- [ ] Information disclosure in error messages — *APPRENTICE*
- [ ] Information disclosure on debug page — *APPRENTICE*
- [ ] Source code disclosure via backup files — *APPRENTICE*
- [ ] Authentication bypass via information disclosure — *APPRENTICE*
- [ ] Information disclosure in version control history — *PRACTITIONER*


## Business logic vulnerabilities

- [ ] Excessive trust in client-side controls — *APPRENTICE*
- [ ] High-level logic vulnerability — *APPRENTICE*
- [ ] Inconsistent security controls — *APPRENTICE*
- [ ] Flawed enforcement of business rules — *APPRENTICE*
- [ ] Low-level logic flaw — *PRACTITIONER*
- [ ] Inconsistent handling of exceptional input — *PRACTITIONER*
- [ ] Weak isolation on dual-use endpoint — *PRACTITIONER*
- [ ] Insufficient workflow validation — *PRACTITIONER*
- [ ] Authentication bypass via flawed state machine — *PRACTITIONER*
- [ ] Infinite money logic flaw — *PRACTITIONER*
- [ ] Authentication bypass via encryption oracle — *PRACTITIONER*
- [ ] Bypassing access controls using email address parsing discrepancies — *EXPERT*


## HTTP Host header attacks

- [ ] Basic password reset poisoning — *APPRENTICE*
- [ ] Host header authentication bypass — *APPRENTICE*
- [ ] Web cache poisoning via ambiguous requests — *PRACTITIONER*
- [ ] Routing-based SSRF — *PRACTITIONER*
- [ ] SSRF via flawed request parsing — *PRACTITIONER*
- [ ] Host validation bypass via connection state attack — *PRACTITIONER*
- [ ] Password reset poisoning via dangling markup — *EXPERT*


## OAuth authentication

- [ ] Authentication bypass via OAuth implicit flow — *APPRENTICE*
- [ ] SSRF via OpenID dynamic client registration — *PRACTITIONER*
- [ ] Forced OAuth profile linking — *PRACTITIONER*
- [ ] OAuth account hijacking via redirect_uri — *PRACTITIONER*
- [ ] Stealing OAuth access tokens via an open redirect — *PRACTITIONER*
- [ ] Stealing OAuth access tokens via a proxy page — *EXPERT*


## File upload vulnerabilities

- [x] Remote code execution via web shell upload — *APPRENTICE*
- [x] Web shell upload via Content-Type restriction bypass — *APPRENTICE*
- [ ] Web shell upload via path traversal — *PRACTITIONER*
- [ ] Web shell upload via extension blacklist bypass — *PRACTITIONER*
- [ ] Web shell upload via obfuscated file extension — *PRACTITIONER*
- [ ] Remote code execution via polyglot web shell upload — *PRACTITIONER*
- [ ] Web shell upload via race condition — *EXPERT*


## JWT

- [ ] JWT authentication bypass via unverified signature — *APPRENTICE*
- [ ] JWT authentication bypass via flawed signature verification — *APPRENTICE*
- [ ] JWT authentication bypass via weak signing key — *PRACTITIONER*
- [ ] JWT authentication bypass via jwk header injection — *PRACTITIONER*
- [ ] JWT authentication bypass via jku header injection — *PRACTITIONER*
- [ ] JWT authentication bypass via kid header path traversal — *PRACTITIONER*
- [ ] JWT authentication bypass via algorithm confusion — *EXPERT*
- [ ] JWT authentication bypass via algorithm confusion with no exposed key — *EXPERT*


## Essential skills

- [ ] Discovering vulnerabilities quickly with targeted scanning — *PRACTITIONER*
- [ ] Scanning non-standard data structures — *PRACTITIONER*


## Prototype pollution

- [ ] Client-side prototype pollution via browser APIs — *PRACTITIONER*
- [ ] DOM XSS via client-side prototype pollution — *PRACTITIONER*
- [ ] DOM XSS via an alternative prototype pollution vector — *PRACTITIONER*
- [ ] Client-side prototype pollution via flawed sanitization — *PRACTITIONER*
- [ ] Client-side prototype pollution in third-party libraries — *PRACTITIONER*
- [ ] Privilege escalation via server-side prototype pollution — *PRACTITIONER*
- [ ] Detecting server-side prototype pollution without polluted property reflection — *PRACTITIONER*
- [ ] Bypassing flawed input filters for server-side prototype pollution — *PRACTITIONER*
- [ ] Remote code execution via server-side prototype pollution — *PRACTITIONER*
- [ ] Exfiltrating sensitive data via server-side prototype pollution — *EXPERT*


## GraphQL API vulnerabilities

- [ ] Accessing private GraphQL posts — *APPRENTICE*
- [ ] Accidental exposure of private GraphQL fields — *PRACTITIONER*
- [ ] Finding a hidden GraphQL endpoint — *PRACTITIONER*
- [ ] Bypassing GraphQL brute force protections — *PRACTITIONER*
- [ ] Performing CSRF exploits over GraphQL — *PRACTITIONER*


## Race conditions

- [ ] Limit overrun race conditions — *APPRENTICE*
- [ ] Bypassing rate limits via race conditions — *PRACTITIONER*
- [ ] Multi-endpoint race conditions — *PRACTITIONER*
- [ ] Single-endpoint race conditions — *PRACTITIONER*
- [ ] Exploiting time-sensitive vulnerabilities — *PRACTITIONER*
- [ ] Partial construction race conditions — *EXPERT*


## NoSQL injection

- [ ] Detecting NoSQL injection — *APPRENTICE*
- [ ] Exploiting NoSQL operator injection to bypass authentication — *APPRENTICE*
- [ ] Exploiting NoSQL injection to extract data — *PRACTITIONER*
- [ ] Exploiting NoSQL operator injection to extract unknown fields — *PRACTITIONER*


## API testing

- [x] Exploiting an API endpoint using documentation — *APPRENTICE*
- [ ] Exploiting server-side parameter pollution in a query string — *PRACTITIONER*
- [x] Finding and exploiting an unused API endpoint — *PRACTITIONER*
- [x] Exploiting a mass assignment vulnerability — *PRACTITIONER*
- [ ] Exploiting server-side parameter pollution in a REST URL — *EXPERT*


## Web LLM attacks

- [x] Exploiting LLM APIs with excessive agency — *APPRENTICE*
- [x] Exploiting vulnerabilities in LLM APIs — *PRACTITIONER*
- [ ] Indirect prompt injection — *PRACTITIONER*
- [ ] Exploiting insecure output handling in LLMs — *EXPERT*


## Web cache deception

- [ ] Exploiting path mapping for web cache deception — *APPRENTICE*
- [ ] Exploiting path delimiters for web cache deception — *PRACTITIONER*
- [ ] Exploiting origin server normalization for web cache deception — *PRACTITIONER*
- [ ] Exploiting cache server normalization for web cache deception — *PRACTITIONER*
- [ ] Exploiting exact-match cache rules for web cache deception — *EXPERT*
