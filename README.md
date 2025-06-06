# task-8
#  Cyber Security Internship – Task 8

##  Objective
Gain hands-on experience using a VPN and understand its role in enhancing online privacy. Additionally, identify and remove suspicious browser extensions to improve local system security.

---

##  Part 1: VPN Setup and Privacy Testing

### VPN Used: ProtonVPN (Free Tier)
 
**VPN Connection Details:**
- **Server**: Netherlands - NL-FREE#131
- **VPN IP**: 185.107.56.141
- **Protocol**: WireGuard (UDP)
- **Server Load**: 92%
- **Connection Status**: Successful

**Verification:**
- Verified changed IP at: [https://whatismyipaddress.com](https://whatismyipaddress.com)
- Confirmed secure browsing over HTTPS
- Screenshot of active VPN session: `vpn_connected.png`

---

###  6. Disconnect and Compare

| Condition | IP Address         | Speed       | Notes                               |
|----------|--------------------|-------------|-------------------------------------|
| VPN ON   | 185.107.56.141     | ~13 KB/s DL | Secure browsing, slightly slower    |
| VPN OFF  | Original ISP IP    | Faster      | Improved load times, IP visible     |

VPN ensures privacy at the slight cost of speed when using high-load free servers.

---

###  7. VPN Encryption and Privacy Features

**Encryption Used**: ChaCha20 + Poly1305 (WireGuard)

**Key Privacy Protections**:
- IP masking
- Encrypted data tunnels
- No-logs policy
- DNS leak protection
- (Optional) Kill Switch in premium

These protect against eavesdropping, tracking, and identity exposure.

---

###  8. VPN Benefits and Limitations

** Benefits:**
- Secure public Wi-Fi use
- Hides IP address
- Access geo-blocked content
- Prevents ISP tracking

** Limitations:**
- Limited servers on free plans
- Slight performance drop
- Not fully anonymous
- Some websites block VPN IPs

---

##  Part 2: Removing Suspicious Extensions

### Browser: Chrome  
**Extensions Page Accessed**: `chrome://extensions/`

###  Removed:
- **PDF Converter Pro** – Excessive permissions
- **Easy Coupons Now** – Pop-up injections, unknown origin
