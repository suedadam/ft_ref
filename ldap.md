# LDAP
<p align="center">
  <img src="http://salesbox.com/wp-content/uploads/2017/09/Messaging-Pillars-Technology-Scalability.png">
</p>

The [LDAP](https://en.wikipedia.org/wiki/Lightweight_Directory_Access_Protocol) protocol is heavily used in many schools and 42 is among them; however, 42 had a unique problem with using an open source LDAP server. It wasn't fast enough! The whole school was built around using LDAP for authentication which meant the server had to handle hundreds of authenciation requests per second. This problem was so problematic that the school opened it up to the student population to solve! To solve this issue we designed and built an LDAP server for the school to use which allowed them to scale easily.

---

# Objectives
|Name|TL;DR
|:-:|:-:|
|A faster LDAP server|We had to make a LDAP server that was faster and more modular than other source ones.|
|Scalable|The LDAP server we made allowed for a scalable setup without the struggle of rebooting or reloading slave instances.|

# Skills
|Skill|How it was used
|:-:|:-:|
|RFC|A large portion of the time taken on this project was to learn the RFC for LDAP ([RFC4511](https://tools.ietf.org/html/rfc4511))|
|Modularity|This project required modularity to allow other staff members to change the code easily.|
