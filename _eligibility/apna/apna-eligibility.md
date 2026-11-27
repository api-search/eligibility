---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you represent an entity, organisation, or any other legal person (not being a natural person), you confirm that you are duly authorised by such entity or its management to accept these Terms
    type: business
  minimum_age:
    text: you are at least 18 (eighteen) years of age or older
    value: '18'
  restricted_uses:
  - summary: Unlawful, fraudulent or misleading content
    text: use the Platform in any unlawful manner or for any fraudulent, deceptive, or malicious activities
  - summary: Discriminatory practices
    text: not engage in any discriminatory practices prohibited by Applicable Law
  - summary: Candidate fees prohibited
    text: You shall not solicit or require from job applicants any form of financial commitment, fee, or deposit as a condition of application or selection
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Job Posts are subject to Apna approval and may be rejected without cause.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Apna
provenance_date: '2026-11-09'
provider_name: Apna
provider_slug: apna
slug: apna-eligibility
source_date: '2026-11-09'
source_filename: apna-eligibility.yml
source_heading: Eligibility
source_page: https://apna.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apna\naid: apna\nurl: https://apna.co/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you represent an entity, organisation, or any other legal person (not being a natural person), you confirm\n    that you are duly authorised by such entity or its management to accept these Terms\nrestricted_uses:\n- summary: Unlawful, fraudulent or misleading content\n  text: use the Platform in any unlawful manner or for any fraudulent, deceptive, or malicious activities\n- summary: Discriminatory practices\n  text: not engage\
  \ in any discriminatory practices prohibited by Applicable Law\n- summary: Candidate fees prohibited\n  text: You shall not solicit or require from job applicants any form of financial commitment, fee, or deposit as\n    a condition of application or selection\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Job Posts are subject to Apna approval and may be rejected without cause.\nminimum_age:\n  value: '18'\n  text: you are at least 18 (eighteen) years of age or older\n"
source_yaml_url: https://artifacts.apis.io/apna/eligibility/apna-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Apna's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Job
- Recruiting
- Professional Networking
- Hiring
- Careers
- India
---
