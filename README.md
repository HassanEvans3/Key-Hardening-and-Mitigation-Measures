# Key-Hardening-and-Mitigation-Measures


This project focused on implementing key system hardening and mitigation strategies to enhance data security. A major priority was ensuring that all users and groups had proper access controls. This involved regularly updating group memberships and permissions, especially as employees join, leave, or change roles. During the project, several user directories required manual corrections to align file access with organizational roles.

Strong password policies were another critical focus. Enforcing complex password requirements helps prevent unauthorized access by making it harder for attackers to guess or crack credentials.

Limiting sudo access was also emphasized. Since users with sudo privileges can make significant changes to the system—including creating backdoors or altering sensitive files—it is crucial to restrict this level of access. For example, Sherlock was given full sudo rights, while Watson, Mycroft, and the research group were granted limited permissions to run specific scripts.

Lastly, maintaining up-to-date system packages is essential for reducing vulnerabilities. Regularly running apt update and apt upgrade ensures that known security flaws are patched, helping to safeguard the system from exploits and malware.
