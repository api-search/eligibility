---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By accessing or using the Platform, you are accepting these Terms (on behalf of yourself or the entity that you represent)
    type: business
  minimum_age:
    text: You may not access or use the Platform or accept the Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Export control compliance
    text: You agree not to export, reexport, or transfer, directly or indirectly, any U.S. technical data acquired from Company, or any products utilizing such data, in violation of the United States export laws or regulations.
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
name: Buyersight
provenance_date: '2026-11-09'
provider_name: Buyersight
provider_slug: buyersight
slug: buyersight-eligibility
source_date: '2026-11-09'
source_filename: buyersight-eligibility.yml
source_heading: Eligibility
source_page: https://app.buyersight.io/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Buyersight\naid: buyersight\nurl: https://app.buyersight.io/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By accessing or using the Platform, you are accepting these Terms (on behalf of yourself or the entity that\n    you represent)\nrestricted_uses:\n- summary: Export control compliance\n  text: You agree not to export, reexport, or transfer, directly or indirectly, any U.S. technical data acquired\n    from Company, or any products utilizing such data, in violation of the United States export laws or regulations.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may not access or use the Platform or accept the Terms if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/buyersight/eligibility/buyersight-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Buyersight's own page on 2026-11-09.
synthetic: false
tags:
- Sales
- Artificial Intelligence
- Outbound
- B2B
- Marketing
---
