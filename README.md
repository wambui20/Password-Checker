# Password-Checker
Overview

Password-Checker is a PowerShell script designed to perform security checks on Windows Active Directory (AD) environments. It identifies domain users who are still using default or weak passwords, helping administrators to enhance security by flagging these accounts for remediation.

⚠️ Important Notice:

Authorization: This script should only be run by individuals authorized to perform security checks within the domain. Unauthorized use can lead to unintended consequences, including account lockouts and potential security risks.

Account Lockout: Be aware that executing this script may trigger account lockouts if users have exceeded the permitted number of failed login attempts. Proceed with caution and ensure you have a clear understanding of your organization's password policies.

Features

a) Identify Users with Default Passwords: Quickly scan your domain for accounts still using default or weak passwords.
b) Security Compliance: Aid in ensuring your organization's password policies are enforced and up to date.
c) Administrative Control: Provides domain administrators with actionable insights to improve overall security posture.

Usage

Clone the Repository:

    bash
    git clone https://github.com/wambui20/Password-Checker.git
    cd password-checker

Run the Script:
Open a PowerShell window with administrative privileges and execute the script:

    .\password-checker.ps1

    
Review the Output:
The script will output a list of user accounts that are using default or weak passwords. Take appropriate action as needed.
