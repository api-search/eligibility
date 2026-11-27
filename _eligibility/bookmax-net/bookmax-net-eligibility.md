---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use BOOKMAX.NET as a consumer, nothing in these Terms limits or excludes any mandatory rights you have under applicable consumer protection law.
    type: individual
  - text: If an account is used on behalf of a company or other organization, the organization may determine how the account and its data are administered, subject to the agreement between the organization and the relevant user.
    type: business
  minimum_age:
    text: You must be at least 13 years old to use BOOKMAX.NET.
    value: '13'
  restricted_uses:
  - summary: Unlawful or infringing content
    text: You must not use BOOKMAX.NET to store or distribute content that is unlawful, fraudulent, malicious, defamatory, threatening, or that infringes intellectual property, privacy or other rights of third parties.
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
name: Bookmax
provenance_date: '2026-11-09'
provider_name: Bookmax
provider_slug: bookmax-net
slug: bookmax-net-eligibility
source_date: '2026-11-09'
source_filename: bookmax-net-eligibility.yml
source_heading: Eligibility
source_page: https://www.bookmax.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bookmax\naid: bookmax-net\nurl: https://www.bookmax.net/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you use BOOKMAX.NET as a consumer, nothing in these Terms limits or excludes any mandatory rights you\n    have under applicable consumer protection law.\n- type: business\n  text: If an account is used on behalf of a company or other organization, the organization may determine how the\n    account and its data are administered, subject to the agreement between the organization and the relevant user.\nrestricted_uses:\n\
  - summary: Unlawful or infringing content\n  text: You must not use BOOKMAX.NET to store or distribute content that is unlawful, fraudulent, malicious, defamatory,\n    threatening, or that infringes intellectual property, privacy or other rights of third parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use BOOKMAX.NET.\n"
source_yaml_url: https://artifacts.apis.io/bookmax-net/eligibility/bookmax-net-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Bookmax's own page on 2026-11-09.
synthetic: false
tags:
- Bookmark
- OnlineService
- Austria
- Free
- Premium
---
