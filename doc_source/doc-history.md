# Document history for Network Load Balancers<a name="doc-history"></a>

The following table describes the releases for Network Load Balancers\.

| Change | Description | Date | 
| --- |--- |--- |
| [Target group health](#doc-history) | This release adds support to configure the minimum count or percentage of targets that must be healthy, and what actions the load balancer takes when the threshold is not met\. | November 17, 2022 | 
| [Health check configuration](#doc-history) | This release provides improvements to health check configuration\. | November 17, 2022 | 
| [Cross\-zone load balancing](#doc-history) | This release adds support to configure cross\-zone load balancing at the level group level\. | November 17, 2022 | 
| [TLS 1\.3](https://docs.aws.amazon.com/elasticloadbalancing/latest/network/create-tls-listener.html#describe-ssl-policies) | This release adds security policies supporting TLS version 1\.3\. | October 14, 2021 | 
| [Application Load Balancers as targets](https://docs.aws.amazon.com/elasticloadbalancing/latest/network/application-load-balancer-target.html) | This release adds support to configure an Application Load Balancer as the target of a Network Load Balancer\. | September 27, 2021 | 
| [Client IP preservation](https://docs.aws.amazon.com/elasticloadbalancing/latest/network/load-balancer-target-groups.html#client-ip-preservation) | This release adds support to configure client IP preservation\. | February 4, 2021 | 
| [Security policy for FS supporting TLS version 1\.2](https://docs.aws.amazon.com/elasticloadbalancing/latest/network/create-tls-listener.html#describe-ssl-policies) | This release adds a security policy for Forward Secrecy \(FS\) supporting TLS version 1\.2\. | November 24, 2020 | 
| [Dual\-stack mode](https://docs.aws.amazon.com/elasticloadbalancing/latest/network/load-balancer-ip-address-type.html) | This release adds support for dual\-stack mode, which enables clients to connect to the load balancer using both IPv4 addresses and IPv6 addresses\. | November 13, 2020 | 
| [Connection termination on deregistration](#doc-history) | This release adds support to close connections to deregistered targets after the end of the deregistration timeout\. | November 13, 2020 | 
| [ALPN policies](https://docs.aws.amazon.com/elasticloadbalancing/latest/network/create-tls-listener.html#alpn-policies) | This release adds support for Application\-Layer Protocol Negotiation \(ALPN\) preference lists\. | May 27, 2020 | 
| [Sticky sessions](https://docs.aws.amazon.com/elasticloadbalancing/latest/network/load-balancer-target-groups.html#sticky-sessions) | This release adds support for sticky sessions based on source IP address and protocol\. | February 28, 2020 | 
| [Shared subnets](#doc-history) | This release adds support for specifying subnets that were shared with you by another AWS account\. | November 26, 2019 | 
| [Private IP addresses](#doc-history) | This release enables you to provide a private IP address from the IPv4 address range of the subnet you specify when you enable an Availability Zone for an internal load balancer\. | November 25, 2019 | 
| [Add subnets](#doc-history) | This release adds support for enabling additional Availability Zones after you create your load balancer\. | November 25, 2019 | 
| [SNI support](https://docs.aws.amazon.com/elasticloadbalancing/latest/network/create-tls-listener.html#sni-certificate-list) | This release adds support for Server Name Indication \(SNI\)\. | September 12, 2019 | 
| [UDP protocol](#doc-history) | This release adds support for the UDP protocol\. | June 24, 2019 | 
| [TLS protocol](https://docs.aws.amazon.com/elasticloadbalancing/latest/network/create-tls-listener.html) | This release adds support for the TLS protocol\. | January 24, 2019 | 
| [Cross\-zone load balancing](#doc-history) | This release adds support for enabling cross\-zone load balancing\. | February 22, 2018 | 
| [Proxy protocol](https://docs.aws.amazon.com/elasticloadbalancing/latest/network/load-balancer-target-groups.html#proxy-protocol) | This release adds support for enabling Proxy Protocol\. | November 17, 2017 | 
| [IP addresses as targets](https://docs.aws.amazon.com/elasticloadbalancing/latest/network/load-balancer-target-groups.html#target-type) | This release adds support for registering IP addresses as targets\. | September 21, 2017 | 
| [New load balancer type](#doc-history) | This release of Elastic Load Balancing introduces Network Load Balancers\. | September 7, 2017 | 