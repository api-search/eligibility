---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By accepting these Terms, you are representing and warranting that (i) you have the legal authority to bind your employer or the entity you are representing to these Terms
    type: business
  - text: If you are using the Service for personal use only (i.e., not on behalf of any organization, business, or other legal entity) and have signed up for your Conduitly account using a personal email address, then all references to “You” in these Terms mean you as an individual.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: Utilize the Service to conduct unlawful or fraudulent activity
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
name: Conduitly
provenance_date: '2026-11-09'
provider_name: Conduitly
provider_slug: conduitly
slug: conduitly-eligibility
source_date: '2026-11-09'
source_filename: conduitly-eligibility.yml
source_heading: Eligibility
source_page: https://www.conduitly.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Conduitly\naid: conduitly\nurl: https://www.conduitly.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By accepting these Terms, you are representing and warranting that (i) you have the legal authority to bind\n    your employer or the entity you are representing to these Terms\n- type: individual\n  text: If you are using the Service for personal use only (i.e., not on behalf of any organization, business, or\n    other legal entity) and have signed up for your Conduitly account using a personal email address,\
  \ then all references\n    to “You” in these Terms mean you as an individual.\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text: Utilize the Service to conduct unlawful or fraudulent activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/conduitly/eligibility/conduitly-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Conduitly's own page on 2026-11-09.
synthetic: false
tags:
- Integration
- Automation
- Workflows
- Business Software
---
