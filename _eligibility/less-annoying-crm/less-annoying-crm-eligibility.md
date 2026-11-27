---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Violation of laws
    text: You may not use the Service in violation of any laws in your jurisdiction.
  - summary: Malicious code
    text: You may not use the Service to transmit any malicious code, such as viruses or worms.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide a valid name, a valid email address, and any other information requested as a part of the signup process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Less Annoying CRM
provenance_date: '2026-11-09'
provider_name: Less Annoying CRM
provider_slug: less-annoying-crm
slug: less-annoying-crm-eligibility
source_date: '2026-11-09'
source_filename: less-annoying-crm-eligibility.yml
source_heading: Eligibility
source_page: https://lessannoyingcrm.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Less Annoying CRM\naid: less-annoying-crm\nurl: https://lessannoyingcrm.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Violation of laws\n  text: You may not use the Service in violation of any laws in your jurisdiction.\n- summary: Malicious code\n  text: You may not use the Service to transmit any malicious code, such as viruses or worms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide a valid name, a valid email address, and any other information requested as a part of\
  \ the\n    signup process.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/less-annoying-crm/eligibility/less-annoying-crm-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Less Annoying CRM's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CRM
- Small Business
- Contact Management
- Software-as-a-Service
---
