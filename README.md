# Awesome Industrial Engineering [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome) ![Resources](https://img.shields.io/badge/resources-80+-blue) ![Last Commit](https://img.shields.io/github/last-commit/gulmezeren2-byte/awesome-industrial-engineering)

> Industrial engineering: designing, measuring and improving the systems that make and move things.

Industrial engineering knowledge is scattered across expensive textbooks, paid certifications and consultancy decks. This list gathers the best freely accessible tools, courses, datasets and communities in one place — for students, practitioners and career-switchers. Curated and maintained by [Eren Gülmez](https://github.com/gulmezeren2-byte): selection over volume, every entry earns its place.

🇹🇷 Türkçe sürüm: [README.tr.md](README.tr.md)

## Contents

- [Learning Resources](#learning-resources)
- [AI Agent Skills](#ai-agent-skills)
- [Books and Classics](#books-and-classics)
- [Optimization and Operations Research](#optimization-and-operations-research)
- [Simulation](#simulation)
- [Forecasting and Demand Planning](#forecasting-and-demand-planning)
- [Production Planning and Scheduling](#production-planning-and-scheduling)
- [Lean and Continuous Improvement](#lean-and-continuous-improvement)
- [Quality and Statistical Process Control](#quality-and-statistical-process-control)
- [Process Mining](#process-mining)
- [Supply Chain Analytics](#supply-chain-analytics)
- [Data Analysis and Visualization](#data-analysis-and-visualization)
- [Open-Source ERP, MES and WMS](#open-source-erp-mes-and-wms)
- [Datasets](#datasets)
- [Standards and Professional Bodies](#standards-and-professional-bodies)
- [Communities](#communities)
- [Related Awesome Lists](#related-awesome-lists)
- [Turkish Resources](#turkish-resources)

Recently added: erp-report-engine (read-only weekly reports from the SQL database behind an ERP) · opsaudit (agent-first ops CLI) · industrial-engineering-ai-skills (method pack) — see their sections below.

## Learning Resources

- [MITx MicroMasters: Supply Chain Management](https://micromasters.mit.edu/scm/) - University-level supply chain program; course content can be audited for free.
- [Rutgers Supply Chain Management Specialization](https://www.coursera.org/specializations/supply-chain-management) - Practical introduction covering logistics, operations and sourcing (free to audit).
- [Google Data Analytics Certificate](https://www.coursera.org/professional-certificates/google-data-analytics) - The de facto entry path into data analysis tooling (financial aid available).
- [freeCodeCamp: Data Analysis with Python](https://www.freecodecamp.org/learn/data-analysis-with-python/) - Free course with certificate.
- [Khan Academy: Statistics and Probability](https://www.khanacademy.org/math/statistics-probability) - The statistical foundation every industrial engineer needs.
- [NPTEL](https://nptel.ac.in/) - Free engineering courses from the IITs, including industrial engineering and operations research.
- [The CP-SAT Primer](https://github.com/d-krupke/cpsat-primer) - Outstanding practical guide to constraint programming with Google OR-Tools, including scheduling models.
- [Forecasting: Principles and Practice](https://otexts.com/fpp3/) - The free reference book on forecasting, by Hyndman and Athanasopoulos.
- [NIST/SEMATECH e-Handbook of Statistical Methods](https://www.itl.nist.gov/div898/handbook/) - Free classic covering SPC, design of experiments and reliability.
- [OpenIntro Statistics](https://www.openintro.org/book/os/) - Free, open-source statistics textbook.
- [SQLBolt](https://sqlbolt.com/) - Learn SQL interactively in an afternoon.

## AI Agent Skills

- [industrial-engineering-ai-skills](https://github.com/gulmezeren2-byte/industrial-engineering-ai-skills) - IE methodology packaged as agent skills (OTIF audit, forecast accuracy, ABC-XYZ, safety stock, Pareto discipline, reporting contracts) for Claude Code, Codex, Cursor and any LLM.
- [opsaudit](https://github.com/gulmezeren2-byte/opsaudit) - JSON-only CLI for agents and pipelines: OTIF, forecast backtests, ABC-XYZ and Pareto, each result carrying a mandatory honesty block.

## Books and Classics

Not free — listed because they define the field. Check your local library.

- [The Goal](https://en.wikipedia.org/wiki/The_Goal_(novel)) - Eliyahu M. Goldratt. Theory of Constraints, told as a novel.
- [Factory Physics](https://factoryphysics.com/) - Wallace Hopp and Mark Spearman. The science underneath factory behaviour.
- [Toyota Production System](https://en.wikipedia.org/wiki/Toyota_Production_System) - Taiichi Ohno. Lean, from the source.
- [Lean Thinking](https://en.wikipedia.org/wiki/Lean_thinking) - James Womack and Daniel Jones.
- [The Machine That Changed the World](https://en.wikipedia.org/wiki/The_Machine_That_Changed_the_World_(book)) - Womack, Jones and Roos.
- [Out of the Crisis](https://en.wikipedia.org/wiki/W._Edwards_Deming) - W. Edwards Deming.
- [Introduction to Operations Research](https://en.wikipedia.org/wiki/Frederick_S._Hillier) - Hillier and Lieberman.
- [Supply Chain Management: Strategy, Planning, and Operation](https://en.wikipedia.org/wiki/Sunil_Chopra_(academic)) - Chopra and Meindl.
- [Designing and Managing the Supply Chain](https://en.wikipedia.org/wiki/David_Simchi-Levi) - David Simchi-Levi et al.

## Optimization and Operations Research

- [OR-Tools](https://github.com/google/or-tools) - Google's open-source suite: CP-SAT, LP/MIP and routing.
- [Pyomo](https://github.com/Pyomo/pyomo) - Algebraic modeling in Python for LP/MIP/NLP.
- [PuLP](https://github.com/coin-or/pulp) - Beginner-friendly linear programming in Python.
- [CVXPY](https://github.com/cvxpy/cvxpy) - Convex optimization modeling language.
- [HiGHS](https://github.com/ERGO-Code/HiGHS) - High-performance open LP/MIP solver.
- [SCIP](https://github.com/scipopt/scip) - One of the fastest non-commercial MIP solvers.
- [Timefold Solver](https://github.com/TimefoldAI/timefold-solver) - AI constraint solver for scheduling, rostering and routing; successor of OptaPlanner.
- [PyVRP](https://github.com/PyVRP/PyVRP) - State-of-the-art open vehicle routing solver.
- [NetworkX](https://github.com/networkx/networkx) - Graph and network analysis in Python.
- [COIN-OR](https://www.coin-or.org/) - Umbrella organization for open operations research software.

## Simulation

- [SimPy](https://gitlab.com/team-simpy/simpy) - The standard process-based discrete-event simulation library for Python.
- [salabim](https://github.com/salabim/salabim) - Discrete-event simulation with built-in animation, great for factory and logistics models.
- [JaamSim](https://github.com/jaamsim/jaamsim) - Free GUI-based simulation package with drag-and-drop 3D modeling.
- [Mesa](https://github.com/mesa/mesa) - Agent-based modeling in Python.
- [AnyLogic PLE](https://www.anylogic.com/downloads/) - Free personal edition of the commercial multimethod simulation tool.

## Forecasting and Demand Planning

- [forecast-accuracy-lab](https://github.com/gulmezeren2-byte/forecast-accuracy-lab) - Five baseline models, rolling-origin backtesting and the metrics that don't lie: WMAPE, bias and Forecast Value Added.
- [forecast-autoresearch](https://github.com/gulmezeren2-byte/forecast-autoresearch) - A sealed-holdout research harness asking whether an AI agent can honestly beat naive forecasting; single metric, frozen protocol, human-directed program.
- [statsforecast](https://github.com/Nixtla/statsforecast) - Lightning-fast classical models (ETS, ARIMA, Croston), ideal for SKU-level demand.
- [Prophet](https://github.com/facebook/prophet) - Business time series with trend, seasonality and holidays.
- [sktime](https://github.com/sktime/sktime) - Unified machine-learning framework for time series.
- [darts](https://github.com/unit8co/darts) - Classical and deep forecasting behind one API.
- [GluonTS](https://github.com/awslabs/gluonts) - Probabilistic and deep forecasting from AWS.
- [statsmodels](https://github.com/statsmodels/statsmodels) - Econometrics and classical statistics in Python.

## Production Planning and Scheduling

- [frePPLe](https://github.com/frePPLe/frepple) - Open-source advanced planning and scheduling: MRP, capacity planning, sequencing.
- [Timefold Quickstarts](https://github.com/TimefoldAI/timefold-quickstarts) - Ready-to-run job-shop and shift-scheduling examples.

## Lean and Continuous Improvement

- [Lean Enterprise Institute](https://www.lean.org/) - Articles, workbooks and the lean lexicon.
- [ASQ Quality Resources](https://asq.org/quality-resources) - Encyclopedic free hub: DMAIC, FMEA, SPC, the seven basic tools.
- [iSixSigma](https://www.isixsigma.com/) - Long-running practitioner community and article base.

## Quality and Statistical Process Control

- [qcc](https://github.com/luca-scr/qcc) - R package for control charts and process capability analysis.

## Process Mining

- [PM4Py](https://github.com/process-intelligence-solutions/pm4py) - Process mining in Python: discovery, conformance, enhancement.
- [bupaR](https://github.com/bupaverse/bupaR) - Business process analysis in R.

## Supply Chain Analytics

- [otif-analytics](https://github.com/gulmezeren2-byte/otif-analytics) - Five definitions of "on-time", one dataset: an OTIF metric-ladder study with driver-decomposition charts and a Streamlit explorer.
- [abc-xyz-inventory](https://github.com/gulmezeren2-byte/abc-xyz-inventory) - ABC-XYZ segmentation, a 9-box policy matrix and a stress test of the safety-stock formula on volatile SKUs.
- [tensor-house](https://github.com/ikatsov/tensor-house) - Large notebook collection: pricing, inventory, demand and supply chain AI.
- [Samir Saci's repositories](https://github.com/samirsaci) - Applied case studies: route optimization, sustainability reporting, forecasting.
- [awesome-supply-chain](https://github.com/Funkmyster/awesome-supply-chain) - Earlier curation effort with complementary scope.

## Data Analysis and Visualization

- [auto-report-pipeline](https://github.com/gulmezeren2-byte/auto-report-pipeline) - A scheduled pipeline that validates operational CSVs, computes weekly KPIs and delivers a plain-language HTML management report.
- [erp-report-engine](https://github.com/gulmezeren2-byte/erp-report-engine) - Weekly KPI reports and a Power BI Command Center from the SQL database behind an ERP (Logo Tiger, Netsis, Mikro) - read-only by construction and measured against a public 28-attack benchmark, plus a guarded MCP server so an AI agent can query the ERP safely. On PyPI and the official MCP registry.
- [pandas](https://github.com/pandas-dev/pandas) - The workhorse of tabular data in Python.
- [DuckDB](https://github.com/duckdb/duckdb) - Analyze large files locally with SQL, no server needed.
- [Streamlit](https://github.com/streamlit/streamlit) - Turn a Python script into a shareable web app, the fastest way to ship an operations tool.
- [Plotly Dash](https://github.com/plotly/dash) - Production-grade dashboards in Python.
- [Apache Superset](https://github.com/apache/superset) - Open-source BI platform.
- [Metabase](https://github.com/metabase/metabase) - The easiest open-source BI to self-host.
- [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/desktop) - Free on Windows; the de facto BI tool in manufacturing job postings.

## Open-Source ERP, MES and WMS

- [Odoo](https://github.com/odoo/odoo) - The most-starred open ERP; includes MRP, inventory and quality modules.
- [ERPNext](https://github.com/frappe/erpnext) - Full ERP including manufacturing.
- [Tryton](https://www.tryton.org/) - Modular open business software platform.
- [GreaterWMS](https://github.com/GreaterWMS/GreaterWMS) - Open-source warehouse management system.
- [United Manufacturing Hub](https://github.com/united-manufacturing-hub/united-manufacturing-hub) - Open manufacturing data stack, from IIoT to analytics.

## Datasets

- [M5 Forecasting](https://www.kaggle.com/competitions/m5-forecasting-accuracy) - Walmart hierarchical retail demand; the benchmark for demand forecasting practice.
- [DataCo Smart Supply Chain](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis) - 180k orders with shipping, customer and product data, ideal for delivery-performance analytics.
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/) - Includes several manufacturing and quality datasets.

## Standards and Professional Bodies

- [ASCM](https://www.ascm.org/) - CPIM/CSCP certifications, salary reports, the SCOR model.
- [IISE](https://www.iise.org/) - Institute of Industrial and Systems Engineers.
- [INFORMS](https://www.informs.org/) - Operations research and analytics society.

## Communities

- [r/supplychain](https://www.reddit.com/r/supplychain/) - Active practitioner community.
- [r/IndustrialEngineering](https://www.reddit.com/r/IndustrialEngineering/) - Careers, tools, coursework.
- [OR Stack Exchange](https://or.stackexchange.com/) - Q&A for optimization practitioners.
- [Cross Validated](https://stats.stackexchange.com/) - Statistics Q&A.

## Related Awesome Lists

- [awesome-quant](https://github.com/wilsonfreitas/awesome-quant) - Proof of what a professional-vertical list can become.
- [awesome-ml4co](https://github.com/Thinklab-SJTU/awesome-ml4co) - Machine learning for combinatorial optimization.
- [awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets) - Datasets across every domain.

## Turkish Resources

Türkçe kaynaklar — Turkish-language resources for practitioners in Türkiye.

- [Model Fabrika](https://www.sanayi.gov.tr/merkez-birimi/92d9c73bddbb/model-fabrika/b81208) - Uygulamalı yalın üretim ve dijital dönüşüm yetkinlik merkezleri ağı.
- [KOSGEB](https://www.kosgeb.gov.tr/) - KOBİ'ler için verimlilik ve dijital dönüşüm danışmanlık destekleri.
- [TÜBİTAK DDX](https://ddx.tubitak.gov.tr/) - Dijital Dönüşüm Değerlendirme Modeli: işletmeleri sertifikalı dijital dönüşüm danışmanlarıyla buluşturan değerlendirme ve yol haritası programı.
