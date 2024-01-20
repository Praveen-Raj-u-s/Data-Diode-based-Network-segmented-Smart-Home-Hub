# Data-Diode-based-Network-segmented-Smart-Home-Hub:


1. Introduction:
Smart-Home technology has witnessed remarkable advancements, yet concerns over user privacy persist. In response, we present a Privacy-focused Smart-Home Architecture that leverages a unique approach to address these concerns. The Primary Novelty of our Privacy-focused Smart-Home Architecture is our Semi-Internet isolated Smart-Home Hub that doesn’t rely on the internet for working. More than 80% of the Processing/computing of the system is completed in the hub itself. Thus, confining user’s data within the walls of their home. 

Yet, there would be cases in which internet connectivity would be inevitable. This includes cases such as streaming live audio, utilizing online services etc. In order to facilitate this internet connectivity while not compromising privacy, our system utilizes a one-way data transmission methodology with data-diodes. The hub incorporates a dual-microcontroller design, ensuring a balance between efficient local processing and stringent security measures.


2. Methodology:
2.1 Dual-Microcontroller Architecture:
The heart of the Smart-Home hub lies in its dual-microcontroller architecture. One microcontroller operates in a high-security environment, while the other handles low-security tasks. This architectural division ensures a balance between local processing efficiency and stringent security measures.

2.2 Localized Voice-to-Text Processing:
The high-security microcontroller employs edge AI for localized Voice-to-Text processing. This ensures that user speech is transformed into text within the secure environment, mitigating the risk of exposing sensitive voice data.

2.3 Secure Communication via Li-fi based Data Diode:
A critical component of the architecture is the Li-fi based data diode, facilitating secure one-way communication between microcontrollers. This diode ensures that data flows only from the high-security microcontroller to the low-security counterpart, preventing unauthorized access and enhancing overall data protection.

2.4 Local Device Control and Limited Internet Access:
The low-security microcontroller connects to various output devices, enabling seamless local control without relying on external servers. Additionally, internet access is restricted through the data diode, allowing connections only for specific commands such as playing songs from YouTube. This bandwidth limitation enhances privacy by preventing unnecessary exposure of user data.

![image](https://github.com/Praveen-Raj-u-s/Data-Diode-based-Network-segmented-Smart-Home-Hub/assets/114270637/234ef7bb-3776-47a4-b51c-5b73ad53e217)



3. Results:
The Data Diode-based Smart-Home Hub successfully achieves the goal of prioritizing user privacy. By combining edge AI, a dual-microcontroller architecture, and a Li-fi based data diode, the hub ensures secure processing of voice commands and prevents unauthorized access to sensitive user data.


5. Conclusion:
This project presents a robust solution to the privacy challenges associated with Smart-Home technology. The Data Diode-based Smart-Home Hub not only showcases technological innovation but also underscores the importance of localized processing in ensuring user data remains confidential.


7. Future Work:
Future iterations of this project could explore additional security features, integration with emerging technologies, and scalability to accommodate evolving Smart-Home ecosystems.


