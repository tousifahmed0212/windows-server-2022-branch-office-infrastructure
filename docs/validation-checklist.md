# Validation Checklist

## Identity and DNS
- Confirm Domain Controller promotion completed
- Confirm `techcorp.local` forward lookup zone exists
- Confirm reverse lookup zone exists
- Confirm `nslookup` resolves domain resources
- Confirm forwarder allows internet resolution

## DHCP
- Confirm DHCP server is authorized
- Confirm client scope is active
- Confirm excluded range protects infrastructure IPs
- Confirm clients receive:
  - IP address
  - default gateway
  - DNS server
  - domain suffix

## Group Policy
- Confirm OU structure exists
- Confirm GPO is linked to correct OU
- Confirm legal notice is applied
- Confirm drive mapping is visible on client
- Confirm user restrictions are enforced

## IPAM
- Confirm IPAM installed with dependencies
- Confirm GPO-based provisioning completed
- Confirm DHCP and DNS are visible in IPAM console
- Confirm lease visibility and utilization tracking are working
