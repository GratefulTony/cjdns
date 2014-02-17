# cjdns


#### *Networking Reinvented (and extended)*

This is a minor fork of the cjdns system-- I am seeking to add some admin features for monitoring and controlling QOS for peers, eventually hoping to add some sort of pay-for-bandwidth functionality. Point being: What to do with an abusive peer (Malissa)? Our downlink has only so much bandwidth, and Malissa is eating it all up and ruining connection quality for everyone! We need Melissa to own up to her packet consumption, or somehow allow her to compensate the uplinlk owner for her high utilization of the finite bandwidth resource.

A lot of projects have been seeking to construct "alt-meshnets" which attempt to implement various schemes for addressing what I will refer to as the Node Compensation/Altruism Problem: (NCAP), while simultaneously attempting to re-implement the networking protocols underlying the system, and, basically, the wheel itself. I feel that this fragmentation of the community isn't healthy, and that the NCAP should be addressed separately from the routing solution. It is obvious that, like any networking protocol, cjdns will probably need peer-QOS functionality eventually, and since this is probably the best place to hook in myriad useful features (as well as the eventual solution to the NCAP), we might as well get it over with and build the QOS system.
