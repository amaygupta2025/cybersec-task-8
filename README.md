# Task 8 – Understanding VPNs for Privacy and Secure Communication

## Objective
Understand the role of VPNs in protecting privacy and secure communication

## Tools Used
- **VPN Type**: Chrome Extension 
- **IP Verification**: [https://whatismyipaddress.com](https://whatismyipaddress.com)
- **Secure Site Browsed**: [https://wikipedia.org](https://wikipedia.org)


##  VPN Privacy Test – Before vs After

###  Before VPN (Real IP)
- My real IP address and city were visible (blurred for privacy).
- The site showed: _“Your location may be exposed!”_
- This highlights that my connection was **not private**.

  `ip_before.png`


###  After VPN (Masked IP)
- After connecting to the VPN, my IP changed.
- The site confirmed: _“Looks like you're using a VPN!”_
- My location and actual IP were hidden successfully.

 `ip_after.png`


##  Secure Browsing Verification
Visited [https://wikipedia.org](https://wikipedia.org) after connecting to VPN:
-  HTTPS was active
-  Lock icon confirmed encryption
-  VPN encrypted browser traffic

  `https_browsing.png`

---

##  What Was Revealed and What Was Hidden

| Data Type         | Status       | Notes                              |
|------------------|--------------|-------------------------------------|
| Real IP Address  |    Hidden    | Blurred in screenshots             |
| Real City/ISP    |    Hidden    | Blurred for privacy                |
| VPN Server City  |    Safe      | Not personally identifiable        |
| VPN IP Address   |    Optional  | Shown or blurred – shared IP       |
| HTTPS Lock Icon  |    Visible   | Confirms traffic encryption        |

---

##  Key Learnings
- VPNs mask your **real IP** to protect identity and location.
- They **encrypt web traffic** using secure protocols.
- VPNs improve privacy but don’t provide complete anonymity.
- Tools like `whatismyipaddress.com` can help verify VPN function.


## Conclusion
This task successfully demonstrates how VPNs protect privacy by masking the IP address and encrypting traffic. The before-and-after evidence shows the importance of using VPNs, especially on insecure or public networks.


##  Screenshots Included
- `ip_before.png`
- `ip_after.png`
- `https_browsing.png`
