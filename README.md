# behind_ingensec

This module can help you to discover the real IP address behind the BinarySec/IngenSec service.

This can be useful if you need to test the security of your server and your website 
behind BinarySec/IngenSec by discovering the real IP address.

![alt text][module_info]

More precisely, I use multiple data sources (DNS enumeration, SEO PrePost) to collect
assigned (or have been) IP addresses from the targeted site or domain that uses the 
BinarySec or IngenSec WAF as a service.

![alt text][module_demo]

Ingensec HTTP headers:

![alt text][module_waf_ingensec]

[module_info]: https://raw.githubusercontent.com/mekhalleh/behind_ingensec/master/pictures/01-demo.png "Module: info"
[module_demo]: https://raw.githubusercontent.com/mekhalleh/behind_ingensec/master/pictures/02-demo.png "Module: demo"
[module_waf_ingensec]: https://raw.githubusercontent.com/mekhalleh/behind_ingensec/master/pictures/03-demo.png "Module: Ingensec"