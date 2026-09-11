# My Notes — \[JENNIFER ILOHA]

## Key Concepts I Learned

<!-- Write the main ideas covered in today's session -->

* Learned how Azure Key Vault helps protect secrets, keys, certificates and other sensitive information.
* Understood how Defense in Depth can be applied to protect Key Vault and cloud/AI workloads across multiple security layers.
* Network-level protections — private endpoints, firewalls and restricting public access to Key Vault
* Incident response process when an alert fires — four steps: identify the source, respond to the immediate threat, measure the impact, and take action.
* Microsoft Defender for Key Vault — Protects the vault from external threats.
* Defender for CSPM (Cloud Security Posture Management) scanning: Protects the environment from secrets exposed outside the vault.









\---

## Lab / Hands-On Work

<!-- Describe what you did in the lab. Include steps, commands, or screenshots descriptions -->



### What I did



* Created a new Azure Key Vault instance.
* Created a key, a certificate and a secret within the vault
* Explored the vault's features and settings to get familiar with how it works.



### What happened / Result



* Successfully set up the Key Vault and confirmed the key, certificate, and secret were created and stored
* Got a clearer picture of how Key Vault manages versions of secrets and keys over time, and how monitoring/logging fits into securing the vault





### Challenges I faced



There were no major challenges during the session.



\---

## My Takeaways

<!-- What was most valuable to you personally from this session? -->



This session made it clear that protecting a single secret takes multiple layers working together — identity, versioning, monitoring, and recovery settings all have to align. Learning why old versions of keys and secrets are retained (rather than deleted) was a good reminder that security isn't just about locking things down, it's also about being able to recover and audit when needed.Key Vault security recommendations: enable soft delete, enable purge protection, and enable diagnostic logs.





\---

## Questions I Still Have

<!-- Anything you want to follow up on or ask the mentor -->

* NONE
* 

\---

## Resources I Found Useful

<!-- Any links, docs, or Microsoft Learn modules you found helpful -->

* https://youtu.be/GKqpej4X9B0?t=9325
* Microsoft Learn SC-500 learning materials.

\---

*Submitted by: \[Jennifer Iloha] · \[Jennifer Iloha]*

