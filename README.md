# Security-Risk-Assessment--Network-Hardening-Mearsures





### **Incident Overview**
Recently, our social media organization experienced a significant data breach, resulting in the exposure of sensitive customer data including names and addresses. This breach was caused by multiple undetected vulnerabilities within our network infrastructure and security protocols. To prevent future incidents, we must implement strong and consistent network hardening practices.

### **Identified Vulnerabilities**
Upon inspection, we discovered the following vulnerabilities:
1. Employees are sharing passwords.
2. The database admin password is still set to the default.
3. Firewall rules are not configured to filter traffic effectively.
4. Multifactor authentication (MFA) is not in use.

If these vulnerabilities are not addressed, the organization remains at high risk for future data breaches and other malicious attacks.

---

## **Network Hardening Tools and Methods**

### **1. Implement Strong Password Policies and Password Management Tools**
- **Tool/Method:** Use password management tools like **LastPass** or **1Password** to generate and store strong, unique passwords for each user.
- **Policy:** Enforce regular password updates, prohibit password sharing, and implement password complexity requirements.

### **2. Change Default Passwords and Implement Role-Based Access Controls (RBAC)**
- **Tool/Method:** Immediately update the admin password for all critical systems, including the database, and enforce **RBAC** to ensure users only have access to what they need based on their job roles.

### **3. Configure and Monitor Firewall Rules**
- **Tool/Method:** Use a next-generation firewall (NGFW) like **pfSense** or **Fortinet** to set up rules for filtering inbound and outbound network traffic.
- **Practice:** Regularly audit firewall rules and update them to block unnecessary or suspicious connections.

### **4. Enable Multifactor Authentication (MFA) Across All Systems**
- **Tool/Method:** Implement an MFA solution such as **Duo Security**, **Google Authenticator**, or **Microsoft Authenticator** for all employee logins, especially for admin-level access.

---

## **Effectiveness of Selected Tools and Methods**

- **Password management and strong policies** reduce the risk of credential theft and unauthorized access due to shared or weak passwords.
- **Changing default passwords** eliminates one of the easiest entry points for attackers and limits internal misuse through **RBAC**.
- **Firewall configurations** help control traffic entering and leaving the network, preventing unauthorized access and malware from communicating with external sources.
- **MFA** provides an additional layer of security by requiring more than just a password, making it much harder for attackers to gain access even if credentials are compromised.

---

## **Conclusion**

By implementing these network hardening tools and practices, the organization can significantly reduce its attack surface and better protect customer data. These methods not only address the vulnerabilities identified in the recent breach but also create a culture of proactive security. Continuous monitoring, routine audits, and employee training should also be part of the organization’s long-term cybersecurity strategy.

