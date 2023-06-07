#hack-a-mae

This is used for the hackathon

* $ npx renovate
* update to the latest minor version, default behaviour
* https://docs.renovatebot.com/renovate-schema.json, default config for renovate.json

1. scan jar for the vulnerabilities to get bill_of_materials, update bill_of_materials.json i.e. packageName, current version and recommended version
2. update renovate.json according to the bill_of_materials
3. run npx renovate
4. create PR with updated version