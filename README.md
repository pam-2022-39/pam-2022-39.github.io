# Active TLS Fingerprinting: Characterizing TLS Server Deployments at Scale - PAM 2022 #39

## Abstract
Active measurements can reveal the Internet as a very complex and heterogeneous network so that extensive structured informationcan be collected. 
Suitable representations of that information enable dis-coveries  of  relationships  and  commonalities  among  scanned  entities  as well as classification and detection of anomalies. Applications are plentiful. 
As an example, the discovery of similarities between cybercriminal server deployments, such as Command and Control (C2) servers, can bea valuable source for Cyber Threat Intelligence.
With Active TLS Fingerprinting we propose a methodology to acquireand leverage the meta-data from TLS servers on a large scale.
We de-ploy active measurements to capture a characteristic TLS behavior fromservers as fingerprint.
Each fingerprint is a textual representation of features extracted from a TLS handshake.
Those features primarily carryinformation about the implementation and configuration deployed on a server.
We proposea sequential scanning procedure using 25 Client Hellos that are designedto trigger different server responses, carrying complementary informationabout  the scanned target, during the TLS handshake.
We fingerprintservers from the Alexa and Majestic toplists and two blocklists containing C2 servers over a period of 12 weeks.
We show that our approach can be used to identify similar deployments on the Internet based on classification of Content Delivery Network (CDN) servers with a precision higher than 99% for Cloudflare and Fastly.
Moreover, we detected 201 IP addresses serving CDN content outside of the Autonomous System operated by the CDN.
We validated these servers by initiating TLS handshakes  for a domain name we knew is served through the CDN.
Additionally, we show the potential of our approach for C2 detectionby identifying 12 unique fingerprints related to specific C2 servers andby evaluating a classifier capable of detecting new blocklisted C2 serverswith a precision higher than 94%.

### More
tbd
