Accessing Federated Cloud Services with Kerberos after Network Authentication
===========================

Alejandro Abad-Carrascosa, Alejandro Perez-Mendez, Rafael Marın-Lopez, and Gabriel Lopez-Millan
Dept. Information and Communications Engineering (DIIC)
University of Murcia, 30100, Spain

Abstract
--
The growth of public and private cloud services,
and the proliferation of open source cloud solutions is un-
deniable. At the same time, new security features are being
developed to provide a stronger confidence of end users and
to improve the user experience. Examples of these features are
advanced/extensible authentication mechanisms, Single Sign-On
(SSO) and Identity Federation. This work introduces a novel
approach to provide these features to cloud services, by taking
advantage of well-known and widely deployed protocols. On
the one hand, Kerberos, providing an advanced authentication
framework and a native SSO mechanism. On the other, the
AAA protocols (such as RADIUS or Diameter) providing widely
deployed network access identity federations, such as eduroam.
The proposed solution allows the end user to bootstrap fresh valid
authentication credentials to access cloud services in a visited
organization from a previous network authentication process,
backed up by a AAA identity federation. Moreover, it does not
imply modifications to the current standards. A proof-of-concept
has been been implemented to validate the feasibility of this
proposal.
