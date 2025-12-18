**Security Testing for Web Applications**

**COMPANY** : CODTECH IT SOLUTIONS 

**NAME** :    SANDHIYA P

**INTERN ID**:CT04DR2320

**DOMAIN** :  SOFTWARE TESTING 

**DURATION** : 4 WEEKS

**MENTOR** : NEELA SANTHOSH

**DESCRIPTION**: The objective of this task is to identify a security vulnerability in a web application using basic manual security testing techniques. As per the task instructions, any one vulnerability such as SQL Injection or Cross-Site Scripting (XSS) is sufficient. In this task, Cross-Site Scripting (XSS) vulnerability was selected and tested.

  The testing was performed on a deliberately vulnerable web application available for security practice. The target application used for this task was http://testphp.vulnweb.com/userinfo.php, which is designed to demonstrate common web vulnerabilities. This application accepts user input and displays it back to the user without proper validation.

  To identify the vulnerability, a simple XSS payload <script>alert(1)</script> was entered into the input field of the application. After submitting the form, the application executed the injected script instead of treating it as normal text. As a result, a browser alert popup displaying the value “1” appeared on the screen.

  The appearance of the alert popup confirms that the application is vulnerable to Cross-Site Scripting (XSS). This occurs because the application does not properly sanitize or validate user input before rendering it on the web page. An attacker can exploit this vulnerability to execute malicious scripts in a user’s browser.

  XSS vulnerabilities are dangerous because they can be used to steal sensitive information such as session cookies, perform unauthorized actions on behalf of users, or redirect users to malicious websites. This can lead to serious security and privacy issues.

  In conclusion, the tested web application is vulnerable to Cross-Site Scripting due to improper input validation. To prevent such vulnerabilities, the application should implement proper input sanitization, output encoding, and security controls to ensure that user-supplied data is handled safely.
  
XSS_Alert_Popup
![Image](https://github.com/user-attachments/assets/b2ab7d5a-fe48-46ee-aa23-2a29b1389c28)


XSS_Payload_Reflected
![Image](https://github.com/user-attachments/assets/79bd9e58-c139-4ca5-baaf-d089fb33e978)
