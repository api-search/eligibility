---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you choose to access the Service from outside of the United States, you are responsible for complying with applicable local laws.
  entity_types:
  - text: The Service is intended for individuals 18 years of age or older.
    type: individual
  minimum_age:
    text: The Service is intended for individuals 18 years of age or older. By accessing or using the Service, you represent and warrant that you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Service only for lawful purposes and in accordance with these Terms of Use.
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
name: Iris Labs
provenance_date: '2026-11-09'
provider_name: Iris Labs
provider_slug: iris-labs
slug: iris-labs-eligibility
source_date: '2026-11-09'
source_filename: iris-labs-eligibility.yml
source_heading: Eligibility
source_page: https://irislabs.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Iris Labs\naid: iris-labs\nurl: https://irislabs.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you choose to access the Service from outside of the United States, you are responsible for complying\n    with applicable local laws.\nentity_types:\n- type: individual\n  text: The Service is intended for individuals 18 years of age or older.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Service only for lawful purposes and in accordance with these Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: The Service is intended for individuals 18 years of age or older. By accessing or using the Service, you\n    represent and warrant that you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/iris-labs/eligibility/iris-labs-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Iris Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Imaging
- Healthcare
- Data Analytics
- Artificial Intelligence
---
