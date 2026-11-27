---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you act for an organization, you represent that you are authorized to bind it.
    type: business
  - text: If you use a Service on behalf of a business, to the extent permitted by law, that business will indemnify ShuttleAI against third-party claims and reasonable resulting costs arising from its unlawful use, infringement by content it supplies, or material breach of these Terms.
    type: business
  minimum_age:
    text: AI accounts, paid services, and developer accounts are not offered to children under 13; a product or platform may require a higher age.
    value: '13'
  restricted_uses:
  - summary: Children under 13
    text: AI accounts, paid services, and developer accounts are not offered to children under 13; a product or platform may require a higher age.
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
name: ShuttleAI
provenance_date: '2026-11-10'
provider_name: ShuttleAI
provider_slug: shuttleai
slug: shuttleai-eligibility
source_date: '2026-11-10'
source_filename: shuttleai-eligibility.yml
source_heading: Eligibility
source_page: https://shuttleai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ShuttleAI\naid: shuttleai\nurl: https://shuttleai.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you act for an organization, you represent that you are authorized to bind it.\n- type: business\n  text: If you use a Service on behalf of a business, to the extent permitted by law, that business will indemnify\n    ShuttleAI against third-party claims and reasonable resulting costs arising from its unlawful use, infringement\n    by content it supplies, or material breach of these Terms.\nrestricted_uses:\n- summary: Children\
  \ under 13\n  text: AI accounts, paid services, and developer accounts are not offered to children under 13; a product or platform\n    may require a higher age.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: AI accounts, paid services, and developer accounts are not offered to children under 13; a product or platform\n    may require a higher age.\n"
source_yaml_url: https://artifacts.apis.io/shuttleai/eligibility/shuttleai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ShuttleAI's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Infrastructure
- Developer Tools
- Product
- Company
---
