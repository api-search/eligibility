---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You - the individual or organisation accessing or using the Service.
    type: individual
  - text: Where you are acting on behalf of an organisation, you have authority to bind that organisation
    type: business
  minimum_age:
    text: You are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Unlawful purposes
    text: Use the Service for any unlawful purpose or in violation of applicable laws or regulations
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
name: formpaste-com
provenance_date: '2026-11-09'
provider_name: formpaste-com
provider_slug: formpaste-com
slug: formpaste-com-eligibility
source_date: '2026-11-09'
source_filename: formpaste-com-eligibility.yml
source_heading: Eligibility
source_page: https://formpaste.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: formpaste-com\naid: formpaste-com\nurl: https://formpaste.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You - the individual or organisation accessing or using the Service.\n- type: business\n  text: Where you are acting on behalf of an organisation, you have authority to bind that organisation\nrestricted_uses:\n- summary: Unlawful purposes\n  text: Use the Service for any unlawful purpose or in violation of applicable laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: You are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/formpaste-com/eligibility/formpaste-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from formpaste-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Form
- Contact
- Free
---
