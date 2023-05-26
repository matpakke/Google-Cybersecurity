# The relationship between frameworks and controls
Previously, you learned how organizations use security frameworks and controls to protect against threats, risks, and vulnerabilities. This included discussions about the **National Institute of Standards and Technology’s (NIST’s) Risk Management Framework (RMF)** and **Cybersecurity Framework (CSF)**, as well as the **confidentiality, integrity, and availability (CIA) triad**. In this reading, you will further explore security frameworks and controls and how they are used together to help mitigate organizational risk.

## Frameworks and controls
**Security frameworks** are guidelines used for building plans to help mitigate risk and threats to data and privacy. Frameworks support organizations’ ability to adhere to compliance laws and regulations. For example, the healthcare industry uses frameworks to comply with the United States’ Health Insurance Portability and Accountability Act (HIPAA), which requires that medical professionals keep patient information safe. 

**Security controls** are safeguards designed to reduce specific security risks. Security controls are the measures organizations use to lower risk and threats to data and privacy. For example, a control that can be used alongside frameworks to ensure a hospital remains compliant with HIPAA is requiring that patients use multi-factor authentication (MFA) to access their medical records. Using a measure like MFA to validate someone’s identity is one way to help mitigate potential risks and threats to private data.

## Specific frameworks and controls
There are many different frameworks and controls that organizations can use to remain compliant with regulations and achieve their security goals. Frameworks covered in this reading are the **Cyber Threat Framework (CTF)** and the **International Organization for Standardization/International Electrotechnical Commission (ISO/IEC) 27001**. Several common security controls, used alongside these types of frameworks, are also explained. 

**Cyber Threat Framework (CTF)**
According to the Office of the Director of National Intelligence, the CTF was developed by the U.S. government to provide “a common language for describing and communicating information about cyber threat activity.” By providing a common language to communicate information about threat activity, the CTF helps cybersecurity professionals analyze and share information more efficiently. This allows organizations to improve their response to the constantly evolving cybersecurity landscape and threat actors' many tactics and techniques.

**International Organization for Standardization/International Electrotechnical Commission (ISO/IEC) 27001**
An internationally recognized and used framework is ISO/IEC 27001. The ISO 27000 family of standards enables organizations of all sectors and sizes to manage the security of assets, such as financial information, intellectual property, employee data, and information entrusted to third parties. This framework outlines requirements for an information security management system, best practices, and controls that support an organization’s ability to manage risks. Although the ISO/IEC 27001 framework does not require the use of specific controls, it does provide a collection of controls that organizations can use to improve their security posture. 

**Controls**
Controls are used alongside frameworks to reduce the possibility and impact of a security threat, risk, or vulnerability. Controls can be physical, technical, and administrative and are typically used to prevent, detect, or correct security issues.

Examples of physical controls:

- Gates, fences, and locks

- Security guards

- Closed-circuit television (CCTV), surveillance cameras, and motion detectors

- Access cards or badges to enter office spaces

Examples of technical controls:

- Firewalls

- MFA

- Antivirus software

Examples of administrative controls:

- Separation of duties

- Authorization

- Asset classification

To learn more about controls, particularly those used to protect health-related assets from a variety of threat types, review the U.S. Department of Health and Human Services’ Physical Access Control presentation. 

-----

# Use the CIA triad to protect organizations
Previously, you were introduced to the confidentiality, integrity, and availability (CIA) triad and how it helps organizations consider and mitigate risk. In this reading, you will learn how cybersecurity analysts use the CIA triad in the workplace. 

