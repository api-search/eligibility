---
api_specs:
- filename: saas-alerts-events-api-openapi.yml
  format: yaml
  label: SaaS Alerts Events API
  slug: saas-alerts-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saas-alerts/openapi/saas-alerts-events-api-openapi.yml
- filename: saas-alerts-reports-api-openapi.yml
  format: yaml
  label: SaaS Alerts Reports API
  slug: saas-alerts-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saas-alerts/openapi/saas-alerts-reports-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a United States governmental entity, please be aware that the Website and all SA goods and services are commercial in nature, and therefore subject to the restrictions set forth in DFARS 252.227-7015 and FAR 52.227-19.
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Malware and interference
    text: Transmitting or introducing any material that contains software viruses or any other malware designed to interrupt, destroy or limit the functionality of any computer software or hardware or equipment
  - summary: Circumventing security
    text: Circumventing any encryption or other security tool(s) used anywhere on a Website
  - summary: Reverse engineering
    text: Reverse engineering, deciphering, decompiling or otherwise disassembling any portion of the Website
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
name: SaaS Alerts
provenance_date: '2026-11-10'
provider_name: SaaS Alerts
provider_slug: saas-alerts
slug: saas-alerts-eligibility
source_date: '2026-11-10'
source_filename: saas-alerts-eligibility.yml
source_heading: Eligibility
source_page: https://saasalerts.com/terms-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SaaS Alerts\naid: saas-alerts\nurl: https://saasalerts.com/terms-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: If you are a United States governmental entity, please be aware that the Website and all SA goods and services\n    are commercial in nature, and therefore subject to the restrictions set forth in DFARS 252.227-7015 and FAR\n    52.227-19.\nrestricted_uses:\n- summary: Malware and interference\n  text: Transmitting or introducing any material that contains software viruses or any other malware designed to\n    interrupt,\
  \ destroy or limit the functionality of any computer software or hardware or equipment\n- summary: Circumventing security\n  text: Circumventing any encryption or other security tool(s) used anywhere on a Website\n- summary: Reverse engineering\n  text: Reverse engineering, deciphering, decompiling or otherwise disassembling any portion of the Website\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/saas-alerts/eligibility/saas-alerts-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from SaaS Alerts's own page on 2026-11-10.
synthetic: false
tags:
- MSP
- SaaS Security
- Security Monitoring
- Threat Detection
- Microsoft 365
- Google Workspace
- MSSP
---
