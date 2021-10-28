# Active TLS Fingerprinting: Characterizing TLS Server Deployments at Scale - PAM 2022 #39

## Abstract
The Internet is a complex and heterogeneous network in which systematic active measurements can be performed to collect structured information about network entities. 
Suitable representations of that information enable discoveries of relationships and commonalities among scanned entities as well as classification and detection of anomalies. 
As an example, the discovery of similarities between cybercriminal server deployments, such as Command and Control (C2) servers, can be a valuable source for Cyber Threat Intelligence. 
We propose a methodology based on Active TLS Fingerprinting to acquire and leverage the meta-data from TLS servers on a large scale. 
We deploy active measurements to capture a characteristic TLS behavior from servers as fingerprint. 
Each fingerprint is a textual representation of features extracted from a TLS handshake. 
Those features primarily carry information about the implementation and deployment configuration of a server. 
We propose a scanning procedure using 25 Client Hellos that are designed to trigger different server responses, which carry complementary information about the scanned target. 
We fingerprint servers from the Alexa and Majestic toplists and two blocklists containing C2 servers over a period of 12 weeks. 
We show that our approach can be used to identify similar deployments based on classification of Content Delivery Network (CDN) servers with a precision higher than 99% for Cloudflare and Fastly. 
Moreover, we detect 201 IP addresses serving CDN content outside of the Autonomous System operated by the CDN. 
We validate these servers by initiating TLS handshakes for a domain name served through that CDN. 
Additionally, we show the potential of our approach for C2 detection by identifying 12 unique fingerprints related to specific C2 servers and by evaluating a classifier capable of detecting new blocklisted C2 servers with a precision higher than 94%.

### More
tbd
