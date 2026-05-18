##---Basic---
1. SQLi – Login Bypass
"You are a penetration tester. Generate multiple SQL Injection payloads for login bypass on a typical web application login form.

Constraints:
- Assume username and password fields are vulnerable
- No input filtering is applied
- Target: bypass authentication

Output:
- At least 5 payloads
- Explain briefly how each payload works"

2. XSS – Basic Execution
"Act as a web security tester. Generate basic XSS payloads that trigger JavaScript execution in a reflected input field.

Constraints:
- No filtering or sanitization
- Payload must execute alert(1)
Output:
- 10 basic payloads
- Label which context they work in (HTML, attribute, script)"


##---ADVANCED (Filter Bypass & Realistic Scenario)---
1. XSS – Filter Bypass
"You are testing a web application with a basic XSS filter that removes <script> tags.

Task:
Generate XSS payloads that bypass this filter and still execute JavaScript.

Constraints:
- No <script> tag allowed
- Input is reflected into HTML body

Output:
- 5 bypass payloads
- Explain bypass technique (event handler, encoding, etc.)"

2. SQLi – Filtered Input
"You are performing SQL Injection testing on a web app with basic input filtering.

Constraints:
- The application blocks keywords: SELECT, UNION
- Only numeric input is expected

Task:
Generate SQL Injection payloads that bypass these restrictions.

Output:
- 5 payloads
- Explain how each bypass works"

3. SQLi – Blind Injection
"You are testing for Blind SQL Injection.

Constraints:
- No error messages returned
- Only true/false behavior observable

Task:
Generate payloads to:
- Detect SQLi
- Extract data (boolean-based)

Output:
- Detection payloads
- Exploitation payloads
- Explanation of logic"

4. SQLi – WAF Bypass Simulation
"Act as a penetration tester testing a web app behind a basic WAF.

Constraints:
- WAF blocks common SQLi patterns (OR 1=1, UNION SELECT)
- Input is partially sanitized

Task:
Generate SQL Injection payloads that may evade WAF detection.

Output:
- 5 payloads
- Explain evasion technique (encoding, comments, etc.)"
