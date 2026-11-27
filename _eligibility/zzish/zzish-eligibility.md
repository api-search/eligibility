---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using Quizalize on behalf of a school, district, or other organization, you confirm that you have authority to accept these Terms for that organization.
    type: business
  - text: Teachers and school staff must provide accurate account information and keep their sign-in details secure.
    type: individual
  minimum_age:
    text: Children under 13, or under the applicable age of digital consent in their country, may only use Quizalize with appropriate school, parent, or guardian consent.
    value: '13'
  restricted_uses:
  - summary: Unlawful or abusive use
    text: 'You must not use Quizalize to: break any law or violate the rights of another person; upload harmful, abusive, discriminatory, or misleading content'
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
name: Zzish
provenance_date: '2026-11-10'
provider_name: Zzish
provider_slug: zzish
slug: zzish-eligibility
source_date: '2026-11-10'
source_filename: zzish-eligibility.yml
source_heading: Eligibility
source_page: https://www.quizalize.com/terms-of-service?lang=en-US
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zzish\naid: zzish\nurl: https://www.quizalize.com/terms-of-service?lang=en-US\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using Quizalize on behalf of a school, district, or other organization, you confirm that you\n    have authority to accept these Terms for that organization.\n- type: individual\n  text: Teachers and school staff must provide accurate account information and keep their sign-in details secure.\nrestricted_uses:\n- summary: Unlawful or abusive use\n  text: 'You must not use Quizalize to: break any law\
  \ or violate the rights of another person; upload harmful, abusive,\n    discriminatory, or misleading content'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Children under 13, or under the applicable age of digital consent in their country, may only use Quizalize\n    with appropriate school, parent, or guardian consent.\n"
source_yaml_url: https://artifacts.apis.io/zzish/eligibility/zzish-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Zzish's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- EdTech
- K-12
- Assessment
- Quizzes
- Learning
- AI Tutoring
---
