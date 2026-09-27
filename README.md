# CASIA Palmprint

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FCASIA--Palmprint-181717?logo=github)](https://github.com/biometric-community/CASIA-Palmprint)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](http://www.cbsr.ia.ac.cn/english/PalmprintDatabases.asp)

**CASIA Palmprint** — tbiom catalog packaging for `casia-palmprint` (palm-knuckle; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/CASIA-Palmprint
- **Upstream source**: http://www.cbsr.ia.ac.cn/english/PalmprintDatabases.asp
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `casia-palmprint` |
| Category | `palm-knuckle` |
| Access | `register` |
| Upstream homepage | http://www.cbsr.ia.ac.cn/english/PalmprintDatabases.asp |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: CASIA palmprint.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/CASIA-Palmprint.git
cd CASIA-Palmprint
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_casia_palmprint.sh
```

Place licensed archives under `projects/datasets/casia-palmprint/` (gitignored).

## Dataset structure

```text
CASIA-Palmprint/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: http://www.cbsr.ia.ac.cn/english/PalmprintDatabases.asp
- Packaging: https://github.com/biometric-community/CASIA-Palmprint/issues
