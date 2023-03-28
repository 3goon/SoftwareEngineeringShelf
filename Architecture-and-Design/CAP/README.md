# CAP Theorem

- **C**onsistency : Every read receives the most recent write or an error.
- **A**vailability : Every request receives a (non-error) response without guaranteeing it contains the most recent write.
- **P**artition tolerance: The system continues to operate despite an arbitrary number of messages being dropped (or delayed) by the network between nodes.


## Nice to remember 
 - We could not have all three at the same time
 - Consistency, as defined in the `CAP` theorem, is quite different from the consistency guaranteed in `ACID` database transactions.

## Source(s) 
- [WikiPedia](https://en.wikipedia.org/wiki/CAP_theorem)
- [Youtube](https://www.youtube.com/watch?v=gkg-FAEXIkY)
