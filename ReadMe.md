RPMEnums.py [![Unlicensed work](https://raw.githubusercontent.com/unlicense/unlicense.org/master/static/favicon.png)](https://unlicense.org/)
============
~~[wheel (GitLab)](https://gitlab.com/prebuilder/RPMEnums.py/-/jobs/artifacts/master/raw/dist/RPMEnums-0.CI-py3-none-any.whl?job=build)~~
[wheel (GHA via `nightly.link`)](https://nightly.link/prebuilder/RPMEnums.py/workflows/CI/master/RPMEnums-0.CI-py3-none-any.whl)
~~![GitLab Build Status](https://gitlab.com/prebuilder/RPMEnums.py/badges/master/pipeline.svg)~~
~~![GitLab Coverage](https://gitlab.com/prebuilder/RPMEnums.py/badges/master/coverage.svg)~~
[![GitHub Actions](https://github.com/prebuilder/RPMEnums.py/workflows/CI/badge.svg)](https://github.com/prebuilder/RPMEnums.py/actions/)
[![Libraries.io Status](https://img.shields.io/librariesio/github/prebuilder/RPMEnums.py.svg)](https://libraries.io/github/prebuilder/RPMEnums.py)

Just pythonic access to RPM enums, like

```python
import RPMEnums
print(RPMEnums.RPMBuild.CHECK | RPMEnums.RPMBuild.CLEAN) # <RPMBuild.CLEAN|CHECK: 24>
print(RPMEnums.RPMBuild(24)) # <RPMBuild.CLEAN|CHECK: 24>
```
