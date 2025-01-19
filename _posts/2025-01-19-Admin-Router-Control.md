---
layout: post
title: "Admin Router Control"
description: “How to secure the password to the router’s control panel.”
url: "https://tey-dev.github.io/your-project"
code_link: "https://github.com/tey-dev/your-project"
---
In this project, I’ll demonstrate how to modify the router’s password. Changing the administrator password reduces the likelihood of the default password being compromised or discovered.
Here’s what you need to do:

1. We’re gonna open up our virtual machine since I’m a native macOS user… and we're going to navigate to the search bar and type “ internet” for Internet Explorer.
![Screenshot 2025-01-19 at 12 08 43 PM](https://github.com/user-attachments/assets/33f71b17-8f06-4992-87bd-79fab9d98fd0)

2. In the address bar, enter the URL as http://support.dlink.com/emulators/dir655/133NA/login.html, then Log in to the router. 
![Screenshot 2025-01-19 at 12 09 03 PM](https://github.com/user-attachments/assets/a8afa935-dacd-4825-bdeb-a0eace8b7d6b)

3. Now that we're in we can head to the TOOLS tab, provide the admin password as @Dmin1234. (Simulated Password)

Scroll down and provide the user password as "teymarrp1234". (Scroll down and provide the user password as teymarrp1234. (If someone needs to access basic router information, that does not modify administrative router settings.)
![Screenshot 2025-01-19 at 12 10 05 PM](https://github.com/user-attachments/assets/f41b7f9a-c8e1-45ec-b437-7079507c0282)

Scroll up to save the settings 

And there you go, the password to access the router control panel has been changed.

The admin password for a router’s control panel enables configuration of network settings and security features. Changing the default password, updating firmware, and employing secure access methods are crucial to safeguard the network from unauthorized access and attacks.

If someone with malicious intent obtained our company’s admin password, they could cause substantial damage. They could disable security features like turning off our firewall, disable any encryption, and alter network settings, making it easier for them to continue their malicious activities. Ultimately, they could lock us out of the administrative router settings, leaving us unable to access them.

To prevent this, I recommend implementing several measures. One effective approach is to use an IDS/IPS, an intrusion detection system and intrusion prevention system. An IDS detects any malicious or suspicious activity, while an IPS actively prevents any malicious behavior and alerts the user. Naturally, I chose both because an IDS only alerts the human for action, and let’s say I’m not available at my computer to see the notification. Someone with malicious intent doesn’t waste any time. Therefore, I also recommend implementing an IPS so it can actively stop any suspicious behavior if I’m not readily available.
