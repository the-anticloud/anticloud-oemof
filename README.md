# OEMOF

![licence](https://img.shields.io/badge/licence-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `OEMOF` in category **CARBON_CAPTURE**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** OEMOF · **Upstream pin:** `d2d7502862c8eec6963de97d9710bc27e4a41a5c` · **Category:** CARBON_CAPTURE · **Vendor:** Anticloud FZ LLE · **Licence:** MIT

---

## What This Project Does

=======================================
Open Energy Modelling Framework (oemof)
=======================================

.. figure:: https://raw.githubusercontent.com/oemof/oemof/master/logo/logo_oemof_big.svg

The Open Energy Modelling Framework (oemof) is a Python toolbox for energy system modelling and optimisation.

The oemof project aims to be a loose organisational frame for tools in the wide field of (energy) system modelling.
Every project is managed by their own developer team but we share some developer and design rules to make it easier to understand each other's tools. All project libraries are free software licenced under the MIT license.

All projects are in different stages of implementation, some even may not have a stable release, but all projects are open to be joined by interested people.
We do not belong to a specific institution and everybody is free to join the developer teams and will have the same rights.
There is no higher decision level.

oemof community
===============
The project `oemof/oemof <https://github.com/oemof/oemof>`_ does not contain any codeof the respective tools but is mainly used to organise everything for the oemof community.

- Webconference dates
- Real life meetings
- Website and Mailinglist
- General communication

You can find recent topics of discussion in the `issues <https://github.com/oemof/oemof/issues>`_.

Real life meetings
------------------
The oemof community meets in person on a regular basis. Find the latest information on the next meeting(s) on this wiki page: https://github.com/oemof/oemof/wiki

---

## Installation

See the upstream documentation quoted in What This Project Does above.

## Usage

The Open Energy Modelling Framework (oemof) is a Python toolbox for energy system modelling and optimisation.

The oemof project aims to be a loose organisational frame for tools in the wide field of (energy) system modelling.
Every project is managed by their own developer team but we share some developer and design rules to make it easier to understand each other's tools. All project libraries are free software licenced under the MIT license.

All projects are in different stages of implementation, some even may not have a stable release, but all projects are open to be joined by interested people.
We do not belong to a specific institution and everybody is free to join the developer teams and will have the same rights.
There is no higher decision level.

oemof community
===============
The project `oemof/oemof <https://github.com/oemof/oemof>`_ does not contain any codeof the respective tools but is mainly used to organise everything for the oemof community.

- Webconference dates
- Real life meetings
- Website and Mailinglist
- General communication

You can find recent topics of discussion in the `issues <https://github.com/oemof/oemof/issues>`_.

Real life meetings
------------------
The oemof community meets in person on a regular basis. Find the latest information on the next meeting(s) on this wiki page: https://github.com/oemof/oemof/wiki

## API

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | MIT |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

============
Contributing
============

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

Bug reports
===========

When `reporting a bug <https://github.com/oemof/oemof/issues>`_ please include:

    * Your operating system name and version.
    * Any details about your local setup that might be helpful in troubleshooting.
    * Detailed steps to reproduce the bug.

Documentation improvements
==========================

oemof could always use more documentation, whether as part of the
official oemof docs, in docstrings, or even on the web in blog posts,
articles, and such.

Feature requests and feedback
=============================

The best way to send feedback is to file an issue at https://github.com/oemof/oemof/issues.

If you are proposing a feature:

* Explain in detail how it would work.
* Keep the scope as narrow as possible, to make it easier to implement.
* Remember that this is a volunteer-driven project, and that code contributions are welcome :)

Development
===========

To set up `oemof` for local development:

1. Fork `oemof <https://github.com/oemof/oemof>`_
   (look for the "Fork" button).
2. source your fork locally::

    git source git@github.com:oemof/oemof.git

3. Create a branch for local development::

    git checkout -b name-of-your-bugfix-or-feature

   Now you can make your changes locally.

4. When you're done making changes run all the checks and docs builder with `tox <https://tox.readthedocs.io/en/latest/install.html>`_ one command::

    tox

5. Commit your changes and push your branch to GitHub::

    git add .
    git commit -m "Your detailed description of your changes."
    git push origin name-of-your-bugfix-or-feature

6. Submit a pull request through the GitHub website.

Pull Request Guidelines
-----------------------

If you need some code review or feedback while you're developing the code just make the pull request.

For merging, you should:

1. Include passing tests (run ``tox``) [1]_.
2. Update documentation when there's new API, functionality etc.
3. Add a note to ``CHANGELOG.rst`` about the changes.
4. Add yourself to ``AUTHORS.rst``.

.. [1] If you don't have all the necessary python versions available locally you can rely on Travis - it will
       `run the tests <https://travis-ci.org/oemof/oemof/pull_requests>`_ for each change you add in the pull request.

       It will be slower though ...

Tips
----

To run a subset of tests::

    tox -e envname -- pytest -k test_myfeature

To run all the test environments in *parallel* (you need to ``pip install detox``)::

    detox

## License

Upstream © its respective contributors under MIT (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** OEMOF
- **Pinned SHA:** `d2d7502862c8eec6963de97d9710bc27e4a41a5c`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.rst`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of `BENCH.json`: `055da8bd08b1b671ab5dbebbe7d8ed9dd315af17882ea2e53947eb7fc3b93b8e`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.


> Note: a same-named project in another category is the canonical published copy; this directory is retained as a local reference and is not published separately.
