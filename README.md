# TAKT — Dental Landing Design

Desktop/mobile header and hero concept for a dental-clinic test assignment.

[Open gallery](https://memorim.github.io/takt-dental-landing-design/)

![Desktop composition](assets/01-desktop.png)

<img src="assets/01-mobile.png" width="320" alt="Mobile composition">

## Implementation

Static HTML/CSS gallery, image assets and design exports. The gallery can be served directly; no application build or secret configuration is needed. Desktop and mobile compositions are separate assets.

## Local setup and checks

```bash
python tests/check_assets.py
python .github/scripts/check_docs.py
python -m http.server 8080 --bind 127.0.0.1
```

Use Python 3.12.14, matching CI. Open `http://localhost:8080`. CI checks asset references and documentation; it does not certify interactive behavior inside images.

## Scope and limits

A design test assignment, not an operating clinic site or appointment backend.

No database, migrations or API are required for this static scope. Forms or integrations would be a separate implementation task.

[Technical details](docs/TECHNICAL.md) · [Recorded checks](docs/VERIFICATION.md) · [Change history](CHANGELOG.md)
