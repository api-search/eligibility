---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you are at least the age of majority in your jurisdiction and have the legal capacity to enter into these Terms.
    type: individual
  - text: If you use the Service on behalf of an organization, you represent that you have authority to bind that organization
    type: business
  - text: If you are a U.S. government entity, the Service is provided as “commercial computer software”
    type: government
  minimum_age:
    text: You represent that you are at least the age of majority in your jurisdiction
    value: age of majority
  restricted_uses:
  - summary: No competitive product build
    text: Access or use the Service to build a competitive product or service, or copy features or functionality;
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
name: Nebula Security
provenance_date: '2026-11-10'
provider_name: Nebula Security
provider_slug: nebula-security
slug: nebula-security-eligibility
source_date: '2026-11-10'
source_filename: nebula-security-eligibility.yml
source_heading: Eligibility
source_page: https://nebusec.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nebula Security\naid: nebula-security\nurl: https://nebusec.ai/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent that you are at least the age of majority in your jurisdiction and have the legal capacity\n    to enter into these Terms.\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you have authority to bind that\n    organization\n- type: government\n  text: If you are a U.S. government entity, the Service is provided as “commercial computer software”\nrestricted_uses:\n\
  - summary: No competitive product build\n  text: Access or use the Service to build a competitive product or service, or copy features or functionality;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You represent that you are at least the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/nebula-security/eligibility/nebula-security-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Nebula Security's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Vulnerability Management
- Application Security
- Code Scanning
- Artificial Intelligence
- Developer Tools
- CLI
---
