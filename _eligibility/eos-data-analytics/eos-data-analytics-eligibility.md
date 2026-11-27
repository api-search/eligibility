---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You warrant that you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a "terrorist supporting" country
  entity_types:
  - text: In instances when you represent an entity or organization in this agreement, you thus warrant and assert that you have been authorized to agree to the provided Terms
    type: business
  minimum_age:
    text: The Services are not aimed at anyone under the age of 18 years
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful activity
    text: in any way that violates, or has the potential to violate, any local, state, national, foreign, or international statute, regulation, rule, order, treaty, or other law
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: we do not conduct any criminal or other identity checks on any visitors or Services users
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: EOS Data Analytics
provenance_date: '2026-11-09'
provider_name: EOS Data Analytics
provider_slug: eos-data-analytics
slug: eos-data-analytics-eligibility
source_date: '2026-11-09'
source_filename: eos-data-analytics-eligibility.yml
source_heading: Eligibility
source_page: https://eos.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EOS Data Analytics\naid: eos-data-analytics\nurl: https://eos.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You warrant that you are not located in a country that is subject to a U.S. Government embargo, or that\n    has been designated by the U.S. Government as a \"terrorist supporting\" country\nentity_types:\n- type: business\n  text: In instances when you represent an entity or organization in this agreement, you thus warrant and assert\n    that you have been authorized to agree to the provided Terms\nrestricted_uses:\n- summary: Unlawful or harmful activity\n\
  \  text: in any way that violates, or has the potential to violate, any local, state, national, foreign, or international\n    statute, regulation, rule, order, treaty, or other law\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: we do not conduct any criminal or other identity checks on any visitors or Services users\nminimum_age:\n  value: '18'\n  text: The Services are not aimed at anyone under the age of 18 years\n"
source_yaml_url: https://artifacts.apis.io/eos-data-analytics/eligibility/eos-data-analytics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from EOS Data Analytics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Satellite
- Analytics
- Agriculture
- Environmental
---
