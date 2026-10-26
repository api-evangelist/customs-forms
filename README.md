# Customs Forms (customs-forms)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Customs forms are the standardized declarations and supporting documents required to move goods across international borders. Common forms include CBP Form 7501 (Entry Summary), CBP Form 3461 (Entry/Immediate Delivery), the commercial invoice, packing list, certificate of origin, CN22/CN23 postal declarations, and the EU Single Administrative Document. Most are now filed electronically through national customs systems (ACE, CDS, ICS2, NACCS), while parcel carriers expose shipping APIs that generate customs paperwork on behalf of shippers.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/customs-forms/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** Public
- **x-type:** topic

## Tags

- CBP Forms, Certificate of Origin, CN22, CN23, Commercial Invoice, Compliance, Customs, Customs Forms, Declarations, International Trade, Logistics, Packing List, SAD, Shipping

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-28

## APIs

No standalone customs form APIs are catalogued here. Form generation is typically delivered as a feature of carrier shipping APIs (UPS, FedEx, DHL, USPS) and customs broker / GTM platforms; national customs systems accept structured EDI/XML rather than form image submission.

## Authoritative Forms and References

- [CBP Forms (full catalogue)](https://www.cbp.gov/newsroom/publications/forms)
- [CBP Form 7501 — Entry Summary](https://www.cbp.gov/document/forms/form-7501-entry-summary)
- [CBP Form 3461 — Entry/Immediate Delivery](https://www.cbp.gov/document/forms/form-3461-entryimmediate-delivery)
- [USPS International Customs Forms](https://www.usps.com/international/customs-forms.htm)
- [Universal Postal Union (UPU) — CN22 / CN23](https://www.upu.int/)
- [EU Single Administrative Document (SAD)](https://taxation-customs.ec.europa.eu/customs-4/customs-procedures-import-and-export-0/customs-declaration_en)
- [USMCA Certificate of Origin](https://www.cbp.gov/trade/free-trade-agreements/usmca)
- [WCO Rules of Origin](https://www.wcoomd.org/en/topics/origin/instrument-and-tools.aspx)
- [WCO Harmonized System Nomenclature](https://www.wcoomd.org/en/topics/nomenclature/instrument-and-tools/hs-nomenclature-2022-edition.aspx)
- [U.S. Harmonized Tariff Schedule](https://hts.usitc.gov/)

## Vocabulary

- **Entry Summary (CBP 7501)** — Summary of the goods being entered, used to assess duties.
- **Entry / Immediate Delivery (CBP 3461)** — Cargo release request submitted prior to or on arrival.
- **Commercial Invoice** — Seller's invoice describing the goods, parties, terms, and value.
- **Certificate of Origin** — Declaration of the country in which the goods were produced; required for FTA preferential rates.
- **CN22 / CN23** — UPU postal customs declaration forms for low-value and standard parcels respectively.
- **Single Administrative Document (SAD)** — Standard EU import / export / transit declaration.
- **Packing List** — Itemized list of contents, weights, and dimensions per package.
- **Shipper's Letter of Instruction (SLI)** — Exporter instructions to a freight forwarder.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
