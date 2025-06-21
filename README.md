# offensive-ai

![](https://img.shields.io/badge/last--updated-December%202021%20-green) ![](https://img.shields.io/badge/src-public-orange)

[Rolling 2 day view of updates from this repo](https://github.com/timb-machine/offensive-ai/compare/master@%7B2day%7D...master)

## YARA rules

Running the rules:

* ```yara -r yara/personal-malware-bazaar/dependsonpythonailib.yara /path/to/check```

### Personal

* dependsonpythonailib.yara - Hunts for references to Python AI libraries
