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