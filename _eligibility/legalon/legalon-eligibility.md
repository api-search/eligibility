---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Website is provided for use by persons in the United States only.
  entity_types:
  - text: the individual, company, or legal entity using the LegalOn Services
    type: business
  - text: IF YOU ARE AN INDIVIDUAL ACCESSING OR USING THE SERVICES ON BEHALF OF A LEGAL ENTITY, YOU HEREBY AGREE TO THESE TERMS ON BEHALF OF SUCH LEGAL ENTITY
    type: individual
  minimum_age:
    text: This Website is intended for users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: High-risk activities
    text: for high-risk activities (life support, critical infrastructure)
  - summary: Use outside attorney supervision
    text: Customer represents and warrants that its users of the Services will be attorneys or people working under the supervision of an attorney.
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
name: LegalOn
provenance_date: '2026-11-09'
provider_name: LegalOn
provider_slug: legalon
slug: legalon-eligibility
source_date: '2026-11-09'
source_filename: legalon-eligibility.yml
source_heading: Eligibility
source_page: https://www.legalontech.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LegalOn\naid: legalon\nurl: https://www.legalontech.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Website is provided for use by persons in the United States only.\nentity_types:\n- type: business\n  text: the individual, company, or legal entity using the LegalOn Services\n- type: individual\n  text: IF YOU ARE AN INDIVIDUAL ACCESSING OR USING THE SERVICES ON BEHALF OF A LEGAL ENTITY, YOU HEREBY AGREE TO\n    THESE TERMS ON BEHALF OF SUCH LEGAL ENTITY\nrestricted_uses:\n- summary: High-risk activities\n  text: for high-risk\
  \ activities (life support, critical infrastructure)\n- summary: Use outside attorney supervision\n  text: Customer represents and warrants that its users of the Services will be attorneys or people working under\n    the supervision of an attorney.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Website is intended for users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/legalon/eligibility/legalon-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from LegalOn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Technology
- Legal
- Legal Tech
- Contracts
- Contract Management
- Contract Lifecycle Management
- Artificial Intelligence
- Document Management
- Compliance
- Governance
- Software-as-a-Service
- Japan
---
