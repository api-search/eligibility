---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    type: individual
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You agree not to export, reexport, or transfer, directly or indirectly, any U.S. technical data acquired from Evermore, or any products utilizing such data, in violation of the United States export laws or regulations.
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
name: Evermore
provenance_date: '2026-11-09'
provider_name: Evermore
provider_slug: evermore
slug: evermore-eligibility
source_date: '2026-11-09'
source_filename: evermore-eligibility.yml
source_heading: Eligibility
source_page: https://evermoreoutcomes.com/wp-content/uploads/2025/10/evermore-Terms-of-Use-10.15.25.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Evermore\naid: evermore\nurl: https://evermoreoutcomes.com/wp-content/uploads/2025/10/evermore-Terms-of-Use-10.15.25.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\nrestricted_uses:\n- summary: Export restrictions\n  text: You agree not to export, reexport, or transfer, directly or indirectly, any U.S. technical data acquired\n    from Evermore, or any products utilizing such data, in violation of the United States export laws or regulations.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/evermore/eligibility/evermore-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Evermore's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Benefits
- Benefits Administration
- Medicare Advantage
- Medicaid
- Smart Benefits
- Health Plans
- Fintech
---