![CIA triad](https://www.i-scoop.eu/wp-content/uploads/2022/04/Cybersecurity-the-infosec-CIA-Triad.jpg.webp)

## The CIA triad for analysts
The CIA triad is a model that helps inform how organizations consider risk when setting up systems and security policies. It is made up of three elements that cybersecurity analysts and organizations work toward upholding: confidentiality, integrity, and availability. Maintaining an acceptable level of risk and ensuring systems and policies are designed with these elements in mind helps establish a successful security posture, which refers to an organization’s ability to manage its defense of critical assets and data and react to change. 

### Confidentiality
Confidentiality is the idea that only authorized users can access specific assets or data. In an organization, confidentiality can be enhanced through the implementation of design principles, such as the principle of least privilege. The principle of least privilege limits users' access to only the information they need to complete work-related tasks. Limiting access is one way of maintaining the confidentiality and security of private data. 

### Integrity
Integrity is the idea that the data is verifiably correct, authentic, and reliable. Having protocols in place to verify the authenticity of data is essential. One way to verify data integrity is through cryptography, which is used to transform data so unauthorized parties cannot read or tamper with it (NIST, 2022). Another example of how an organization might implement integrity is by enabling encryption, which is the process of converting data from a readable format to an encoded format. It can be used to prevent access to data, such as messages on an organization's internal chat platform. 

### Availability
Availability is the idea that data is accessible to those who are authorized to use it. When a system adheres to both availability and confidentiality principles, data can be used when needed. In the workplace, this could mean that the organization allows remote employees to access its internal network to perform their jobs. It’s worth noting that access to data on the internal network is still limited, depending on what type of access employees need to do their jobs. If, for example, an employee works in the organization’s accounting department, they might need access to corporate accounts but not data related to ongoing development projects. 

# NIST Risk Management Framework (RMF)
National Institute of Standards and Technology’s (NIST’s) Risk Management Framework (RMF)

The Risk Management Framework provides a process that integrates security, privacy, and cyber supply chain risk management activities into the system development life cycle. The risk-based approach to control selection and specification considers effectiveness, efficiency, and constraints due to applicable laws, directives, Executive Orders, policies, standards, or regulations. Managing organizational risk is paramount to effective information security and privacy programs; the RMF approach can be applied to new and legacy systems, any type of system or technology (e.g., IoT, control systems), and within any type of organization regardless of size or sector.

<img src="https://csrc.nist.gov/CSRC/media/Projects/risk-management/images-media/RMF%20Logos/PNG%20Format/NIST%20RMF%20Graphc.png" width="500">

| RMF Step | Description |
| ----------- | ----------- |
| Prepare | Essential activities to prepare the organization to manage security and privacy risks  |
| Categorize | Categorize the system and information processed, stored, and transmitted based on an impact analysis |
| Select | Select the set of NIST SP 800-53 controls to protect the system based on risk assessment(s) |
| Implement | Implement the controls and document how controls are deployed |
| Assess | Assess to determine if the controls are in place, operating as intended, and producing the desired results |
| Authorize | Senior official makes a risk-based decision to authorize the system (to operate) |
| Monitor | Continuously monitor control implementation and risks to the system |

[NIST 800-53 Revision 5](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r5.pdf)

---

# OWASP security principles

Previously, you learned that cybersecurity analysts help keep data safe and reduce risk for an organization by using a variety of security frameworks, controls, and security principles. In this reading, you will learn about more Open Web Application Security Project, recently renamed Open Worldwide Application Security Project® (OWASP), security principles and how entry-level analysts use them. 

## Security principles
In the workplace, security principles are embedded in your daily tasks. Whether you are analyzing logs, monitoring a security information and event (SIEM) dashboard, or using a vulnerability scanner, you will use these principles in some way. 

Previously, you were introduced to several OWASP security principles. These included:

- **Minimize attack surface area:** Attack surface refers to all the potential vulnerabilities a threat actor could exploit.

- **Principle of least privilege:** Users have the least amount of access required to perform their everyday tasks.

- **Defense in depth:** Organizations should have varying security controls that mitigate risks and threats.

- **Separation of duties:** Critical actions should rely on multiple people, each of whom follow the principle of least privilege. 

- **Keep security simple:** Avoid unnecessarily complicated solutions. Complexity makes security difficult. 

- **Fix security issues correctly:** When security incidents occur, identify the root cause, contain the impact, identify vulnerabilities, and conduct tests to ensure that remediation is successful.

## Additional OWASP security principles
Next, you’ll learn about four additional OWASP security principles that cybersecurity analysts and their teams use to keep organizational operations and people safe.

### Establish secure defaults
This principle means that the optimal security state of an application is also its default state for users; it should take extra work to make the application insecure. 

### Fail securely
Fail securely means that when a control fails or stops, it should do so by defaulting to its most secure option. For example, when a firewall fails it should simply close all connections and block all new ones, rather than start accepting everything.

### Don’t trust services
Many organizations work with third-party partners. These outside partners often have different security policies than the organization does. And the organization shouldn’t explicitly trust that their partners’ systems are secure. For example, if a third-party vendor tracks reward points for airline customers, the airline should ensure that the balance is accurate before sharing that information with their customers.

### Avoid security by obscurity
The security of key systems should not rely on keeping details hidden. Consider the following example from OWASP (2016):

The security of an application should not rely on keeping the source code secret. Its security should rely upon many other factors, including reasonable password policies, defense in depth, business transaction limits, solid network architecture, and fraud and audit controls.

[Security By Design Principles According To OWASP](https://patchstack.com/articles/security-design-principles-owasp/)

----

# More about security audits
Previously, you were introduced to how to plan and complete an internal security audit. In this reading, you will learn more about security audits, including the goals and objectives of audits. 

## Security audits
A **security audit** is a review of an organization's security controls, policies, and procedures against a set of expectations. Audits are independent reviews that evaluate whether an organization is meeting internal and external criteria. Internal criteria include outlined policies, procedures, and best practices. External criteria include regulatory compliance, laws, and federal regulations. 

Additionally, a security audit can be used to assess an organization's established security controls. As a reminder, security controls are safeguards designed to reduce specific security risks. 

Audits help ensure that security checks are made (i.e., daily monitoring of security information and event management dashboards), to identify threats, risks, and vulnerabilities. This helps maintain an organization’s security posture. And, if there are security issues, a remediation process must be in place.

## Goals and objectives of an audit
The goal of an audit is to ensure an organization's information technology (IT) practices are meeting industry and organizational standards. The objective is to identify and address areas of remediation and growth. Audits provide direction and clarity by identifying what the current failures are and developing a plan to correct them. 

Security audits must be performed to safeguard data and avoid penalties and fines from governmental agencies. The frequency of audits is dependent on local laws and federal compliance regulations.

## Factors that affect audits
Factors that determine the types of audits an organization implements include: 

- Industry type

- Organization size

- Ties to the applicable government regulations

- A business’s geographical location

- A business decision to adhere to a specific regulatory compliance

To review common compliance regulations that different organizations need to adhere to, refer to [the reading about controls, frameworks, and compliance](https://www.coursera.org/learn/foundations-of-cybersecurity/supplement/xu4pr/controls-frameworks-and-compliance).

## The role of frameworks and controls in audits
Along with compliance, it’s important to mention the role of frameworks and controls in security audits. Frameworks such as the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF) and the international standard for information security (ISO 27000) series are designed to help organizations prepare for regulatory compliance security audits. By adhering to these and other relevant frameworks, organizations can save time when conducting external and internal audits. Additionally, frameworks, when used alongside controls, can support organizations’ ability to align with regulatory compliance requirements and standards.  

There are three main categories of controls to review during an audit, which are administrative and/or managerial, technical, and physical controls. To learn more about specific controls related to each category, click the following link and select “Use Template.” 

Link to template: [Control categories](https://docs.google.com/document/d/1HsIw5HNDbRXzW7pmhPLsK06B7HF-KMifENO_TlccbSU/template/preview)

## Audit checklist
It’s necessary to create an audit checklist before conducting an audit. A checklist is generally made up of the following areas of focus:

### Identify the scope of the audit

* The audit should:

- List assets that will be assessed (e.g., firewalls are configured correctly, PII is secure, physical assets are locked, etc.) 

- Note how the audit will help the organization achieve its desired goals

- Indicate how often an audit should be performed

- Include an evaluation of organizational policies, protocols, and procedures to make sure they are working as intended and being implemented by employees

### Complete a risk assessment

- A risk assessment is used to evaluate identified organizational risks related to budget, controls, internal processes, and external standards (i.e., regulations).

### Conduct the audit

- When conducting an internal audit, you will assess the security of the identified assets listed in the audit scope.

### Create a mitigation plan

- A mitigation plan is a strategy established to lower the level of risk and potential costs, penalties, or other issues that can negatively affect the organization’s security posture. 

### Communicate results to stakeholders

- The end result of this process is providing a detailed report of findings, suggested improvements needed to lower the organization's level of risk, and compliance regulations and standards the organization needs to adhere to. 

## Key takeaways
In this reading you learned more about security audits, including what they are; why they’re conducted; and the role of frameworks, controls, and compliance in audits. 

Although there is much more to learn about security audits, this introduction is meant to support your ability to complete an audit of your own for a self-reflection portfolio activity later in this course.

### Resources for more information
Resources that you can explore to further develop your understanding of audits in the cybersecurity space are: 

- [IT Security Procedural Guide: Audit and Accountability (AU) CIO-IT Security-01-08](https://www.gsa.gov/cdnstatic/Audit_and_Accountability_(AU)_%5BCIO-IT_Security_01-08_Rev_6%5D_12-03-2020docx.pdf)

- [Assessment and Auditing Resources](https://www.nist.gov/cyberframework/assessment-auditing-resources)

- [IT Disaster Recovery Plan](https://www.ready.gov/it-disaster-recovery-plan)