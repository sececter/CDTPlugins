# CDTPlugins
CDT is a tool used to detect the coding style warnings, potential programming problems, security vulnerabilities and syntax and semantics errors. In this project I have developed plug-ins in Java to detect the vulnerabilities such as Use of a One-Way Hash without a Salt, Integer Overflow or Wraparound, Uncontrolled Format String, Improper Restriction of Excessive Authentication Attempts, Use of a Broken or Risky Cryptographic Algorithm and Use of Potentially Dangerous Function. These vulnerabilities are mentioned in “2011 CWE/SANS Top 25 Most Dangerous Software Errors”, document version: 1.0.3, September 13, 2011, by Bob Martin (MITRE), Mason Brown (SANS), Alan Paller (SANS), Dennis Kirby (SANS). For instance, if there is an integer overflow in a C++ code, CDT will display a colored (color depends on the type of vulnerability) bug in the side bar of the Eclipse IDE during run time, as a warning to the programmer. In this way some of the vulnerabilities which can introduce security flaws in C/C++ code can be easily detected and eliminated.
