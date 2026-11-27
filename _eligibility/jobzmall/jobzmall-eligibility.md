---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: p) post jobs located in countries subject to economic sanctions of the United States Government
  entity_types:
  - text: You must be at least 13 years old (or, outside of the United States, the applicable legal age to enter into a contract) to use our Site.
    type: individual
  - text: If you are accepting these Terms and using the Services on behalf of an institution, company, organization, government, or other legal entity (individually or collectively, an “Institution”), then (a) “you” includes you and that Institution
    type: business
  minimum_age:
    text: You must be at least 13 years old (or, outside of the United States, the applicable legal age to enter into a contract) to use our Site.
    value: '13'
  restricted_uses:
  - summary: No employment-eligibility determinations on profiles
    text: '(d) with respect to Profiles, determine a consumer''s eligibility for: (i) credit or insurance for person, family, or household purposes; (ii) employment; or (iii) a government license of benefit.'
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
name: JobzMall
provenance_date: '2026-11-09'
provider_name: JobzMall
provider_slug: jobzmall
slug: jobzmall-eligibility
source_date: '2026-11-09'
source_filename: jobzmall-eligibility.yml
source_heading: Eligibility
source_page: https://app.jobzmall.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: JobzMall\naid: jobzmall\nurl: https://app.jobzmall.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: p) post jobs located in countries subject to economic sanctions of the United States Government\nentity_types:\n- type: individual\n  text: You must be at least 13 years old (or, outside of the United States, the applicable legal age to enter into\n    a contract) to use our Site.\n- type: business\n  text: If you are accepting these Terms and using the Services on behalf of an institution, company, organization,\n    government, or other legal entity\
  \ (individually or collectively, an “Institution”), then (a) “you” includes\n    you and that Institution\nrestricted_uses:\n- summary: No employment-eligibility determinations on profiles\n  text: '(d) with respect to Profiles, determine a consumer''s eligibility for: (i) credit or insurance for person,\n    family, or household purposes; (ii) employment; or (iii) a government license of benefit.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old (or, outside of the United States, the applicable legal age to enter into\n    a contract) to use our Site.\n"
source_yaml_url: https://artifacts.apis.io/jobzmall/eligibility/jobzmall-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from JobzMall's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video
- Talent
- Marketplace
- Hiring
- Resume
---
