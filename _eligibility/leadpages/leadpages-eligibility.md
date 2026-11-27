---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: provided that you are of legal age to form a binding contract in your applicable jurisdiction
    type: individual
  - text: 'If you create a Leadpages Account on behalf of a company, organization, or other entity, then: (a) “you” includes you and that entity'
    type: business
  minimum_age:
    text: Any use or access of the Site and/or any Services by Users under the age of thirteen (13), or such minimum age as required under applicable law, is strictly prohibited and in violation of this Agreement.
    value: thirteen (13)
  restricted_uses:
  - summary: Spam and unsolicited messaging
    text: use the Services to engage in spamming, “chain letters,” “pyramid schemes,” advertisement of illegal or controlled products or services
  - summary: Competitors
    text: access the Site and/or Services if you are a direct competitor of Leadpages, except with Leadpages’ prior written consent, or for any other competitive purposes
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
name: Leadpages
provenance_date: '2026-11-09'
provider_name: Leadpages
provider_slug: leadpages
slug: leadpages-eligibility
source_date: '2026-11-09'
source_filename: leadpages-eligibility.yml
source_heading: Eligibility
source_page: https://leadpages.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Leadpages\naid: leadpages\nurl: https://leadpages.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: provided that you are of legal age to form a binding contract in your applicable jurisdiction\n- type: business\n  text: 'If you create a Leadpages Account on behalf of a company, organization, or other entity, then: (a) “you”\n    includes you and that entity'\nrestricted_uses:\n- summary: Spam and unsolicited messaging\n  text: use the Services to engage in spamming, “chain letters,” “pyramid schemes,”\
  \ advertisement of illegal or\n    controlled products or services\n- summary: Competitors\n  text: access the Site and/or Services if you are a direct competitor of Leadpages, except with Leadpages’ prior\n    written consent, or for any other competitive purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: thirteen (13)\n  text: Any use or access of the Site and/or any Services by Users under the age of thirteen (13), or such minimum\n    age as required under applicable law, is strictly prohibited and in violation of this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/leadpages/eligibility/leadpages-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Leadpages's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Landing Pages
- Marketing
- Conversion Optimization
- A/B Testing
- Website Builder
- Lead Generation
- Content Management
- Agents
- Analytics
- A2A
---
