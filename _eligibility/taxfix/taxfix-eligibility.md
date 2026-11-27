---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Die Plattform ist auf die Erstellung und elektronische Übermittlung der Einkommensteuererklärung an deutsche Finanzämter über die Nutzung der ELSTER-Schnittstelle ausgerichtet.
  entity_types:
  - text: Diese Bedingungen richten sich an Verbraucher*innen i.S.v. § 13 BGB.
    type: individual
  - text: Schließt du den Vertrag als Unternehmer*in i.S.v. § 14 BGB, gelten ergänzend und teilweise abweichend die Sonderbedingungen für Unternehmer*innen (Anlage 2)
    type: business
  minimum_age:
    text: Vertragsschlüsse über die Plattform setzen voraus, dass du unbeschränkt geschäftsfähig bist.
    value: unbeschränkt geschäftsfähig
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Für jede über die Plattform abgegebene Einkommensteuererklärung sind die nach der Abgabenordnung erforderlichen Identifikationsmerkmale zu erheben.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Taxfix
provenance_date: '2026-11-10'
provider_name: Taxfix
provider_slug: taxfix
slug: taxfix-eligibility
source_date: '2026-11-10'
source_filename: taxfix-eligibility.yml
source_heading: Eligibility
source_page: https://taxfix.de/agb/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Taxfix\naid: taxfix\nurl: https://taxfix.de/agb/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Die Plattform ist auf die Erstellung und elektronische Übermittlung der Einkommensteuererklärung an deutsche\n    Finanzämter über die Nutzung der ELSTER-Schnittstelle ausgerichtet.\nentity_types:\n- type: individual\n  text: Diese Bedingungen richten sich an Verbraucher*innen i.S.v. § 13 BGB.\n- type: business\n  text: Schließt du den Vertrag als Unternehmer*in i.S.v. § 14 BGB, gelten ergänzend und teilweise abweichend die\n    Sonderbedingungen für Unternehmer*innen (Anlage 2)\nrestricted_uses:\
  \ []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Für jede über die Plattform abgegebene Einkommensteuererklärung sind die nach der Abgabenordnung erforderlichen\n    Identifikationsmerkmale zu erheben.\nminimum_age:\n  value: unbeschränkt geschäftsfähig\n  text: Vertragsschlüsse über die Plattform setzen voraus, dass du unbeschränkt geschäftsfähig bist.\n"
source_yaml_url: https://artifacts.apis.io/taxfix/eligibility/taxfix-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from Taxfix's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Tax
- Tax Filing
- Personal Finance
- Germany
- Mobile
---
