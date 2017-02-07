https://qph.ec.quoracdn.net/main-qimg-5d4d2bdcafb1f42bbc1668d9d2cfebbb-c

The part of internet that is used daily is known as the surface web. It makes up approximately 4% of the internet. The rest, beyond the visible and easily accessible is in the deep web and darknet. Deep web (coined by Mike Bergman in 2000) is unindexed content, it is sites that cannot be accessed via traditional search engine like on-demand content, banking, email, databases. Dark web, sometimes used synonymously with deep web, is accessible only with specific software, most commonly via Tor (the Onion Router) or I2P (the Invisible Internet Project). 


Darknet has many uses and despite stigma of being mostly criminal (drugs, weapons, assassins, counterfeiting, pornography, malware, information), it is also used for non-criminal purposes like political activism (especially in countries with little to no free speech and restricted internet use but also in unstable nations), privacy (businesses keeping certain topics to darknet to avoid fraud and forged information, individuals using forums and blogs for support, for private or controversial topics), research (especially anything related to security), journalism (communication and censorship avoidance), law enforcement (sting operations, and keeping government IP addresses out of web logs). Accessing the Darknet is not a technical and complicated task but it should be remembered that "there is no such thing as absolute anonymity. From server handshakes to video and keystroke surveillance, someone always knows – this should be [..] number one assumption." http://fembotcollective.org/blog/2015/05/06/toolkit-anonymous/


The easiest beginner solution is Tor <https://www.torproject.org/projects/torbrowser.html.en>. It looks like a regular browser and is small enough that it can be run from a memory stick. It should be noted that NSA targets every download of TOR and then targets that IP address so the best solution is to download it using public terminal at a library or college. Anything done using Tor should be done only on Tor, no mixing accounts (e.g. using your regular email or other accounts, also no using tor email on regular browser) or any nicknames that could be traced back. Using account based systems should only be done on private networks. Information is very commonly traded commodity in both clearnet (visible internet) and darknet. SSD<https://ssd.eff.org/> (Surveillance Self-Defence) offers guidance for maximising anonymity and personal security.




"The Tor Project offers entry-level documentation for its new users and is easy to use. Tor over the years has become very popular with the common user. The Tor Browser Bundle made connecting to Tor very simple for the average user. Tor has received a large amount of academic review over the years and is a very well-funded project. One issue that still remains with Tor is the trust of exit nodes. Attackers can set up malicious exit nodes or spy on the traffic coming out of the network. The best use for Tor is for anonymous out proxing to the internet.
I2p is an anonymous peer-to-peer network overlay that focuses on internal services. It allows users to send data between computers running I2P with end-to-end encryption. I2P uses unidirectional tunnels and layered encryption versus Tor bi-directional tunnels.
I2P is not a very well-known service in comparison to Tor. It has received limited academic review but contains great documentation for all of its users. One issue regarding I2P is the limited number of out proxies to the internet. The best use for i2P is for peer-to-peer file sharing." https://blog.radware.com/security/2016/04/darknet-101/




"Tor is free software and an open network that helps you defend against traffic analysis, a form of network surveillance that threatens personal freedom and privacy, confidential business activities and relationships, and state security."  https://www.torproject.org/index.html.en


"I2P is an anonymous overlay network - a network within a network. It is intended to protect communication from dragnet surveillance and monitoring by third parties such as ISPs." https://geti2p.net/en/

# How Tor Works 

  Tor uses a technique, known as onion routing. Onion routing is an internet protocol which is used to conceal a user’s IP address, by routing it through a series of proxy nodes, maintain by a global network of volunteers, and encrypting the traffic in transit. Each node can only know the identity of the previous node, making it so a given relay in the Tor network cannot know the complete route of the user’s data, and by extension, their identity. Each “hop” through the Tor network uses a separate key pair to make traffic further untraceable.

# Exit Nodes 

  Exit nodes are nodes in the Tor network which serve as exit points for the user’s traffic. This node can see what data the user requested, but it cannot see the user’s identity. Exit nodes are sometimes considered to be the weak point(s) in the Tor network, and are often heavily monitored by law enforcement.

# Limitations & Risks 

  While Tor has proven to be a highly effective means of anonymizing a user while said user’s traffic is traveling through the Tor network, Tor cannot mask a user entering and exiting the network.  
Most Tor users use the Tor browser bundle, or TBB. The TBB is forked from the popular Firefox browser, and therefore often carries certain exploits from Firefox. In 2016, a zero-day-exploit in Firefox was used to comprise the identities of users of the TBB on Windows, OSX, and Linux. 
