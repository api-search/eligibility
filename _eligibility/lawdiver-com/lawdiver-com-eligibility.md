---
api_specs:
- filename: lawdiver-com-openapi-generated.yml
  format: yaml
  label: LawDiver API
  slug: lawdiver-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lawdiver-com/openapi/_ae-authored/lawdiver-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: LawDiver is offered solely to persons located in the United States.
  entity_types:
  - text: If you use the Service on behalf of an organization, you represent that you have authority to bind that organization, and "you" includes that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: use the Service only for lawful purposes and in compliance with these Terms and applicable law
  - summary: No unauthorized practice of law
    text: not use the Service to provide legal advice to others in a manner that would constitute the unauthorized practice of law in any jurisdiction
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
name: LawDiver
provenance_date: '2026-11-09'
provider_name: LawDiver
provider_slug: lawdiver-com
slug: lawdiver-com-eligibility
source_date: '2026-11-09'
source_filename: lawdiver-com-eligibility.yml
source_heading: Eligibility
source_page: https://lawdiver.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LawDiver\naid: lawdiver-com\nurl: https://lawdiver.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: LawDiver is offered solely to persons located in the United States.\nentity_types:\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you have authority to bind that\n    organization, and \"you\" includes that organization.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: use the Service only for lawful purposes and in compliance with these Terms and applicable law\n- summary: No unauthorized practice of law\n\
  \  text: not use the Service to provide legal advice to others in a manner that would constitute the unauthorized\n    practice of law in any jurisdiction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lawdiver-com/eligibility/lawdiver-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from LawDiver's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal Tech
- Legal Research
- Free
---
