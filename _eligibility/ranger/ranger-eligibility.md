---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use of the Site is unauthorized in any jurisdiction that does not give effect to all provisions of these Terms.
  entity_types:
  - text: If you are under 18, you may use https://ranger.net only with permission of a parent or guardian.
    type: individual
  minimum_age:
    text: Ranger does not knowingly collect, either online or offline, personal information from persons under the age of thirteen. If you are under 18, you may use https://ranger.net only with permission of a parent or guardian.
    value: '13'
  restricted_uses:
  - summary: Unlawful use
    text: you will not use the Site for any purpose that is unlawful or prohibited by these Terms.
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
name: Ranger
provenance_date: '2026-11-10'
provider_name: Ranger
provider_slug: ranger
slug: ranger-eligibility
source_date: '2026-11-10'
source_filename: ranger-eligibility.yml
source_heading: Eligibility
source_page: https://www.ranger.net/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ranger\naid: ranger\nurl: https://www.ranger.net/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use of the Site is unauthorized in any jurisdiction that does not give effect to all provisions of these\n    Terms.\nentity_types:\n- type: individual\n  text: If you are under 18, you may use https://ranger.net only with permission of a parent or guardian.\nrestricted_uses:\n- summary: Unlawful use\n  text: you will not use the Site for any purpose that is unlawful or prohibited by these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '13'\n  text: Ranger does not knowingly collect, either online or offline, personal information from persons under the\n    age of thirteen. If you are under 18, you may use https://ranger.net only with permission of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/ranger/eligibility/ranger-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ranger's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Quality Assurance
- Testing
- Browser Automation
- Artificial Intelligence
- Agents
- Developer Tools
- DevOps
- CLI
---
