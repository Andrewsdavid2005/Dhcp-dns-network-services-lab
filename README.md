# DHCP & DNS Network Services Lab

A hands-on **Cisco Packet Tracer** project demonstrating DHCP, DNS, HTTP web services, IP addressing, client-server communication, and basic network troubleshooting.

---

## Project Overview

This project simulates a small office network where clients automatically receive their network configuration using **DHCP** and access an internal web server using a hostname resolved through **DNS**.

The project also includes a troubleshooting scenario where IP connectivity was working, but hostname resolution failed due to a DNS configuration issue.

### Network Flow

```text
                    ┌──────────────┐
                    │    Router    │
                    │     R1       │
                    │    DHCP      │
                    └──────┬───────┘
                           │
                           │
                    ┌──────┴───────┐
                    │     SW1      │
                    │   Switch     │
                    └──┬────┬────┬─┘
                       │    │    │
                      PC1  PC2  Server
                              DNS + HTTP
