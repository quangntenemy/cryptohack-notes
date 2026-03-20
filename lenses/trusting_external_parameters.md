## Trusting External Parameters

Systems often rely on shared constants to maintain consistency.

When those constants are allowed to vary — especially under user control —
the system no longer verifies authenticity, only internal consistency.

At that point, validation becomes circular:
the system confirms values derived from inputs it never should have trusted.

---

### Observation

If both the input and the rule used to validate that input are influenced by the same source,
the check loses meaning.

---

### Takeaway

Security assumptions fail when control boundaries are unclear.
What is meant to be fixed must remain fixed.
