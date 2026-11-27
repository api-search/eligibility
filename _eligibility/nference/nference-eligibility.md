---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF THE INDIVIDUAL ENTERING INTO THIS AGREEMENT IS DOING SO ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, SUCH INDIVIDUAL REPRESENTS THAT HE OR SHE HAS THE REQUISITE AUTHORITY TO BIND SUCH ENTITY
    type: business
  minimum_age:
    text: The Sites are not for persons under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: As a condition of your use of the Site, you will not use the Site for any purpose that is unlawful or prohibited by this Agreement.
  - summary: False or misleading accounts
    text: you agree not to use false or misleading information in connection with your user account and acknowledge that we reserve the right to disable any user account with a profile which we believe (in our sole discretion) is false or misleading
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
name: nference
provenance_date: '2026-11-10'
provider_name: nference
provider_slug: nference
slug: nference-eligibility
source_date: '2026-11-10'
source_filename: nference-eligibility.yml
source_heading: Eligibility
source_page: https://nference.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: nference\naid: nference\nurl: https://nference.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF THE INDIVIDUAL ENTERING INTO THIS AGREEMENT IS DOING SO ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY,\n    SUCH INDIVIDUAL REPRESENTS THAT HE OR SHE HAS THE REQUISITE AUTHORITY TO BIND SUCH ENTITY\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: As a condition of your use of the Site, you will not use the Site for any purpose that is unlawful or prohibited\n    by this Agreement.\n- summary: False or misleading\
  \ accounts\n  text: you agree not to use false or misleading information in connection with your user account and acknowledge\n    that we reserve the right to disable any user account with a profile which we believe (in our sole discretion)\n    is false or misleading\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Sites are not for persons under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/nference/eligibility/nference-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from nference's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health Tech
- Artificial Intelligence
- Clinical Research
- Life Sciences
- Medical Imaging
- Data Science
- Biomarkers
---
