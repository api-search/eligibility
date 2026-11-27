---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be legally able to enter this agreement in your jurisdiction.
    type: individual
  - text: If you use Media2URL for a company or another organization, you confirm that you have authority to accept these Terms for that organization.
    type: business
  minimum_age:
    text: You must meet the minimum age required by the law that applies to you
    value: null
  restricted_uses:
  - summary: Regulated or sensitive records
    text: upload regulated or highly sensitive records without a lawful and suitable purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require additional verification or limit functionality when account activity presents security, fraud, spam, or operational risk.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Media2URL Direct Media Delivery API
provenance_date: '2026-11-10'
provider_name: Media2URL Direct Media Delivery API
provider_slug: media2url
slug: media2url-eligibility
source_date: '2026-11-10'
source_filename: media2url-eligibility.yml
source_heading: Eligibility
source_page: https://media2url.info/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Media2URL Direct Media Delivery API\naid: media2url\nurl: https://media2url.info/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be legally able to enter this agreement in your jurisdiction.\n- type: business\n  text: If you use Media2URL for a company or another organization, you confirm that you have authority to accept\n    these Terms for that organization.\nrestricted_uses:\n- summary: Regulated or sensitive records\n  text: upload regulated or highly sensitive records without a lawful and suitable purpose\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require additional verification or limit functionality when account activity presents security, fraud,\n    spam, or operational risk.\nminimum_age:\n  value: null\n  text: You must meet the minimum age required by the law that applies to you\n"
source_yaml_url: https://artifacts.apis.io/media2url/eligibility/media2url-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Media2URL Direct Media Delivery API's own page on 2026-11-10.
synthetic: false
tags:
- Media
- File Hosting
- Direct Links
- Upload
---
