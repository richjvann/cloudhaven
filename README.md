# CloudHaven

For the best description of cloudhaven goto http://www.cloudhaven.net.

CloudHaven is a "User Platform" which extracts the "user entity" from cloud applications and consolidates into under users' control for full data protection/privacy, centralized authentication and user management, collaboration and file sharing and other user functions for seamless multi-application integration.

The best way to understand CloudHaven is to look at it from a number of angles.

CloudHaven essentially gives users there own application, their own "functional presence", in the Cloud. Because cloud applications, digital platforms, etc. in the Cloud were developed one at a time, it was natural to also independently develop all of the user-related functionality. As a result, there is in essence a logical "user entity" that has been redundantly implemented in tens of thousands, if not millions of applications. This "user entity" includes not just authentication and user management but also messaging, file sharing, collaboration, personal data storage and protection and even the user-interface itself, at least at the lowest level (that's why its called a "user"-interface). Much of this is commodity stuff - not really anything that gives an application its unique value. Its silly that this functionality has been so redundantly implemented. CloudHaven solves this by centralizing and consolidating this "user entity" under users', not the applications, full control.

No doubt a developer's first thought is that sounds great, but how are you going to integrate that functionality easily and securely in applications so that it is seamless? The secret to this is that CloudHaven provides the presentation layer via a User Interface-as-a-Service. CloudHaven essentially becomes a wrapper around applications providing the authentication and security over the Internet. But this model does much more:

1. It allows the "tokenization" of personal data and anonymous interaction with applications (personal data never enters CH-wrapped applications - they can just handle the tokens - CH intercepts personal data incoming and replaces with a token, and then intercepts tokens outgoing and replaces with personal data. No more Cambridge Analyticas or other Big Data exploitation because users not democratically control their own data and there is no need for applications to touch it. Note that this is a somewhat simplistic presentation of tokenization - it is a little more complicated than this. In some cases there will be need to touch actual data, such as with quantitative health data, however, there is also a single data privacy agreement in place between the user and CloudHaven and between CloudHaven and each CH-registered application which would severely restrict how such data could be used.
HIPAA and GDPR compliance is greatly simplified since applications don't touch PHI or PII, etc.
2. Files and associated viewers can be seamlessly injected by CH into application UIs
3. Collaboration components can be seamlessly injected in application UIs
4. "Applets" from other applications can be seamlessly injected into UIs
5. Users can have full control over who they share their data with for the lifetime of that data. The concept of "sending" emails goes away because emails are simply shared (or unshared).

CloudHaven also enables the following:

1. One-click registrations of vetted applications
(Users only need to register with CloudHaven once and vendors only need to register their application with CloudHaven once).
CloudHaven is like a telephone switch - instead of having point-to-point connections between every application and every user, only a fraction of the connections are required - between users and CH and between CH and applications
2. Universal localization
3. Rapid application development
Application developers no longer need to concern themselves with implementing authentication, roles and permissions, user management, file-sharing, messaging and collaboration, low-level UI presentation (they still, however, develop the higher level UI logic that defines their application)
4. Users can still monetize data, but only anoymously such as for health research and only if they democratically agree to do this.

Another way to look at CloudHaven is that it is a vendor neutral platform for integrating many proprietary silos of application functionality.

Another intent of CloudHaven is for users to have a single way to work with any application. In fact, there could be a marketplace of UI themes that a user could select to work with any application they have one-click registered with - that way they work with forms, tables, reports, searches, etc. in the same way regardless of which application they are using.

Note that in this model, the wild west, insecure Internet only exist between users and CloudHaven - applications could have a leased-line, or VPN connection with CloudHaven thus eliminating most security concerns associated with operating on the open Internet.

An argument that often comes up against CloudHaven is that now all the eggs are in one basket and that makes personal data very vulnerable. My position is that this is better than having all of your eggs in many baskets with varying levels of security or implementation of that security - CloudHaven would have security as its top core competency in an organization democratically controlled by its users.

 
