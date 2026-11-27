---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in, organized under the laws of, or ordinarily resident in a country or territory subject to comprehensive sanctions, and that you are not listed on any prohibited or restricted party list.
  entity_types:
  - text: You must be at least 18 years old and legally able to enter into a contract to use the Services.
    type: individual
  - text: If you are using the Services on behalf of a company, organization, or other legal entity, you represent that you have authority to bind that entity.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into a contract to use the Services.
    value: '18'
  restricted_uses:
  - summary: High-risk decisions
    text: You may not use the Services as the sole basis for emergency decisions, safety-critical decisions, medical diagnosis or treatment, legal determinations, financial decisions, employment decisions, eligibility decisions, housing decisions, credit decisions, insurance decisions, or other high-impact decisions without appropriate human review, validation, safeguards, and legal compliance.
  - summary: Regulated data
    text: Use involving protected health information, sensitive personal information, biometric information, children’s information, or similarly regulated data may require additional written terms with Soniox before such use is permitted.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Soniox may require payment information, identity verification, or additional approval to increase usage, capacity, quotas, or access.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Soniox
provenance_date: '2026-11-10'
provider_name: Soniox
provider_slug: soniox
slug: soniox-eligibility
source_date: '2026-11-10'
source_filename: soniox-eligibility.yml
source_heading: Eligibility
source_page: https://soniox.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Soniox\naid: soniox\nurl: https://soniox.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in, organized under the laws of, or ordinarily resident in a country\n    or territory subject to comprehensive sanctions, and that you are not listed on any prohibited or restricted\n    party list.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter into a contract to use the Services.\n- type: business\n  text: If you are using the Services on behalf of a company, organization,\
  \ or other legal entity, you represent\n    that you have authority to bind that entity.\nrestricted_uses:\n- summary: High-risk decisions\n  text: You may not use the Services as the sole basis for emergency decisions, safety-critical decisions, medical\n    diagnosis or treatment, legal determinations, financial decisions, employment decisions, eligibility decisions,\n    housing decisions, credit decisions, insurance decisions, or other high-impact decisions without appropriate\n    human review, validation, safeguards, and legal compliance.\n- summary: Regulated data\n  text: Use involving protected health information, sensitive personal information, biometric information, children’s\n    information, or similarly regulated data may require additional written terms with Soniox before such use is\n    permitted.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Soniox may require payment information, identity verification, or additional approval to increase\
  \ usage,\n    capacity, quotas, or access.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into a contract to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/soniox/eligibility/soniox-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Soniox's own page on 2026-11-10.
synthetic: false
tags:
- Speech AI
- Multilingual
- Real-Time
- Streaming
---
