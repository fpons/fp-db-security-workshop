# Database Security Solutions Workshop #

## Workshop Overview ##

This workshop addresses how to identify threats and remediate them by leveraging Oracle Database Security features. Oracle Database Security Options are an essential part of the Oracle strategy to protect data and sensitive information in Oracle Databases and offer ways to comply with recent Data Privacy regulations such as EU GDPR. The workshop covers most Oracle Database Security features and options and covers all topics related to the main rings of data protection: preventive, detective and monitoring. The materials are applicable to various database releases (11gR2 through to 19c). It is also valid wherever the database is deployed On-Premises or in the Oracle Cloud. It also covers Autonomous Database Security.

## Workshop Requirements

- DBA experience with Oracle Database.
- Basic knowledge of Linux.
- SSH and VNC to connect to remote hosts.

## Agenda - Day 1

### Database labs

- **Lab 1 Database Security Assessment Tool** - Assessing the security of an On-Premise database with the Database Security Assessment Tool (DBSAT).

- **Lab 2: Network encryption** - Encrypting the network with Oracle Net.

- **Lab 3: Transparent Data Encryption** - Encrypting On-Premises databases with Transparent Data Encryption.

- **Lab 4: Data Redaction** - Using Data Redaction policies to prevent sensitive data from leaving the database unprotected (aka pseudonymization).

- **Lab 5: Privilege Analysis** - Using Privilege Analysis to adopt a Least Privilege Model.

- **Lab 6: Database Vault** - Configuring Database Vault to protect the database from over-privileged users and implement Separation Of Duties.

## Agenda - Day 2

### Database labs

- **Lab 7: Database Audit** - Configuring Unified Auditing and Unified Auditing policies.

- **Lab 8: Audit Vault** - Using Audit Vault to manage audit data, view reports and create alerts.

- **Lab 10 (optional) : Running DBSAT again to compare results** - Using dbsat_diff companion utility to DBSAT to measure progress in securing a database.

### Data Safe labs - Using Data Safe to manage security features in Oracle databases
- **Lab DS01 :** Provision an ATP-S instance and import data
- **Lab DS02 :** Register the ATP-S instance to Data Safe
- **Lab DS03 :** Provision Audit and Alert Policies
- **Lab DS04 :** Run Security Assessments with Data Safe
- **Lab DS05 :** Discover and Mask Sensitive Data


## Accessing the labs ##

- Use the **Lab Contents** menu on your left to access the labs 0 to 10.

- If the menu is not displayed, click the menu button ![](./images/menu-button.png "") on the top left to make it visible.

- From the menu, click on the lab that you would like to proceed with. The **Lab 0: Accessing the Lab Environment** will explain how to connect to the virtual machines in the database labs environment. The database labs are usually **order dependent** : you need to proceed in order.

- You may close the menu by clicking again the hamburger menu on the top left ![](./images/menu-button.png "").


## Acknowledgments

**Authors**

- Adrian Galindo, PTS LAD & François Pons, PTS EMEA - Database Product Management - December 2020.

**Credits**

- Data Safe Labs based on the materials from Oracle Database Security Product Management Team.
