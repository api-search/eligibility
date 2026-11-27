---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer is located in a region that is prohibited from using the Services by law.
  entity_types:
  - text: the entity you represent (the "Customer") is hereby agreeing with Indusface Inc. to the following terms of service
    type: business
  minimum_age:
    text: null
    value: null
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
name: Indusface
provenance_date: '2026-11-09'
provider_name: Indusface
provider_slug: indusface
slug: indusface-eligibility
source_date: '2026-11-09'
source_filename: indusface-eligibility.yml
source_heading: Eligibility
source_page: https://www.indusface.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Indusface\naid: indusface\nurl: https://www.indusface.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer is located in a region that is prohibited from using the Services by law.\nentity_types:\n- type: business\n  text: the entity you represent (the \"Customer\") is hereby agreeing with Indusface Inc. to the following terms\n    of service\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/indusface/eligibility/indusface-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Indusface's own page on 2026-11-09.
synthetic: false
tags:
- Security
- Web Application Firewall
- Cloud
- Artificial Intelligence
- Enterprise
---
