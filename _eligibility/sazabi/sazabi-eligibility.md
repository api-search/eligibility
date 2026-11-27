---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By accessing or using the Site, you are accepting these Terms (on behalf of yourself or the entity that you represent)
    type: business
  minimum_age:
    text: You may not access or use the Site or accept the Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Export control
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
name: Sazabi
provenance_date: '2026-11-10'
provider_name: Sazabi
provider_slug: sazabi
slug: sazabi-eligibility
source_date: '2026-11-10'
source_filename: sazabi-eligibility.yml
source_heading: Eligibility
source_page: https://www.sazabi.com/legal/website/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sazabi\naid: sazabi\nurl: https://www.sazabi.com/legal/website/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By accessing or using the Site, you are accepting these Terms (on behalf of yourself or the entity that\n    you represent)\nrestricted_uses:\n- summary: Export control\n  text: You agree not to export, reexport, or transfer, directly or indirectly, any U.S. technical data acquired\n    from Company, or any products utilizing such data, in violation of the United States export laws or regulations.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may not access or use the Site or accept the Terms if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/sazabi/eligibility/sazabi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Sazabi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Observability
- Monitoring
- Artificial Intelligence
- Agents
- MCP
- DevOps
- Incident Response
- Logging
---
