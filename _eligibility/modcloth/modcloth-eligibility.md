---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: makes no representation that the Site ... [is] appropriate or available for use in locations other than the United States of America or Canada.
  entity_types:
  - text: By using the Service, you confirm that you are at least 18 years old (or the legal age of majority in your jurisdiction) and capable of forming a binding contract.
    type: individual
  - text: If you are accessing or using the Service on behalf of an entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: By using the Service, you confirm that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: The Site may be used only for lawful purposes by individuals using authorized services of ModCloth.
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
name: Modcloth
provenance_date: '2026-11-10'
provider_name: Modcloth
provider_slug: modcloth
slug: modcloth-eligibility
source_date: '2026-11-10'
source_filename: modcloth-eligibility.yml
source_heading: Eligibility
source_page: https://modcloth.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Modcloth\naid: modcloth\nurl: https://modcloth.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: makes no representation that the Site ... [is] appropriate or available for use in locations other than\n    the United States of America or Canada.\nentity_types:\n- type: individual\n  text: By using the Service, you confirm that you are at least 18 years old (or the legal age of majority in your\n    jurisdiction) and capable of forming a binding contract.\n- type: business\n  text: If you are accessing or using the Service on behalf of an entity,\
  \ you represent and warrant that you have\n    the authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: The Site may be used only for lawful purposes by individuals using authorized services of ModCloth.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Service, you confirm that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/modcloth/eligibility/modcloth-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Modcloth's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Retail
- E-Commerce
- Fashion
- Apparel
- Shopify
- Agentic Commerce
- MCP
---
