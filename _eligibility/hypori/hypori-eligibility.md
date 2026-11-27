---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Products are intended for use in jurisdictions where they are lawfully available. Access from jurisdictions where such access is illegal is prohibited.
  entity_types:
  - text: If you are accessing the Products on behalf of an organization, you represent that you are authorized to do so.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Products.
    value: '18'
  restricted_uses:
  - summary: Export and sanctions
    text: You may not access or use the Products in violation of applicable export control or sanctions laws.
  - summary: Government Cloud access
    text: Access to Hypori Government Cloud may be restricted based on security, citizenship, residency, clearance, or eligibility requirements.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If your organization has not entered into an agreement with Hypori, you may not access the Products.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hypori
provenance_date: '2026-11-09'
provider_name: Hypori
provider_slug: hypori
slug: hypori-eligibility
source_date: '2026-11-09'
source_filename: hypori-eligibility.yml
source_heading: Eligibility
source_page: https://www.hypori.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hypori\naid: hypori\nurl: https://www.hypori.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Products are intended for use in jurisdictions where they are lawfully available. Access from jurisdictions\n    where such access is illegal is prohibited.\nentity_types:\n- type: business\n  text: If you are accessing the Products on behalf of an organization, you represent that you are authorized to\n    do so.\nrestricted_uses:\n- summary: Export and sanctions\n  text: You may not access or use the Products in violation of applicable export control or sanctions\
  \ laws.\n- summary: Government Cloud access\n  text: Access to Hypori Government Cloud may be restricted based on security, citizenship, residency, clearance,\n    or eligibility requirements.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If your organization has not entered into an agreement with Hypori, you may not access the Products.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Products.\n"
source_yaml_url: https://artifacts.apis.io/hypori/eligibility/hypori-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Hypori's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Mobile
- Virtualization
- Zero Trust
- BYOD
- Government
- Defense
- Compliance
- Identity
- Software-as-a-Service
---
