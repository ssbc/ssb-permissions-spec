:warning: **Status: gathering requirements** :warning

---

# ssb-permissions-spec

## Problem

In the context of private groups, we may want to establish "rules" for who is allowed to do what.


## User Journeys

A collection of stories about how "permisions" would work in real situtations.

We can use these to more quickly surface the nature of the problem, and also as tests to have our potential solutions have to pass.

1. I have a group which has 4 "admins" and only these admins are allowed to create new "decision" threads in our group.
2. I make a gathering which only me and 2 friends are allowed to edit, but anyone can say they are attendind

---

## Possible Solutions

## Principles

1. Simple to implement in multiple languages


## Questions

1. Are permissions broader than just "private groups"
2. Is this an extension of the "free listening" idea? (since permission to speak is almost impossible in a p2p space)
3. Where does the power/authority come from to start some permissions rule?
    - a) does it all flow from the group initiator?
    - b) could anyone make a permission rule and people attest that they are going to consent to follow that? (anarchy / bottom up organising woo!!)


## Prior art

- [ssb-crut-authors](https://gitlab.com/ahau/lib/ssb-crut-authors/)
    - allows you to build a list of "valid authors" inro a particulat document/record/thread
    - anyone can publish anything, but this defines a clear way to _reduce_ messages posts which adhere to the "valid authors" at each point in the tangle
    - problems:
        - this just defines "authorship" permission
        - it ties "permission" to the record. We've seen that it would be much more helpful to be able to define that permission elsewhere and then records can say which permissions definitions they're following. This introduces more complexity but Mix + the Pandas have done some planning on this.



