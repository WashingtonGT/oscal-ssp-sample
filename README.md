# oscal-ssp-sample
Follow the example of ssp sample

~~~
trestle init

trestle import -f https://raw.githubusercontent.com/usnistgov/oscal-content/master/nist.gov/SP800-53/rev5/json/NIST_SP-800-53_rev5_catalog.json -o 800-53

trestle import -f https://raw.githubusercontent.com/usnistgov/oscal-content/master/nist.gov/SP800-53/rev5/json/NIST_SP-800-53_rev5_LOW-baseline_profile.json -o 800-53-low
~~~

## Generate catalog md doc
trestle author catalog-generate --name 800-53  --output md-800-53

### Reference

https://www.easydynamics.com/oscal/
https://d1.awsstatic.com/events/aws-reinforce-2022/GRC304_Automating-security-and-compliance-with-OSCAL%20-%20Copy.pdf
https://github.com/usnistgov/oscal-tools
https://d1.awsstatic.com/events/aws-reinforce-2022/GRC304_Automating-security-and-compliance-with-OSCAL%20-%20Copy.pdf
