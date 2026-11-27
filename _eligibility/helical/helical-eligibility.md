---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Customer warrants that neither it nor any Authorised User is a sanctioned person or located in a comprehensively sanctioned territory, and the Customer shall not permit access to the Services from any such territory.
  entity_types:
  - text: The Customer confirms that it is a business and not a consumer.
    type: business
  minimum_age:
    text: Each Authorised User must be at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Not a medical device / no clinical use
    text: The Services are not a medical device and are not intended for use in clinical diagnosis, treatment decisions or patient care.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Accredited academic and non-profit research institutions may apply for free or discounted credits through the verification process described in the Documentation.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Helical
provenance_date: '2026-11-09'
provider_name: Helical
provider_slug: helical
slug: helical-eligibility
source_date: '2026-11-09'
source_filename: helical-eligibility.yml
source_heading: Eligibility
source_page: https://www.helical.bio/plugin/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Helical\naid: helical\nurl: https://www.helical.bio/plugin/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Customer warrants that neither it nor any Authorised User is a sanctioned person or located in a comprehensively\n    sanctioned territory, and the Customer shall not permit access to the Services from any such territory.\nentity_types:\n- type: business\n  text: The Customer confirms that it is a business and not a consumer.\nrestricted_uses:\n- summary: Not a medical device / no clinical use\n  text: The Services are not a medical device and are not intended for\
  \ use in clinical diagnosis, treatment decisions\n    or patient care.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Accredited academic and non-profit research institutions may apply for free or discounted credits through\n    the verification process described in the Documentation.\nminimum_age:\n  value: '18'\n  text: Each Authorised User must be at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/helical/eligibility/helical-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Helical's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Artificial Intelligence
- Drug Discovery
- Bioinformatics
- Platform
---
