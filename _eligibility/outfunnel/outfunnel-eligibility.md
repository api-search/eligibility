---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Client”, “you” and “your” refer to the individual person, company or organisation that is using the Service.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctions and trade control compliance
    text: Third Party shall take no action, directly or indirectly, that would cause Outfunnel or any of its Affiliates, or any of their respective officers, directors, employees, or representatives, to violate any Sanctions or Trade Controls.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide your legal full name, company name and a valid work email address and any other information requested by us in order to complete the signup process and use the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Outfunnel
provenance_date: '2026-11-10'
provider_name: Outfunnel
provider_slug: outfunnel
slug: outfunnel-eligibility
source_date: '2026-11-10'
source_filename: outfunnel-eligibility.yml
source_heading: Eligibility
source_page: https://outfunnel.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Outfunnel\naid: outfunnel\nurl: https://outfunnel.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “Client”, “you” and “your” refer to the individual person, company or organisation that is using the Service.\nrestricted_uses:\n- summary: Sanctions and trade control compliance\n  text: Third Party shall take no action, directly or indirectly, that would cause Outfunnel or any of its Affiliates,\n    or any of their respective officers, directors, employees, or representatives, to violate any Sanctions or Trade\n    Controls.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide your legal full name, company name and a valid work email address and any other information\n    requested by us in order to complete the signup process and use the Service.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/outfunnel/eligibility/outfunnel-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Outfunnel's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sales
- Marketing
- Automation
- Integration
---
