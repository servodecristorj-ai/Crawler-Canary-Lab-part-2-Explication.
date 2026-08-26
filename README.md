# Experiment 002 — Crawler Exposes Itself (Public Summary)
For journalism / defensive research

Finding
When a honeypot redirects to a crawler's own public documentation, the crawler is forced to fetch it, revealing that it uses multiple IP ranges for the same task.

Observed: Meta's crawler produced logs from two distinct ranges (indexing edge and validation edge) when exposed to self-reference.

Why it matters for publishers
If you block only one range, the second still validates your paywalled URL. This is evidence of multi-egress infrastructure - useful for reporting on AI scraping.

Note
Full methodology, tokens, and complete IPs are withheld from this public summary for responsible disclosure. They are available in the private audit version under NDA.

License: MIT - Defensive use only


