
*Jothis Notes**
1. **Test SSH Configuration**:
   - Ensure SSH configurations are secure and properly set up to prevent unauthorized access.

2. **TLS Misconfiguration**:
   - Check for misconfigurations in TLS/SSL settings to ensure secure communication.

3. **Dirsearch Syntax**:
   - Use a tool like `dirsearch` to scan for directories on a web server.
   - Example syntax: `dirsearch -u <URL> -r -R 3 -t 200`

4. **Security Headers**:
   - Verify if security headers like CSP, X-Content-Type-Options, and X-Frame-Options are correctly set.

5. **JavaScript Security**:
   - Use tools like Retire.js to check for known vulnerabilities in JavaScript libraries.
   - Manually review JavaScript files for sensitive information exposure.

6. **Wappalyzer**:
   - Use Wappalyzer to identify technologies used on a website.

7. **Robots.txt**:
   - Review the `robots.txt` file for information about restricted areas of a website.

8. **View Page Source**:
   - Examine the HTML source code of web pages for potential vulnerabilities.

9. **Inspect Source**:
   - Use browser developer tools to inspect and search the source code for specific content.

10. **Create an Account**:
    - Sign up for an account on a website to test its registration process.

11. **Scope Configuration**:
    - Configure a scope for security testing to limit the testing to specific URLs.

12. **Proxy Settings**:
    - Set up a proxy to intercept and analyze web traffic.

13. **Password Checks**:
    - Verify that password and confirmation fields match.
    - Check for password complexity and length requirements.

14. **Response Modification**:
    - Use proxy tools to modify and analyze responses, highlighting fields.

15. **Security Issue Testing**:
    - Attempt to exploit security issues, but only in a legal and authorized context.

16. **HTML Injection**:
    - Test for HTML injection vulnerabilities using payloads like `<h1>test</h1>`.

17. **Cross-Site Scripting (XSS)**:
    - Test for XSS vulnerabilities with payloads like `<script>alert('1')</script>`.

18. **XSS Fuzzing**:
    - Test for reflected XSS with various payloads.

19. **Feedback Form**:
    - Test comment forms for potential vulnerabilities, such as blind XSS.

20. **SQL Injection**:
    - Test for SQL injection vulnerabilities, ensuring data validation and sanitization.

21. **File Upload Testing**:
    - Test file upload functionality for security vulnerabilities, such as directory traversal.

22. **Insecure Direct Object References (IDOR)**:
    - Check for IDOR vulnerabilities, where one user can access another's data.

23. **Server-Side Request Forgery (SSRF)**:
    - Test for SSRF vulnerabilities by manipulating URLs to access internal resources.

24. **File Upload Media Type**:
    - Test for file upload vulnerabilities related to media types and extensions.

25. **Reflected XSS**:
    - Test for reflected XSS with payloads like `<img src="#" onclick=alert(document.domain)>`.

26. **Access Control Testing**:
    - Test access control by trying to access restricted pages.

27. **CSRF Testing**:
    - Test for Cross-Site Request Forgery vulnerabilities.

28. **Token Handling**:
    - Check how tokens are stored in local storage and ensure their security.

29. **Basket Manipulation**:
    - Modify the shopping basket and inspect requests and responses.

30. **Secure Flag**:
    - Check if the "secure" flag is set for cookies.

31. **JavaScript Path Testing**:
    - Search for paths and vulnerabilities in JavaScript files.

32. **User Access Testing**:
    - Test user roles and permissions, ensuring users can't access unauthorized pages.

33. **Page Enumeration**:
    - Enumerate pages using incremental URLs (e.g., /1, /2, /3) for potential vulnerabilities.

34. **Negative Quantity Testing**:
    - Test for negative quantity inputs during shopping.

35. **2FA Configuration**:
    - Evaluate two-factor authentication configurations for security.

36. **Change Password**:
    - Test password change functionality for security and CSRF.

37. **Token Storage**:
    - Investigate token storage mechanisms in the local storage.

38. **Review and Analyze Traffic**:
    - Use tools like Burp Suite to analyze and manipulate requests.

39. **SQL Injection with SQLMap**:
    - Use SQLMap to detect and exploit SQL injection vulnerabilities in a controlled environment.

40. **Application Inspection**:
    - Verify secure flag settings in cookies.

Please remember to perform these tasks only on systems and applications for which you have explicit authorization, and always follow ethical hacking guidelines and legal requirements. Unauthorized hacking can lead to serious legal consequences.
