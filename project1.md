[Back to Portfolio](./)

Windows Cybersecurity Compliance Check using Python
===============

-   **Class:** CSCI 301 
-   **Grade:** 100
-   **Language(s):** Python
-   **Source Code Repository:** [features/mastering-markdown](https://guides.github.com/features/mastering-markdown/)  
    (Please [email me](mailto:csneal@student.csuniv.edu) to request access.)

## Project description

For the final project, I selected the Cybersecurity option, which required automating compliance checks for five rules from an operating system CIS Benchmark or DoD STIG. I implemented a Python script that evaluates a Windows system against five essential security controls drawn from these standards.
The script checks:
1. Windows Defender Antivirus — verifies that the service is running.
2. Windows Firewall — ensures all profiles (Domain, Private, Public) are enabled.
3. Password Policy — confirms the minimum password length is at least 14 characters.
4. Guest Account Status — checks that the Guest account is disabled.
5. Microsoft SmartScreen — verifies that SmartScreen protection for Microsoft Edge is enabled.

Each check uses Python’s subprocess module to run Windows commands or query registry values, then interprets the results to determine whether the system is Compliant, Non‑Compliant, or Unable to Verify.
This project demonstrates practical skills in:
- Interpreting CIS/STIG security requirements
- Querying Windows configuration programmatically
- Automating compliance checks safely (without modifying system settings)
- Producing readable, actionable security reports 

## How to compile and run the program

How to compile (if applicable) and run the project.

```bash
python compliance_check.py
```

## UI Design

Almost every program requires user interaction, even command-line programs. Include in this section the tasks the user can complete and what the program does. You don't need to include how it works here; that information may go in the project description or in an additional section, depending on its significance.

Although command‑line based, the script is designed to function like a lightweight workstation compliance tool. Users can:
- Run all checks with a single command
- View clear pass/fail results for each rule
- Read short explanations of what each rule means
- Identify which settings require remediation 



For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
