---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and able to form a binding contract.
    type: individual
  - text: If you use BacklinkGenie on behalf of a company, you agree on its behalf.
    type: business
  minimum_age:
    text: You must be at least 18 and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Restricted site categories
    text: We do not provide the service to sites in these categories, and every site is reviewed at signup and periodically afterwards
  - summary: Regulated areas need manual review
    text: Sites in some regulated areas (for example health, finance, legal and political content) may require manual review before outreach begins.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: every site is reviewed at signup and periodically afterwards
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BacklinkGenie
provenance_date: '2026-11-09'
provider_name: BacklinkGenie
provider_slug: backlinkgenie-com
slug: backlinkgenie-com-eligibility
source_date: '2026-11-09'
source_filename: backlinkgenie-com-eligibility.yml
source_heading: Eligibility
source_page: https://backlinkgenie.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BacklinkGenie\naid: backlinkgenie-com\nurl: https://backlinkgenie.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and able to form a binding contract.\n- type: business\n  text: If you use BacklinkGenie on behalf of a company, you agree on its behalf.\nrestricted_uses:\n- summary: Restricted site categories\n  text: We do not provide the service to sites in these categories, and every site is reviewed at signup and periodically\n    afterwards\n- summary: Regulated areas need manual review\n  text:\
  \ Sites in some regulated areas (for example health, finance, legal and political content) may require manual\n    review before outreach begins.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: every site is reviewed at signup and periodically afterwards\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/backlinkgenie-com/eligibility/backlinkgenie-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from BacklinkGenie's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- SEO
- Link Building
- Marketing
- Automation
---
