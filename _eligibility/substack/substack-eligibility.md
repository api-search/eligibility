---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are of legal age to form a binding contract.
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization or entity’s behalf and bind them to these Terms
    type: business
  minimum_age:
    text: As detailed further below, you may not and must not use Substack if you are under 16 years old.
    value: '16'
  restricted_uses:
  - summary: Political contributions
    text: Reader is a natural person who is at least 18 years of age and a U.S. citizen or lawful permanent resident residing in the U.S. (i.e., green card holder).
  - source: https://substack.com/api-tos
    summary: Surveillance, profiling, or targeting
    text: Aggregate Authorized Data in a manner that enables surveillance, profiling, or behavioral targeting of creators
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
name: Substack
provenance_date: '2026-11-10'
provider_name: Substack
provider_slug: substack
slug: substack-eligibility
source_date: '2026-11-10'
source_filename: substack-eligibility.yml
source_heading: Eligibility
source_page: https://substack.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Substack\naid: substack\nurl: https://substack.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://substack.com/api-tos\n  - https://substack.com/tos\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are of legal age to form a binding contract.\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization or entity’s behalf and bind them to these Terms\nrestricted_uses:\n- summary:\
  \ Political contributions\n  text: Reader is a natural person who is at least 18 years of age and a U.S. citizen or lawful permanent resident\n    residing in the U.S. (i.e., green card holder).\n- summary: Surveillance, profiling, or targeting\n  text: Aggregate Authorized Data in a manner that enables surveillance, profiling, or behavioral targeting of creators\n  source: https://substack.com/api-tos\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: As detailed further below, you may not and must not use Substack if you are under 16 years old.\n"
source_yaml_url: https://artifacts.apis.io/substack/eligibility/substack-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Substack's own page on 2026-11-10.
synthetic: false
tags:
- Newsletters
- Publishing
- Creator Economy
- Subscription
- Email
- Podcasts
- Notes
- Media
- Independent Media
- Paid Content
- MCP
- Agents
- RSS
- Analytics
---
