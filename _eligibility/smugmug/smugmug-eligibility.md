---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you access the Services on behalf of a company or other entity, you warrant that you are an authorized representative of such company or entity with the right to bind such company or entity to these Terms of Use.
    type: business
  minimum_age:
    text: The Services are not targeted towards, nor intended for use by, anyone under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful user content
    text: User Content that is unlawful, harmful, threatening, abusive, harassing, tortious, defamatory, vulgar, obscene, libelous, invasive of another's privacy, hateful, or racially, ethnically or otherwise objectionable;
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
name: SmugMug
provenance_date: '2026-11-10'
provider_name: SmugMug
provider_slug: smugmug
slug: smugmug-eligibility
source_date: '2026-11-10'
source_filename: smugmug-eligibility.yml
source_heading: Eligibility
source_page: https://www.smugmug.com/about/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SmugMug\naid: smugmug\nurl: https://www.smugmug.com/about/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you access the Services on behalf of a company or other entity, you warrant that you are an authorized\n    representative of such company or entity with the right to bind such company or entity to these Terms of Use.\nrestricted_uses:\n- summary: Unlawful or harmful user content\n  text: User Content that is unlawful, harmful, threatening, abusive, harassing, tortious, defamatory, vulgar, obscene,\n \
  \   libelous, invasive of another's privacy, hateful, or racially, ethnically or otherwise objectionable;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are not targeted towards, nor intended for use by, anyone under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/smugmug/eligibility/smugmug-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from SmugMug's own page on 2026-11-10.
synthetic: false
tags:
- Photography
- Photo Sharing
- E-Commerce
- Cloud Storage
- Software-as-a-Service
---
