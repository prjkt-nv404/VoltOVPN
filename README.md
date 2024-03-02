# VoltOVPN - Dockerized

OpenVPN server as a Docker.

#### Install and Run

```shell
wget -O "inst_ovpn.sh" https://raw.githubusercontent.com/prjkt-nv404/VoltOVPN/main/inst_ovpn.sh; chmod +x inst_ovpn.sh; ./inst_ovpn.sh
```
 ### Security Upgrades: Configuration, $OPENVPN/pki, and Tunnel Integrity

```mkdn
* Enhanced Configuration Security: Eliminates reliance on serveconfig for HTTPS configuration distribution,
  minimizing potential configuration vulnerabilities.

* Robust $OPENVPN/pki Implementation: Provides secure authentication and encryption for data in transit and at rest.

* Persistent Security: OpenVPN configuration settings, keys, and certificates stored on a dedicated volume
  for simplified management and resilience.

* Improved Tunnel Integrity: tls-auth implementation adds HMAC security, ensuring data within the VPN tunnel
  remains unmodified.
```
