---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - EU
    - GB
    served:
    - CA
    - US
    text: The site and services are intended for individuals and businesses located in Canada (excluding the province of Quebec) and the United States. I make no representation that the site or services are appropriate, legal, or available for use elsewhere, including the European Union, the United Kingdom, or the province of Quebec.
  entity_types:
  - text: The site and services are intended for individuals and businesses located in Canada (excluding the province of Quebec) and the United States.
    type: individual
  - text: The site and services are intended for individuals and businesses located in Canada (excluding the province of Quebec) and the United States.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Automation not for health care providers
    text: Automation is not offered to health care providers, or for any health or patient information.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- EU
- GB
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DigiCatalyst Systems
provenance_date: '2026-11-09'
provider_name: DigiCatalyst Systems
provider_slug: digicatalyst-ca
slug: digicatalyst-ca-eligibility
source_date: '2026-11-09'
source_filename: digicatalyst-ca-eligibility.yml
source_heading: Eligibility
source_page: https://digicatalyst.ca/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DigiCatalyst Systems\naid: digicatalyst-ca\nurl: https://digicatalyst.ca/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  - US\n  excluded:\n  - EU\n  - GB\n  text: The site and services are intended for individuals and businesses located in Canada (excluding the province\n    of Quebec) and the United States. I make no representation that the site or services are appropriate, legal,\n    or available for use elsewhere, including the European Union, the United Kingdom, or the province of Quebec.\nentity_types:\n- type: individual\n  text: The site and services are intended for individuals\
  \ and businesses located in Canada (excluding the province\n    of Quebec) and the United States.\n- type: business\n  text: The site and services are intended for individuals and businesses located in Canada (excluding the province\n    of Quebec) and the United States.\nrestricted_uses:\n- summary: Automation not for health care providers\n  text: Automation is not offered to health care providers, or for any health or patient information.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/digicatalyst-ca/eligibility/digicatalyst-ca-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from DigiCatalyst Systems's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web Design
- SEO
- Local SEO
- Automation
- Small Business
- Canada
- Toronto
---
