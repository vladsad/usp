<!-- Reference Links -->
[1]:	https://github.com/BroadbandForum/usp/tree/master/data-model "TR-181 Issue 2 Device Data Model for TR-069"
[2]: https://www.broadband-forum.org/technical/download/TR-069.pdf	"TR-069 Amendment 6	CPE WAN Management Protocol"
[3]:	https://www.broadband-forum.org/technical/download/TR-106_Amendment-8.pdf "TR-106 Amendment 8	Data Model Template for TR-069 Enabled Devices"
[4]:	https://tools.ietf.org/html/rfc7228 "RFC 7228	Terminology for Constrained-Node Networks"
[5]:	https://tools.ietf.org/html/rfc2136	"RFC 2136 Dynamic Updates in the Domain Name System"
[6]:	https://tools.ietf.org/html/rfc3007	"RFC 3007 Secure Domain Name System Dynamic Update"
[7]:	https://tools.ietf.org/html/rfc6763	"RFC 6763 DNS-Based Service Discovery"
[8]:	https://tools.ietf.org/html/rfc6762	"RFC 6762 Multicast DNS"
[9]:	https://tools.ietf.org/html/rfc7252	"RFC 7252 The Constrained Application Protocol (CoAP)"
[10]:	https://tools.ietf.org/html/rfc7390	"RFC 7390 Group Communication for the Constrained Application Protocol (CoAP)"
[11]:	https://tools.ietf.org/html/rfc4033	"RFC 4033 DNS Security Introduction and Requirements"
[12]:	https://developers.google.com/protocol-buffers/docs/proto3 "Protocol Buffers v3	Protocol Buffers Mechanism for Serializing Structured Data Version 3"
[13]: https://regauth.standards.ieee.org/standards-ra-web/pub/view.html#registries "IEEE Registration Authority"
[14]: https://tools.ietf.org/html/rfc4122 "RFC 4122 A Universally Unique IDentifier (UUID) URN Namespace"
[15]: https://tools.ietf.org/html/rfc5280 "RFC 5290 Internet X.509 Public Key Infrastructure Certificate and Certificate Revocation List (CRL) Profile"
[16]: https://tools.ietf.org/html/rfc6818 "RFC 6818 Updates to the Internet X.509 Public Key Infrastructure Certificate and Certificate Revocation List (CRL) Profile"
[17]: https://www.ietf.org/rfc/rfc2234.txt "RFC 2234 Augmented BNF for Syntax Specifications: ABNF"
[18]: https://www.ietf.org/rfc/rfc3986.txt "RFC 3986 Uniform Resource Identifier (URI): Generic Syntax"
[19]: https://www.ietf.org/rfc/rfc2141.txt "RFC 2141 URN Syntax"
[Conventions]: https://www.ietf.org/rfc/rfc2119.txt "Key words for use in RFCs to Indicate Requirement Levels"

# Message Encoding

USP requires a mechanism to serialize data to be sent over a message transfer protocol. The description of each individual message encoding scheme is covered in a section of this document and/or in the referenced specification. This version of the specification includes support for:

* [Protocol Buffers Version 3][12]

**R-ENC.0** - An implementation using protocol buffers encoding MUST conform to the schema defined in [usp-msg.proto](https://github.com/BroadbandForum/usp/blob/master/specification/usp-msg.proto).

[<-- Message Transfer Protocols](/specification/mtp/)
[End-to-End Messages Exchange -->](/specification/e2e-message-exchange/)