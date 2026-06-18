# Cyber Security Task 01

## Part B: Password Security Review

**1. What makes a strong password?**
A strong password is long (at least 12-14 characters) and complex, incorporating a mix of uppercase and lowercase letters, numbers, and special characters. It should be unique, unpredictable, and avoid using dictionary words, common substitutions, or personal information (like names, birthdays, or pet names).

**2. Why should passwords be unique?**
Passwords must be unique to prevent credential stuffing attacks. If a user reuses the same password across multiple sites and one of those sites suffers a data breach, attackers will automatically try that compromised username/password combination on hundreds of other services (like email, banking, or social media). Unique passwords ensure that a breach on one platform does not compromise your accounts on others.

**3. What is Multi-Factor Authentication (MFA)?**
MFA is a security mechanism that requires a user to provide two or more different forms of verification before granting access to an account or system. These factors typically include something you know (a password or PIN), something you have (a smartphone authenticator app or a hardware security key), or something you are (biometrics like a fingerprint or facial recognition).

**4. What are the risks of password reuse?**
The primary risk of password reuse is the domino effect it creates following a data breach. Once a reused password is leaked from one poorly secured website, threat actors can use automated tools to gain unauthorized access to your more critical accounts (like email or banking) that share the same credentials, leading to identity theft, financial loss, or unauthorized data access.

**Password Policy Best Practices:**
1. **Length over Complexity:** Mandate a minimum password length of 14 characters.
2. **Eliminate Dictionary Words:** Prohibit the use of common dictionary words, predictable patterns (like "Qwerty123!"), and personal information.
3. **Unique Passwords Only:** Strictly prohibit password reuse across different applications and services.
4. **Mandatory MFA:** Require Multi-Factor Authentication (MFA) to be enabled on all accounts, prioritizing authenticator apps or hardware keys over SMS-based codes.
5. **Use a Password Manager:** Encourage or require the use of a reputable, encrypted password manager to securely generate and store unique credentials.

---

## Part C: Online Account Security Check

| Account | MFA Enabled? | Strong Password? | Recovery Email Configured? |
| :--- | :---: | :---: | :---: |
| Google | Yes | Yes | Yes |
| GitHub | Yes | Yes | Yes |
| LinkedIn | Yes | Yes | Yes |

*Note: Actual passwords are not shared.*

---

## Part D: Cyber Threat Research

**1. Phishing**
*   **Definition:** A social engineering attack where malicious actors impersonate a trusted entity (like a bank, employer, or popular service) via email, text, or phone to deceive victims into revealing sensitive information, such as login credentials or credit card numbers.
*   **Real-world Example:** The 2016 spear-phishing attack against John Podesta, the chairman of Hillary Clinton's presidential campaign. Attackers sent a fake Google security alert requesting him to reset his password, which led to the massive leak of his emails.
*   **Prevention Methods:** Verify sender addresses carefully, avoid clicking on unsolicited links or attachments, use email filtering/anti-spam tools, and enable MFA to render stolen passwords useless.

**2. Malware**
*   **Definition:** An umbrella term for malicious software—including viruses, worms, trojans, spyware, and adware—designed to infiltrate, damage, or gain unauthorized access to computer systems and networks.
*   **Real-world Example:** The Stuxnet worm, discovered in 2010, which specifically targeted and sabotaged industrial control systems (SCADA) used in Iran's nuclear program by causing uranium centrifuges to spin out of control while displaying normal operations to monitors.
*   **Prevention Methods:** Keep operating systems and software consistently updated, utilize reputable antivirus/anti-malware solutions, avoid downloading pirated software, and exercise caution with removable media (like USB drives).

**3. Ransomware**
*   **Definition:** A specific type of malware that encrypts a victim's files or locks them out of their systems entirely. The attacker then demands a ransom payment (often in cryptocurrency) in exchange for the decryption key to restore access.
*   **Real-world Example:** The 2017 WannaCry global ransomware attack, which exploited a Windows vulnerability to infect hundreds of thousands of computers across 150 countries. It significantly disrupted critical infrastructure, including the UK's National Health Service (NHS).
*   **Prevention Methods:** Maintain frequent, offline backups of all critical data, implement robust network segmentation, ensure all software is patched promptly, and train employees to recognize phishing attempts (the common delivery method for ransomware).

**4. Social Engineering**
*   **Definition:** The psychological manipulation of individuals into performing actions or divulging confidential information. It exploits human psychology (like trust, fear, or urgency) rather than technical vulnerabilities to bypass security controls.
*   **Real-world Example:** The 2020 Twitter (now X) hack, where attackers used phone-based spear-phishing (vishing) to trick Twitter employees into granting them access to internal administrative tools. This allowed the attackers to take over high-profile accounts (including Barack Obama and Elon Musk) to run a Bitcoin scam.
*   **Prevention Methods:** Conduct regular, comprehensive security awareness training for employees, establish strict protocols for verifying requests for sensitive information or access, and foster a "zero trust" mindset where requests are verified regardless of the apparent source.

**5. Data Breach**
*   **Definition:** A security incident where sensitive, protected, or confidential data is accessed, copied, transmitted, or stolen by an unauthorized individual or group.
*   **Real-world Example:** The 2017 Equifax data breach, which exposed the highly sensitive personal information (including Social Security numbers, birth dates, and addresses) of approximately 147 million consumers due to an unpatched vulnerability in an open-source web application framework.
*   **Prevention Methods:** Encrypt sensitive data both at rest and in transit, implement the Principle of Least Privilege (ensuring users only have access to data necessary for their roles), conduct regular vulnerability scanning and penetration testing, and maintain a robust patch management program.

---

## Part E: Cyber Security Awareness Poster

Please refer to the generated image file `phishing_poster.png` located in this directory for the awareness poster.

---

## Part F: Security Reflection

**1. What cybersecurity risks did you identify in your own digital habits?**
In reviewing my digital footprint, I identified a few concerning habits. First, I realized that while I use complex passwords for critical accounts like banking, I tend to reuse variations of a simpler "base" password for lower-risk accounts (like forums or minor retail sites). This exposes me to credential stuffing attacks if one of those smaller sites is breached. Second, I have several older online accounts where I never bothered to configure Multi-Factor Authentication (MFA), relying solely on passwords. Finally, I occasionally connect to public Wi-Fi networks in coffee shops without consistently ensuring my traffic is routed through a VPN, potentially exposing my browsing activity to interception on the local network.

**2. What security improvements will you implement immediately?**
I plan to implement several immediate changes to harden my security posture. I will conduct a comprehensive audit of my active online accounts and migrate all of them to unique, strong passwords generated and stored within a dedicated, encrypted password manager. I will no longer rely on memory for passwords. Furthermore, I will enable MFA on every account that offers it, prioritizing the use of an authenticator app over SMS-based codes, which are susceptible to SIM-swapping attacks. I will also configure my devices to install operating system and application updates automatically.

**3. Why is cybersecurity important in today's world?**
Cybersecurity is of paramount importance today because our personal, professional, and financial lives are deeply interwoven with digital infrastructure. We entrust an immense amount of sensitive data—from financial records to intimate communications and health information—to technology every day. Cyberattacks are no longer merely an IT inconvenience; they represent a direct threat to personal privacy, financial stability, and even national security (as seen with attacks on critical infrastructure). As threat actors become increasingly sophisticated, leveraging AI and operating within organized syndicates, adopting robust cybersecurity practices is essential to protect our digital identities, prevent devastating data breaches, and maintain the integrity of the digital ecosystem we rely upon.
