---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for visitors located within the United States. We make no representation that the Site is appropriate or available for use outside of the United States.
  entity_types:
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Site.
    value: '18'
  restricted_uses:
  - summary: No real patient data or PHI in sandbox
    text: You may not input, upload, or process any real patient data or Protected Health Information (PHI) in the Sandbox environment.
  - summary: Clinical use requires signed agreements
    text: Production access to the Ultralight platform is permitted only upon full execution of a Master Subscription Agreement (MSA) and, if applicable, a Business Associate Agreement (BAA).
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Production access to the Ultralight platform is permitted only upon full execution of a Master Subscription Agreement (MSA) and, if applicable, a Business Associate Agreement (BAA).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ultralight
provenance_date: '2026-11-10'
provider_name: Ultralight
provider_slug: ultralight
slug: ultralight-eligibility
source_date: '2026-11-10'
source_filename: ultralight-eligibility.yml
source_heading: Eligibility
source_page: https://www.ultralighthealth.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ultralight\naid: ultralight\nurl: https://www.ultralighthealth.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for visitors located within the United States. We make no representation that the Site\n    is appropriate or available for use outside of the United States.\nentity_types:\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: No real patient data\
  \ or PHI in sandbox\n  text: You may not input, upload, or process any real patient data or Protected Health Information (PHI) in the\n    Sandbox environment.\n- summary: Clinical use requires signed agreements\n  text: Production access to the Ultralight platform is permitted only upon full execution of a Master Subscription\n    Agreement (MSA) and, if applicable, a Business Associate Agreement (BAA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Production access to the Ultralight platform is permitted only upon full execution of a Master Subscription\n    Agreement (MSA) and, if applicable, a Business Associate Agreement (BAA).\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/ultralight/eligibility/ultralight-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Ultralight's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Electronic Health Records
- Artificial Intelligence
- Functional Medicine
- Integrative Medicine
- Longevity Medicine
- Clinical Intelligence
- Patient Experience
---
