Your host at 10.0.0.1 is receiving traffic on port `31337`; block that traffic.

---

In this challenge, you will manage how traffic is handled on a particular port of your host machine. The title should give you a hint as to how — use a firewall! 

Firewalls control network traffic by applying security rules, often referred to as an **access control list (ACL)**, on the host machine. A useful command-line tool for configuring these rules is [iptables](https://linux.die.net/man/8/iptables). 

In most firewall configurations, rule ordering and priority matter. Listing the active configuration can help you understand how packets are matched and processed, making it easier to debug unexpected behavior.
