---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents it is not located in, or a national of, a country that is subject to a U.S. government embargo or has been designated by the U.S. government as a state sponsor of terrorism;
  entity_types:
  - text: 'If you are using Services on behalf of an entity or organization that you represent: (1) all references to “Customer” are to that entity or organization'
    type: business
  - text: To the extent Customer is an agency of, or otherwise represents, the United States federal government
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted Information
    text: unless otherwise agreed to by Exaforce in writing, Customer must not use the Services to process Restricted Information.
  - summary: ITAR-controlled information
    text: will not use any Service or Support to process information that is controlled under the U.S. International Traffic in Arms Regulations.
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
name: Exaforce
provenance_date: '2026-11-09'
provider_name: Exaforce
provider_slug: exaforce
slug: exaforce-eligibility
source_date: '2026-11-09'
source_filename: exaforce-eligibility.yml
source_heading: Eligibility
source_page: https://www.exaforce.com/policy-archive/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Exaforce\naid: exaforce\nurl: https://www.exaforce.com/policy-archive/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents it is not located in, or a national of, a country that is subject to a U.S. government\n    embargo or has been designated by the U.S. government as a state sponsor of terrorism;\nentity_types:\n- type: business\n  text: 'If you are using Services on behalf of an entity or organization that you represent: (1) all references\n    to “Customer” are to that entity or organization'\n- type: government\n  text: To\
  \ the extent Customer is an agency of, or otherwise represents, the United States federal government\nrestricted_uses:\n- summary: Restricted Information\n  text: unless otherwise agreed to by Exaforce in writing, Customer must not use the Services to process Restricted\n    Information.\n- summary: ITAR-controlled information\n  text: will not use any Service or Support to process information that is controlled under the U.S. International\n    Traffic in Arms Regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/exaforce/eligibility/exaforce-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Exaforce's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Security Operations
- SOC
- SIEM
- Threat Detection
- Incident Response
- Artificial Intelligence
- AI Agents
- Managed Detection and Response
- Cloud Security
---
