# Customs Forms (customs-forms)

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
