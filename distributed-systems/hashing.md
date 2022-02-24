# Hashing

E.g. used for load balancing, hashing request to find target server.

## Properties

Uniformity



## Types

### **Consistent Hashing**

A type of hashing that minimizes the number of keys that need to be remapped when a hash table gets resized. It minimizes the number of requests that get forwarded to different servers when new servers are added or when existing servers are brought down.

### Rendezvous Hashing

Also called **highest random weight** hashing. Allows for minimal re-distribution of mappings when a server goes down.
