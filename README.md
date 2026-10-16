# Netcore Router Vulnerability Public References

This directory contains minimal public references for CVE coordination involving Netcore router findings.
The files intentionally omit proof-of-concept material, exploit steps, and detailed remediation notes.
Public reference date: 2026-09-04
Contributors: Zhou Ao, Yin Luxing, Jiang Yuxuan, Lu Fangzhou, Liu Xin, @Nebusec
Status: 22 findings have provisional CVE IDs; 3 additional references are pending confirmation. 7 additional NR256CN references published on 2026-10-16; CVE submission pending.

## Advisories
- [Unterminated Buffer Over-read in filter_arp_put_file.cgi via String API Misuse](2026.08.19-netcore-nr255v-arp-import-overread.md)
- [Cross-User Session and Browsing History Disclosure via Audit Endpoints](2026.08.19-netcore-nr255v-audit-endpoint-disclosure.md)
- [Captive-Portal Credential Disclosure via l7_web_auth_user_show.cgi](2026.08.19-netcore-nr255v-captive-portal-cred-disclosure.md)
- [CSRF on WAN/LAN Reconfiguration Endpoints](2026.08.19-netcore-nr255v-csrf-wan-reconfig.md)
- [DDNS Management Builds Root-run Command Lines from Unquoted User Input](2026.08.19-netcore-nr255v-ddns-argv-injection.md)
- [DDNS Plaintext Credential Disclosure via ddns_wan_list_show.cgi](2026.08.19-netcore-nr255v-ddns-cred-disclosure.md)
- [Stored Cross-site Scripting via DDNS eval() in ddns_wan_list_show.cgi](2026.08.19-netcore-nr255v-ddns-stored-xss.md)
- [Stored Cross-site Scripting Across DHCP/ACL/MAC/DNS/Option82 Management Pages](2026.08.19-netcore-nr255v-dhcp-acl-stored-xss.md)
- [LAN-Triggerable Stored Cross-site Scripting via DHCP and ARP Hostname Fields](2026.08.19-netcore-nr255v-dhcp-lan-xss.md)
- [Out-of-bounds Reads in mtd_write Pre-flash Validation via Short Firmware Upload](2026.08.19-netcore-nr255v-firmware-upload-oob.md)
- [IPsec PSK and RSA Key Disclosure via Read Handlers](2026.08.19-netcore-nr255v-ipsec-cred-disclosure.md)
- [Stored Cross-site Scripting Across L7 Content Management Pages via eval() Sinks](2026.08.19-netcore-nr255v-l7-content-stored-xss.md)
- [NULL Pointer Dereference via Unchecked atoi() in QoS Setter Handlers](2026.08.19-netcore-nr255v-null-deref-atoi.md)
- [PPTP/L2TP VPN Credential Disclosure via Read Handlers](2026.08.19-netcore-nr255v-pptp-l2tp-cred-disclosure.md)
- [Stored Cross-site Scripting via Unescaped QoS Rule Names in eval()-Parsed Responses](2026.08.19-netcore-nr255v-qos-stored-xss.md)
- [QoS Read Routes Expose Live Network Telemetry to Broad Authenticated Roles](2026.08.19-netcore-nr255v-qos-telemetry-disclosure.md)
- [Stack-based Buffer Overflow in reboot_timer_set.cgi via sscanf Token Parsing](2026.08.19-netcore-nr255v-reboot-timer-overflow.md)
- [Stored Cross-site Scripting Across Route/NAT Configuration Pages via eval() and HTML Sinks](2026.08.19-netcore-nr255v-route-nat-stored-xss.md)
- [NULL Pointer Dereference via Missing exit_port in route_policy_add.cgi](2026.08.19-netcore-nr255v-route-policy-null-deref.md)
- [OS Command Argument Injection in Nettools tcpdump Launch Paths](2026.08.19-netcore-nr255v-tcpdump-arg-injection.md)
- [Stack-based Buffer Overflow in ntools_tcpdump_start_set.cgi via Unsized sprintf](2026.08.19-netcore-nr255v-tcpdump-overflow.md)
- [Low-Privilege Router Credential Disclosure via user_pass_show.cgi](2026.08.19-netcore-nr255v-user-pass-disclosure.md)
- [Stack-based Buffer Overflow in wake_up_set.cgi via Unbounded MAC and ID Tokenization](2026.08.19-netcore-nr255v-wake-up-set-overflow.md)
- [Forgeable Firmware Authenticity Check in mtd_write](2026.08.19-netcore-nr268-firmware-forgery.md)
- [Parameter Restore Archive Bypass via Prefix Check in parame_put_file.cgi](2026.08.19-netcore-nr268-restore-bypass.md)
- [Pre-authentication Stack Buffer Overflow via a Long Basic-Auth Username in user_ok](2026.10.15-netcore-nr256cn-basic-auth-stack-overflow.md)
- [NULL Pointer Dereference in Basic-Auth Parsing Before Authentication Failure Handling](2026.10.15-netcore-nr256cn-basic-auth-null-deref.md)
- [Authentication Bypass on Protected Management CGI Handlers via Public-Route URI Prefixes](2026.10.15-netcore-nr256cn-cgi-auth-bypass-alternate-path.md)
- [Out-of-Bounds Write in Scheduler fd_set Handling under Concurrent POST Uploads](2026.10.15-netcore-nr256cn-fdset-oob-write-post-spray.md)
- [Out-of-Bounds Read in Multipart Upload Parsing via Unterminated Body Search](2026.10.15-netcore-nr256cn-multipart-body-overread.md)
- [Invalid Boundary Pointer Dereference during CGI Handoff on Multipart Uploads](2026.10.15-netcore-nr256cn-multipart-boundary-pointer-deref.md)
- [Unauthenticated Writes to Predictable Fixed Temporary Files via Arbitrary CGI Pathnames](2026.10.15-netcore-nr256cn-fixed-tmp-sink-write.md)
