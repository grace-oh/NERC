# NERC
five directives to electricity distribution companies in four days by April 10



Project Title: Electricity Band Check Portal

Description:

The Electricity Band Check Portal is a web-based application designed to assist customers of electricity distribution companies (DisCos) in Nigeria in determining their current electricity bands. Developed in response to the directives of the Nigerian Electricity Regulatory Commission (NERC), the portal offers customers a convenient and transparent means to verify their electricity bands based on their meter or account numbers.

The primary objective of the Electricity Band Check Portal is to ensure transparency and accountability in electricity billing processes. By allowing customers to independently verify their electricity bands, the portal aims to promote trust and confidence in the billing practices of DisCos, thereby enhancing customer satisfaction and reducing disputes related to electricity billing.

The portal's functionality revolves around a user-friendly interface where customers can input their meter or account numbers. Upon submission, the portal communicates with the backend system to retrieve the corresponding electricity band information associated with the provided meter/account number. The retrieved information is then displayed to the user, indicating their current electricity band.

Behind the scenes, the backend of the Electricity Band Check Portal is powered by Python using the Flask framework. It securely handles customer data, ensures proper authentication and authorization mechanisms are in place, and communicates with the database to retrieve electricity band information. The database, implemented using SQLite, stores customer account details and their corresponding electricity bands.

Security is paramount in the design and implementation of the Electricity Band Check Portal. The application utilizes HTTPS to encrypt data transmission, implements input validation to prevent malicious attacks, and employs authentication and authorization mechanisms to restrict access to sensitive information. Passwords are securely hashed, and sensitive data stored in the database is encrypted to protect customer privacy.

In addition to providing a secure and reliable service, the Electricity Band Check Portal adheres to regulatory requirements set forth by NERC. It ensures compliance with directives related to electricity tariff rates, feeder classifications, and customer refunds. By maintaining alignment with regulatory standards, the portal contributes to the overall efficiency and transparency of the electricity distribution sector in Nigeria.

Overall, the Electricity Band Check Portal serves as a valuable tool for both electricity consumers and distribution companies. It empowers customers with access to critical information about their electricity bands while promoting transparency and accountability in the billing process. As Nigeria continues to pursue improvements in its electricity infrastructure, the portal plays a pivotal role in fostering trust and efficiency within the industry.
