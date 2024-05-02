RE: https://github.com/byoda/byoda-python

# Thoughts & Issues

## To Sort:

> - Potential vulnerability by notifications of friend requests being sent for storage directly to another users pod. Could the current implementation result in a 'DDOS style attack' whereby a malicious actor can flood a pod with requests causing storage to reach a limit and freeze or to inflate to a point of extreme cost to the receiver?
>   > - Resolved by storing requests elsewhere or adding logic to prevent multiple requests/requests from blocked people etc?

## Networking

### Addressing

#### DNS

- Fundamentally disagree with the feasability of DNS for pods outside of serious content creators, businesses etc.
- Rewrite the pod implementation to allow for DNS using DNSLink to allow for the rework of the system to content addressing https://dnslink.dev/.
- Or platform providers like youtube would serve as gateways for IPNS resolution.
- Sped up through enabling IPNS over pub-sub rather than just DHT.
