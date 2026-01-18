# Security Policy

A security policy outlines how your project handles vulnerabilities, reports, and disclosures. It ensures contributors and users know how to report issues safely and responsibly, helping maintain the integrity of the project.

> [!NOTE]
> 📌 **Remember, security is everyone’s responsibility, and compliance does not equal security.**

## Examples

> [!NOTE]
> The examples *we* provided are opinionated and intended as guidance. We encourage you to explore other approaches, adapt them to your workflow, and expand upon them to fit the specific needs of your project.

- [SECURITY.md](/security-policy/SECURITY.md)

Common elements you might include in a security policy:

1. **Reporting Vulnerabilities**
   - How to report a security issue (e.g., email, GitHub Security Advisory).
   - Recommended level of detail in the report.
2. **Response Process**
   - How maintainers will acknowledge and triage reports.
   - Expected timelines for responses and patches.
3. **Disclosure Guidelines**
   - Coordinated disclosure process to avoid public exposure before a fix is available.
   - Whether the project follows a responsible disclosure policy.
4. **Supported Versions**
   - Which versions are actively maintained and supported for security fixes.
5. **References & Resources**
   - Links to relevant security standards or practices your project follows.

## Resources

- [GitHub Docs: Adding a security policy to your repository](https://docs.github.com/en/code-security/getting-started/adding-a-security-policy-to-your-repository)
- [Mozilla Wiki: GitHub/Repository Security](https://wiki.mozilla.org/GitHub/Repository_Security)
- [OWASP Top 10 Risks for Open Source Software](https://owasp.org/www-project-open-source-software-top-10/)
- [OWASP: Free for Open Source Application Security Tools](https://owasp.org/www-community/Free_for_Open_Source_Application_Security_Tools)
- [Open Source Security Foundation (OpenSSF) Guides](https://openssf.org/resources/guides/)

## OSS Project Security Policy Examples

- [Kubernetes](https://github.com/kubernetes/kubernetes?tab=security-ov-file)
- [Node](https://github.com/nodejs/node/blob/main/SECURITY.md)
- [Various Apache Projects](https://github.com/orgs/apache/repositories)
  > Select the `Security` tab on any project to view its security policy.

## Tools

Tools and practices to manage security in your project:

- **GitHub Security Advisories** – For confidential vulnerability reporting and tracking.
- **Dependabot / Snyk / GitHub Dependabot Alerts** – Automated dependency vulnerability scanning.
- **Static Analysis Tools / Linters** – To detect potential security issues in code.
- **Automated Tests & CI/CD** – Ensure security fixes are tested before release.
- **Encryption and Key Management Tools** – For handling sensitive data securely.
