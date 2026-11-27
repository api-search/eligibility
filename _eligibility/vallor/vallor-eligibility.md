---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Vallor does not provide services to governments, governmental agencies, businesses, individuals, other groups, or any of their agents that are subject to U.S. trade sanctions.
  entity_types:
  - text: you may use and access the Services and AI Components solely as an authorized user for your Organization’s internal business purposes
    type: business
  minimum_age:
    text: You may not access or use the SERVICES OR AI COMPONENTS or accept these Terms if you have not reached the age of consent in your jurisdiction
    value: null
  restricted_uses:
  - summary: Protected health information without BAA
    text: falls within the definition of “Protected Health Information” under the HIPAA Privacy Rule (45 C.F.R. Section 160.103 ), unless you have entered into a current Business Associate Agreement or similar document with Vallor
  - summary: Nonpublic personal information under GLBA
    text: falls within the definition of “Nonpublic Personal Information” under the Gramm-Leach-Bliley Act.
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
name: Vallor
provenance_date: '2026-11-10'
provider_name: Vallor
provider_slug: vallor
slug: vallor-eligibility
source_date: '2026-11-10'
source_filename: vallor-eligibility.yml
source_heading: Eligibility
source_page: https://vallor.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vallor\naid: vallor\nurl: https://vallor.ai/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Vallor does not provide services to governments, governmental agencies, businesses, individuals, other groups,\n    or any of their agents that are subject to U.S. trade sanctions.\nentity_types:\n- type: business\n  text: you may use and access the Services and AI Components solely as an authorized user for your Organization’s\n    internal business purposes\nrestricted_uses:\n- summary: Protected health information without BAA\n  text: falls within the definition of “Protected\
  \ Health Information” under the HIPAA Privacy Rule (45 C.F.R. Section\n    160.103 ), unless you have entered into a current Business Associate Agreement or similar document with Vallor\n- summary: Nonpublic personal information under GLBA\n  text: falls within the definition of “Nonpublic Personal Information” under the Gramm-Leach-Bliley Act.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You may not access or use the SERVICES OR AI COMPONENTS or accept these Terms if you have not reached the\n    age of consent in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/vallor/eligibility/vallor-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Vallor's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Contract Management
- Contract Lifecycle Management
- Procurement
- Legal
- Sales
- Artificial Intelligence
- AI Agents
---
