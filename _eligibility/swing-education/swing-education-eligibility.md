---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: SwingSubs, who are teachers and related professionals working to provide teaching and tutoring services for Schools.
    type: individual
  - text: School administrators who use the Website to engage in the Platform & Services (for instance, in order to post teaching requests).
    type: other
  minimum_age:
    text: You represent that you are (1) at least eighteen (18) years old;
    value: '18'
  restricted_uses:
  - summary: Under-18 accounts prohibited
    text: Please note any individual under 18 (namely, students) may not have an account with Swing Education.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we may receive Personal and/or Anonymous Data about you from other sources, such as verification information and results from background checks from LiveScan or other third parties.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Swing Education
provenance_date: '2026-11-10'
provider_name: Swing Education
provider_slug: swing-education
slug: swing-education-eligibility
source_date: '2026-11-10'
source_filename: swing-education-eligibility.yml
source_heading: Eligibility
source_page: https://swingeducation.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Swing Education\naid: swing-education\nurl: https://swingeducation.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: SwingSubs, who are teachers and related professionals working to provide teaching and tutoring services\n    for Schools.\n- type: other\n  text: School administrators who use the Website to engage in the Platform & Services (for instance, in order to\n    post teaching requests).\nrestricted_uses:\n- summary: Under-18 accounts prohibited\n  text: Please note any individual under 18 (namely, students) may not\
  \ have an account with Swing Education.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: we may receive Personal and/or Anonymous Data about you from other sources, such as verification information\n    and results from background checks from LiveScan or other third parties.\nminimum_age:\n  value: '18'\n  text: You represent that you are (1) at least eighteen (18) years old;\n"
source_yaml_url: https://artifacts.apis.io/swing-education/eligibility/swing-education-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Swing Education's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- EdTech
- Staffing
- Substitute Teachers
- K-12
- Marketplace
- Workforce
---
