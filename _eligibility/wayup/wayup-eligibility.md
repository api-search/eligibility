---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: if you are not a legal resident of the United States, you are not granted permission to use our Services and must exit immediately
  entity_types:
  - text: current and former students at particular educational institutions seeking employment opportunities or contracting opportunities (each, a “Student”)
    type: individual
  - text: providers of such employment or contracting opportunities (each, a “Business”)
    type: business
  minimum_age:
    text: By registering an account on our Services, you represent that you are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: (a) any illegal or unauthorized purposes that violate any local, national, or international laws
  - summary: Unlawful discrimination by Businesses
    text: it may not use our Services to unlawfully discriminate against any Student
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: WayUp reserves the right to verify these representations and warranties, WayUp is not obligated to do so, and may choose not to do so, at WayUp’s sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: wayup
provenance_date: '2026-11-10'
provider_name: wayup
provider_slug: wayup
slug: wayup-eligibility
source_date: '2026-11-10'
source_filename: wayup-eligibility.yml
source_heading: Eligibility
source_page: https://www.wayup.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: wayup\naid: wayup\nurl: https://www.wayup.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: if you are not a legal resident of the United States, you are not granted permission to use our Services\n    and must exit immediately\nentity_types:\n- type: individual\n  text: current and former students at particular educational institutions seeking employment opportunities or contracting\n    opportunities (each, a “Student”)\n- type: business\n  text: providers of such employment or contracting opportunities (each, a “Business”)\nrestricted_uses:\n- summary: Illegal or unauthorized\
  \ purposes\n  text: (a) any illegal or unauthorized purposes that violate any local, national, or international laws\n- summary: Unlawful discrimination by Businesses\n  text: it may not use our Services to unlawfully discriminate against any Student\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: WayUp reserves the right to verify these representations and warranties, WayUp is not obligated to do so,\n    and may choose not to do so, at WayUp’s sole discretion.\nminimum_age:\n  value: '18'\n  text: By registering an account on our Services, you represent that you are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/wayup/eligibility/wayup-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from wayup's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Job
- Recruiting
- Early Career
- Internships
- Careers
- Talent Acquisition
---
