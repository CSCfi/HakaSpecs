---
title: Haka Federation – Service Agreement
sidebar: home_sidebar
permalink: haka_appendix_3.html
summary: An English translation of the Finnish document dated April 13th 2011
---

## Appendix 3: Service description and requirements

### 1. Services provided by the Operator

The Operator of the Haka Federation provides central services necessary for running the AAI. The services are available for all Federation Members. The services described in section 1.2 are available for all Federation Partners.

Criteria for the membership and partnership in the Federation are defined in Appendix 2.

#### 1.1. Center of Excellence

The Operator has a test equipment to check functions of the AAI and its new components. The test equipment comprises a test SAML Identity Provider and a SAML Service Provider.

The Operator organizes events that support development and deployment of the Haka Federation and generally enhances the know-how transfer among the Finnish higher education.

The Operator, working as the secretary of the Advisory and Operations Committees, convenes and prepares the Committee meetings.
The Operator maintains international contacts with other national federations and bodies and with the developers of the technologies used in the AAI.

#### 1.2. WAYF/DS server and AAI metadata

The Operator operates the central WAYF/DS (Where Are You From/Discovery Service) server and a register of metadata describing the AAI, including
- technical and administrational contacts of the Federation Members and Partners
- addresses and other data describing the servers registered to the AAI  
- a list of attributes necessary for the Service Providers in the AAI, and the Privacy policy address of a Service Provider if the Service Provider processes personal data.

The Operator provides AAI metadata to the Federation Members, Partners and their WAYF/DS servers, if any.

#### 1.3. Strategy and marketing 

Assisted by the Advisory Committee, the Operator is responsible for **planning** the development of the Federation. The goal of the development is to monitor and identify the changing requirements of the Federation Members and to respond to them proactively.

The Operator is responsible for marketing the Federation in the Finnish higher education. The goal of the **marketing** is that prospective Federation Members learn about the possibilities and advantages of the AAI.

### 2. Responsibilities for Federation Participants

Federation Participants are obligated to follow the Haka Federation’s requirements described below.

#### 2.1.  The Operator

In addition to what is presented in chapter 1,

2.1.1. The Operator collects and tests Shibboleth software and, as far as possible, other **software components** available to Federation Members and Partners as SAML Identity Providers, SAML Service Providers and tools supporting them.

2.1.2. The Operator takes the necessary steps to **ensure seamless operation** of the services under its control and monitors service availability. Outages due to planned maintenance operations shall be announced in advance and should be restricted to maintenance windows previously agreed by the Advisory Committee.

2.1.3. The Operator provides **helpdesk** services for Federation Members' technical contact persons to work out operational problems.

2.1.4. The Operator informs Federation Members and Partners of bug fixes, **security updates** and upgrades of AAI components and coordinates efforts to keep the AAI operational and secure.

2.1.5. The Operator collects modification requests and needs related to the **funetEduPerson schema** and drafts a schema draft resolution for Operations Committee. Additionally the Operator gives detailed advice on syntax and semantics of its attributes to Home Organizations and Service Providers.

#### 2.2. Federation Members and Partners

2.2.1. Federation Members and Partners shall **install and update** new AAI software releases according to the agreed schedule maintained by the Advisory Committee.

2.2.2. Federation Members and Partners shall make sure that the AAI **metadata** they are using is up-to-date.

2.2.3. Federation Members and Partners shall inform the Operator about any **changes** of their own AAI elements’ metadata without delay.

2.2.4. Federation Members and Partners shall indicate technical and administrative **contact information** to the Operator.

2.2.5. Federation Members and Partners shall use **server certificates** provided by a CA accredited by the Advisory Committee for all their AAI elements.

2.2.6. Federation Members and Partners shall take care of data security, protection and security updates of their servers properly.

#### 2.3. Special provisions concerning Home Organizations

Only a Federation Member is able to act as a Home Organization.

2.3.1. Home Organizations shall **install and operate** a SAML Identity Provider and other necessary AAI elements and integrate them with their authentication systems and user directory.

2.3.2. When **registering** a new End User and providing him/her with a username, the Home Organization authenticates the End User according to the Federation policies. The Home Organization makes sure that the End User has accepted the Home Organization’s policy of use. 

2.3.3. When an End User is accessing services provided by a Service Provider in the AAI, the Home Organization **authenticates** the End User with a password or in some more secure way. 

2.3.4. If authentication is executed by **passwords**, the Home Organization shall require that End Users have passwords of at least eight characters and try to prevent use of passwords of low quality. Periodical renewal of passwords is recommended.

2.3.5. The attributes collected and released in the AAI shall follow at least the **funetEduPerson schema** ver 2.1 and its possible later versions. At least attributes marked as MUST shall be populated. However, several services will require a value also for other attributes.

2.3.6. Home Organizations take every reasonable step to ensure that the attributes provided to Service Providers are accurate and kept up-to-date and that they are **adequate, relevant and not excessive** in relation to the service in question.

2.3.7. Home organizations maintain **attribute release policies** (ARP), which define what are the user attributes released to each of the Service Providers.

2.3.8. The starting point is that each End User shall give his/her **consent** for release of personal data to each Service Provider separately (see Appendix 7). The End User shall have a chance to read the privacy policy of the service before giving his/her consent.

2.3.9. The Home Organization shall **collect a log** that includes at least the Name Identifier soname identifier that an End User can be linked to a SAML Assertion provided to a Service Provider.

2.3.10. The Home Organization **informs** the End Users about the information collected concerning their use of services on AAI; the purpose of the processing of that information; and where the information is possibly released.

2.3.11. Home Organizations operate a **helpdesk** for their End Users to attend to AAI related issues.

2.3.12. Home Organizations provide a **description of their identity management** procedures to Federation Members and Partners.

### 2.4. Special provisions concerning Service Providers

Both Federation Members and Partners are able to act as a Service Provider.

2.4.1. Service Providers shall **install** and operate a SAML Service Provider and other necessary AAI elements and integrate them with their service.

2.4.2. Service Providers indicate which **attributes are necessary** for their service.

2.4.3. If the Service Provider processes attributes which are considered as personal data, the Service Provider informs the Operator about the URL in which the End Users are able to read the **Privacy policy** before they start to use the service. If the purpose of processing of personal data in the service is changed, the Service Provider is considered as a new service in the AAI. 

2.4.4. The Service Provider shall ensure that only **authorized End Users** can access the service. The access control can be based on the attributes released by the Home Organization.

2.4.5. Considering the articles in the Personal Data Act, the Service Provider shall **collect a log** that includes at least the Name Identifier of the End User. To facilitate abuse investigation, the Service Provider shall provide relevant log entries to the Home Organization.

### 3. Collaboration with foreign partners providing AAI services

The Operator may also sign agreements with foreign collaboration partners providing AAI services. The purpose of the collaboration arrangements is to support Haka Federation Members' international networking and co-operation. Joining a collaboration arrangement is approved by the Advisory Committee. 

Exposing a SAML Identity or Service Provider from Haka Federation to an international collaboration arrangement is always based on a request by the Federation Member or Partner who has registered the Provider to the Federation.

Via a collaboration arrangement, Federation Members and Partners receive Metadata on foreign SAML Identity and Service Providers who are typically not committed to the policies and rules of this Agreement. In that case, the Operator will present the foreign Providers' metadata to Federation Members and Partners in a way which clearly separates them from Haka Federation's Metadata. Additionally, the Operator maintains information on the main differences in policies and rules between the foreign Providers and the Members and Partners committed to this Agreement.

