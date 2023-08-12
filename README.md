# GoogleGuryere-exercise
Completing google guryere

1. Setup Google Gruyere Codelab to perform this CW, https://google-gruyere.appspot.com/start ,
by creating your instance.
2. You will be presented with the following challenges:
a. XSS Challenges:
i. File Upload XSS: Can you upload a file that allows you to execute arbitrary
script on the google-gruyere.appspot.com domain?
ii. Reflected XSS: Find a reflected XSS attack. What we want is a URL that when
clicked on will execute a script
iii. Stored XSS: Now find a stored XSS. What we want to do is put a script in a place
where Gruyere will serve it back to another user.
iv. Stored XSS via HTML Attribute: you can also do XSS by injecting a value into an
HTML attribute. Inject a script by setting the colour value in a profile
v. Stored XSS via AJAX: Find an XSS attack that uses a bug in Gruyere's AJAX code
vi. Reflected XSS via AJAX: Find a URL that when clicked on will execute a script
using one of Gruyere's AJAX features
b. Client State Manipulation:
i. Elevation of Privilege: Convert your account to an administrator account
ii. Cookie Manipulation: Get Gruyere to issue you a cookie for someone else's
account
c. XSRF: Find a way to get someone to delete one of their Gruyere snippets
d. XSSI: Find a way to read someone else's private snippet using XSSI
e. Path Traversal:
i. Information disclosure via path traversal: Find a way to read secret.txt from a
running Gruyere server
ii. Data tampering via path traversal: Find a way to replace secret.txt on a running
Gruyere server
f. Denial of Service:
i. DoS Quit the Server: Find a way to make the server quit
ii. DoS Overloading the Server: find a way to overload the server when it
processed a request
g. Code Execution: Find a code execution exploit
h. Configuration Vulnerabilities:
i. Information disclosure 1: Read the contents of the database off of a running
server by exploiting a configuration vulnerability
ii. Information disclosure 2: Even after implementing the fix described above, an
attacker can undo it and execute the attack! How can that be?
iii. Information disclosure 3: Even after implementing the fixes described above, a
similar attack is still possible through a different attack vector. Can you find it?
i. AJAX Vulnerabilities:
i. DoS via AJAX: Find an attack that prevents users from seeing their private
snippets on the home page
ii. Phishing via AJAX: Find a way to change the sign in link in the upper right
corner to point to https://evil.example.com.
3. Explore all offered scenarios to find security vulnerabilities related to all OWASP top 10
vulnerabilities, exploit them, then mitigate them.
4. Using your wording and writing style: Provide a report to the management explaining the
discovered flaws and the security posture of the application. List how you found each
vulnerability, how you fixed it, and what was the security impact. Support your report with
screenshots of vulnerabilities found on Gruyere.
