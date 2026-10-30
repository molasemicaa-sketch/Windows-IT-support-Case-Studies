## Case Study 09: Account Locked

### Problem Statement

An employee reports that they cannot access their Windows computer or company account because the account has been locked. When attempting to sign in, Windows displays a message indicating that the account is locked or that the employee cannot sign in at this time. The employee is unable to access work files, applications, and company resources needed to complete an important work assignment.

### Initial Questions

1. What exact error message appears when the employee attempts to sign in?

2. Is the locked account a local Windows account, a Microsoft account, or a company-managed domain account?

3. Did the employee recently enter an incorrect password several times or change their password?

4. Can the employee access other company services, or is the lockout affecting all accounts and devices associated with the employee?

### Possible Causes

- Multiple unsuccessful login attempts triggered the account lockout policy.

- An outdated saved password is being used by a device, application, or background service.

- Another person or automated process is repeatedly attempting to sign in to the account.

- The account has been disabled or restricted by an administrator.

- A security policy has temporarily locked the account after detecting suspicious login activity.

### Troubleshooting Process

1. **Check the error message.** Review the message displayed on the Windows sign-in screen to determine whether the account is locked, disabled, or experiencing a password-related issue. Record the exact message for further investigation.

2. **Verify the account details.** Confirm that the employee is selecting the correct account and entering the correct username. Check the keyboard layout and Caps Lock status to rule out incorrect password entry.

3. **Determine the account type.** Identify whether the employee uses a local Windows account, a Microsoft account, or a company-managed account. Each account type may require a different recovery procedure.

4. **Avoid repeated login attempts.** Stop entering passwords repeatedly, as additional attempts may extend the lockout or trigger further security restrictions. Follow the organization's account recovery instructions.

5. **Check the lockout status.** For a company-managed account, contact the IT administrator to determine whether the account is temporarily locked, disabled, or subject to another security restriction. The administrator can review available authentication logs and lockout events.

6. **Investigate repeated failed sign-ins.** If the account repeatedly becomes locked, check whether a phone, another computer, a mapped network drive, or an application is attempting to authenticate with an outdated password. If suspicious activity is suspected, escalate the incident to the security team.

7. **Restore account access.** Follow the approved recovery process for the account type. An authorized administrator may unlock a company-managed account when permitted by policy. If the password is forgotten or compromised, perform an appropriate password reset and address any security concerns before restoring normal access.

### Resolution

For this example, suppose the investigation identifies multiple unsuccessful login attempts as the cause of the employee's account lockout.

The technician confirms that the employee's company-managed account has been temporarily locked after several incorrect password entries. After verifying the employee's identity and checking the account status, the authorized IT administrator unlocks the account in accordance with company policy.

The technician asks the employee to sign in using the correct credentials and verifies that the account can access the Windows desktop and required company applications. The technician also advises the employee to check any other devices that may be using outdated saved credentials.

The employee confirms that access has been restored and resumes the work assignment.

## 6. Preventive Measures

- Use the correct login credentials and avoid repeatedly guessing passwords.

- Keep saved credentials updated on authorized devices and applications.

- Configure approved password recovery methods and keep recovery information current.

- Enable multifactor authentication where supported and required by company policy.

- Monitor recurring account lockouts and investigate unusual authentication activity.

- Never share passwords or verification codes with unauthorized individuals.

- Report unexpected or repeated account lockouts to IT support promptly.

- Follow company security policies for password changes, account recovery, and identity verification.

### Conclusion

The case demonstrates a systematic approach to troubleshooting account lockouts. By reviewing error messages, verifying account details, identifying the account type, investigating failed sign-in attempts, and following approved account recovery procedures, a technician can restore access safely and efficiently. Proper credential management and monitoring of suspicious authentication activity help prevent repeated lockouts and protect company accounts from unauthorized access.
