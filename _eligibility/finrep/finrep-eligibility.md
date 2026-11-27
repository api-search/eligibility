---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Platform is intended for enterprise customers and their authorized personnel.
    type: business
  - text: The Platform is not intended for consumers or individuals in a personal capacity.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age and legally capable of entering into binding contracts.
    value: '18'
  restricted_uses:
  - summary: False financial information
    text: generate, submit, or disseminate false or materially misleading financial information
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
name: Finrep
provenance_date: '2026-11-09'
provider_name: Finrep
provider_slug: finrep
slug: finrep-eligibility
source_date: '2026-11-09'
source_filename: finrep-eligibility.yml
source_heading: Eligibility
source_page: https://www.finrep.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Finrep\naid: finrep\nurl: https://www.finrep.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Platform is intended for enterprise customers and their authorized personnel.\n- type: individual\n  text: The Platform is not intended for consumers or individuals in a personal capacity.\nrestricted_uses:\n- summary: False financial information\n  text: generate, submit, or disseminate false or materially misleading financial information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: You must be at least 18 years of age and legally capable of entering into binding contracts.\n"
source_yaml_url: https://artifacts.apis.io/finrep/eligibility/finrep-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Finrep's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Financial Reporting
- SEC Filings
- Accounting
- Fintech
- Compliance
- Disclosure
- EDGAR
---
