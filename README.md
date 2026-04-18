# FUTURE_CS_01 
A read-only vulnerability assessment was conducted on the public OWASP Juice Shop demo
(https://demo.owasp-juice.shop). The conduct of this security assessment was undertaken in the
cyber-friendly Kali Linux operating system, and it uncovered network exposure, security header
configuration, cookie security configuration, and client-side traffic response assessment without performing destructive exploitation. The network exposure assessment revealed open ports that could expose the site by enabling
unauthorized communication with the server. It was able to answer the question: “Is the target
website showing too much to the public?” The security header and cookie security configuration
assessments ensured that the website provides sufficient security instructions to the browser
(Chrome, Edge, etc.) and reminds it to keep the cookies safe and protected. (Cookies are like name
tags that are sent to the browser, and their leakage might cause issues like giving the attacker the
ability to pretend to be the user, and many more.) The client-side traffic response assessment is
performed by watching the conversation between the website and the visitor’s browser, using the
DevTools on a browser. Finally, in this assessment, I wanted to make sure that the website isn’t
exposing too much to the public. In the overall assessment, I have detected 9 vulnerabilities that could
be categorized as low/informational-level, medium-level, and high-level vulnerabilities. Some
considerable remediation tips have also been included at the end of the individual vulnerability
descriptions
