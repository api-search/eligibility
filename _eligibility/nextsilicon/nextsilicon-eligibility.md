---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: make use of the Website in any jurisdiction where such use is illegal or which would subject Next Silicon or its affiliates to any registration requirement within such jurisdiction or country
  entity_types:
  - text: By accessing or using the Website for your own personal use, you confirm that (i) you can form a binding contract with Us under the applicable laws of your jurisdiction, and (ii) you are over the age of 18.
    type: individual
  - text: By accessing or using the Services on behalf of a corporation (or any other legal entity), you confirm that you are duly authorized by such legal entity to enter into an agreement on behalf of that legal entity
    type: business
  minimum_age:
    text: you are over the age of 18.
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful use
    text: use, or encourage, promote, facilitate, or instruct others to use the Website for any illegal, harmful, or offensive use
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The use of the Website, or any part thereof, may require you to open an account; you must complete the registration process by providing current, complete and accurate information as prompted by the applicable registration form.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: NextSilicon
provenance_date: '2026-11-10'
provider_name: NextSilicon
provider_slug: nextsilicon
slug: nextsilicon-eligibility
source_date: '2026-11-10'
source_filename: nextsilicon-eligibility.yml
source_heading: Eligibility
source_page: https://www.nextsilicon.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NextSilicon\naid: nextsilicon\nurl: https://www.nextsilicon.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: make use of the Website in any jurisdiction where such use is illegal or which would subject Next Silicon\n    or its affiliates to any registration requirement within such jurisdiction or country\nentity_types:\n- type: individual\n  text: By accessing or using the Website for your own personal use, you confirm that (i) you can form a binding\n    contract with Us under the applicable laws of your jurisdiction, and (ii) you are over the age of 18.\n- type:\
  \ business\n  text: By accessing or using the Services on behalf of a corporation (or any other legal entity), you confirm that\n    you are duly authorized by such legal entity to enter into an agreement on behalf of that legal entity\nrestricted_uses:\n- summary: Illegal or harmful use\n  text: use, or encourage, promote, facilitate, or instruct others to use the Website for any illegal, harmful,\n    or offensive use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The use of the Website, or any part thereof, may require you to open an account; you must complete the registration\n    process by providing current, complete and accurate information as prompted by the applicable registration form.\nminimum_age:\n  value: '18'\n  text: you are over the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/nextsilicon/eligibility/nextsilicon-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from NextSilicon's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Compute
- High Performance Computing
- Semiconductors
- Hardware
- Accelerator
- RISC-V
- Artificial Intelligence
---
