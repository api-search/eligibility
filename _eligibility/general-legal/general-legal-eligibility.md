---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are intended solely for users located in the United States.
  entity_types:
  - text: If you are an individual, you may not access or use the Site or any Services or accept the Terms if you are not at least 18 years old.
    type: individual
  - text: If you are creating an Account on behalf of an entity, you represent and warrant that you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: If you are an individual, you may not access or use the Site or any Services or accept the Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No account use for AI training or evaluation without consent
    text: or training or evaluating any artificial intelligence system, in each case without General Legal’s prior written consent.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: An attorney-client relationship is formed only if and when General Legal has completed its conflict of interest review and has confirmed its acceptance of the representation in writing
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: General Legal
provenance_date: '2026-11-09'
provider_name: General Legal
provider_slug: general-legal
slug: general-legal-eligibility
source_date: '2026-11-09'
source_filename: general-legal-eligibility.yml
source_heading: Eligibility
source_page: https://general.legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: General Legal\naid: general-legal\nurl: https://general.legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are intended solely for users located in the United States.\nentity_types:\n- type: individual\n  text: If you are an individual, you may not access or use the Site or any Services or accept the Terms if you\n    are not at least 18 years old.\n- type: business\n  text: If you are creating an Account on behalf of an entity, you represent and warrant that you have the authority\n    to bind that entity to these Terms\n\
  restricted_uses:\n- summary: No account use for AI training or evaluation without consent\n  text: or training or evaluating any artificial intelligence system, in each case without General Legal’s prior\n    written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: An attorney-client relationship is formed only if and when General Legal has completed its conflict of interest\n    review and has confirmed its acceptance of the representation in writing\nminimum_age:\n  value: '18'\n  text: If you are an individual, you may not access or use the Site or any Services or accept the Terms if you\n    are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/general-legal/eligibility/general-legal-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from General Legal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Law Firms
- Legal Tech
- Contracts
- Contract Review
- Compliance
- Artificial Intelligence
- Startups
- Y Combinator
---
