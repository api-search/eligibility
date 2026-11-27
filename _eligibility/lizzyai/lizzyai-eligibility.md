---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Export compliance: You represent and warrant that you are not listed on any US government list of prohibited or restricted parties or located in (or a national of) a country subject to a US government embargo'
  entity_types:
  - text: If you are an agency, department, employee or other entity of the United States Government, then your access to and use of the Software and/or the Documentation shall be subject solely to the terms and conditions of this Agreement.
    type: government
  minimum_age:
    text: You affirm that you are of a legal age in your jurisdiction to form a binding contract, but in any event over eighteen (18) years.
    value: '18'
  restricted_uses:
  - summary: Not for mission critical or high-risk use
    text: THE SOFTWARE IS NOT DESIGNED OR INTENDED FOR USE IN CONJUNCTION WITH MISSION CRITICAL AND/OR HIGH-RISK APPLICATIONS
  - summary: No weapons of mass destruction or ITAR-controlled activities
    text: You agree that the Software will not be used for activities related to weapons of mass destruction, or other activities controlled under the US International Traffic in Arms Regulations.
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
name: Lizzyai
provenance_date: '2026-11-09'
provider_name: Lizzyai
provider_slug: lizzyai
slug: lizzyai-eligibility
source_date: '2026-11-09'
source_filename: lizzyai-eligibility.yml
source_heading: Eligibility
source_page: https://lizzyai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lizzyai\naid: lizzyai\nurl: https://lizzyai.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Export compliance: You represent and warrant that you are not listed on any US government list of prohibited\n    or restricted parties or located in (or a national of) a country subject to a US government embargo'\nentity_types:\n- type: government\n  text: If you are an agency, department, employee or other entity of the United States Government, then your access\n    to and use of the Software and/or the Documentation shall be subject solely to the terms and conditions of this\n\
  \    Agreement.\nrestricted_uses:\n- summary: Not for mission critical or high-risk use\n  text: THE SOFTWARE IS NOT DESIGNED OR INTENDED FOR USE IN CONJUNCTION WITH MISSION CRITICAL AND/OR HIGH-RISK APPLICATIONS\n- summary: No weapons of mass destruction or ITAR-controlled activities\n  text: You agree that the Software will not be used for activities related to weapons of mass destruction, or other\n    activities controlled under the US International Traffic in Arms Regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You affirm that you are of a legal age in your jurisdiction to form a binding contract, but in any event\n    over eighteen (18) years.\n"
source_yaml_url: https://artifacts.apis.io/lizzyai/eligibility/lizzyai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Lizzyai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal AI
- Generative AI
- Artificial Intelligence
- Legal Tech
- Document Management
- Contract Review
- Software-as-a-Service
---
