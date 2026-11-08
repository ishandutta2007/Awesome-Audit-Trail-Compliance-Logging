# Awesome-Audit-Trail-Compliance-Logging

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag what the search results actually support, because **the open-source side of your list is empty**, and several entries have no usable current pricing.



## The data problems



**"Freshworks Audit Logs" is not a standalone product.** Freshworks CRM audit logs track configuration changes (workflows, sequences, territories, account settings) for **90 days**, visible to Account Admins and Admins . Freshdesk audit logs track account subscription, agent, authentication, automation, and knowledge base changes . Neither is a platform you buy separately—they are admin features included with the CRM/support product.



**Splunk's pricing page returned only Observability Cloud pricing** ($15/host/month) , not Splunk Enterprise or Enterprise Security. **No current SIEM price surfaced.** Do not fabricate one.



**Datadog Cloud SIEM's pricing page returned only a free learning course** ($0.00) , not the per-GB or per-million-event rate. A Datadog docs page confirms Cloud SIEM bills on **total GB analyzed** , but no rate is stated.



**LogRhythm's price is from a 2016 SC Magazine review**: **$32,000 plus 20% annual maintenance** . That is **ten years old**. Do not present it as current pricing.



**Elastic has published current pricing**: **Security Analytics Essentials from $0.09/GB ingest, $0.017/GB retained per month**; **Complete from $0.11/GB ingest, $0.019/GB retained** . **Per-endpoint fees were eliminated on March 23, 2026** . This is the most reliable data in the results.



**Sumo Logic has published Flex pricing**: **$0 ingest, unlimited users, pay per TB scanned**—estimated **$3.14 per TB scanned** .



**Graylog has a datasheet but no list price.** It emphasizes "predictable pricing" based on analysis rather than ingest, with selective retrieval . No dollar figures.



**AuditBoard and Panther are quote-only.** Panther's own blog states managed SIEM budgets are "in the six figures annually," with hidden costs causing **25%–50% cost overruns** . No specific AuditBoard price surfaced.



**The open-source section has exactly one genuine entry: `audittrail`.** It is a **Python library** for tamper-proof audit logging in FastAPI, with hash-chained entries, encrypted payloads, and optional compliance features (RSA signatures, WORM protection, anomaly detection) . It is **not a SIEM or log management platform**—it is middleware for your own application.



## What the search results actually contain



| Platform | Pricing data | Status |

|---|---|---|

| **Elastic Security** | **$0.09–$0.11/GB ingest; $0.017–$0.019/GB retained**  | Current, verified |

| **Sumo Logic** | **$3.14/TB scanned** (Flex)  | Current, verified |

| **Freshworks** | Admin feature, 90-day retention  | Not sold separately |

| **Splunk** | **Not surfaced**  | Do not fabricate |

| **Datadog** | **Not surfaced**  | Do not fabricate |

| **LogRhythm** | **$32,000 + 20% maintenance (2016)**  | **Ten years old—do not cite as current** |

| **Graylog** | **No list price**  | Quote-only |

| **AuditBoard** | **Not surfaced** | Quote-only |

| **Panther** | **"Six figures annually"**  | Quote-only |

| **Papertrail** | **Not surfaced** | Do not fabricate |



## What I recommend



**Remove "Freshworks Audit Logs"** from the platform list. It is an admin feature, not a standalone compliance logging product. If you mention it, note the 90-day retention and module coverage .



**The open-source section should be honest about its limits.** `audittrail` is the only open-source entry , and it is a **Python middleware library for application-level audit logging**, not a SIEM or log management platform. Do not present it as a replacement for Splunk or Elastic.



**The SaaS section has verified current pricing for Elastic and Sumo Logic only.** Splunk, Datadog, LogRhythm, Graylog, AuditBoard, Panther, and Papertrail should be marked **"pricing not surfaced"** or **"quote-only."** LogRhythm's 2016 figure must be labeled as historical, not current .



If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not fabricate Splunk or Datadog SIEM pricing, present Freshworks audit logs as a standalone product, or cite LogRhythm's 2016 price as current.
