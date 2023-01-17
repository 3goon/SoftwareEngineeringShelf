# CAP Theorem

- **C**onsistency : Every read receives the most recent write or an error.
- **A**vailability : Every request receives a (non-error) response, without the guarantee that it contains the most recent write.
- **P**artition tolerance : The system continues to operate despite an arbitrary number of messages being dropped (or delayed) by the network between nodes.

---

__Nice to remember__ : 
 - We could not have all three at the same time

---

__Source(s)__ : 
- [WikiPedia](https://en.wikipedia.org/wiki/CAP_theorem)