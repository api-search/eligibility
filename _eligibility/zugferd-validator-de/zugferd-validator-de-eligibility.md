---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Der Dienst richtet sich ausschließlich an Unternehmer im Sinne des § 14 BGB
    type: business
  - text: juristische Personen des öffentlichen Rechts und öffentlich-rechtliche Sondervermögen
    type: government
  - text: Ein Vertragsschluss mit Verbrauchern ist nicht vorgesehen.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No consumer contracts
    text: Ein Vertragsschluss mit Verbrauchern ist nicht vorgesehen.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: zugferd-validator-de
provenance_date: '2026-11-10'
provider_name: zugferd-validator-de
provider_slug: zugferd-validator-de
slug: zugferd-validator-de-eligibility
source_date: '2026-11-10'
source_filename: zugferd-validator-de-eligibility.yml
source_heading: Eligibility
source_page: https://zugferd-validator.de/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: zugferd-validator-de\naid: zugferd-validator-de\nurl: https://zugferd-validator.de/agb\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Der Dienst richtet sich ausschließlich an Unternehmer im Sinne des § 14 BGB\n- type: government\n  text: juristische Personen des öffentlichen Rechts und öffentlich-rechtliche Sondervermögen\n- type: individual\n  text: Ein Vertragsschluss mit Verbrauchern ist nicht vorgesehen.\nrestricted_uses:\n- summary: No consumer contracts\n  text: Ein Vertragsschluss mit Verbrauchern ist nicht vorgesehen.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zugferd-validator-de/eligibility/zugferd-validator-de-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from zugferd-validator-de's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Validation
- E-Invoicing
- Germany
---
