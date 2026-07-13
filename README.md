# Awesome Industrial Engineering [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of free tools, learning resources, datasets and communities for industrial engineers, supply chain analysts, production planners and operations professionals.

Industrial engineering knowledge is scattered across expensive textbooks, paid certifications and consultancy decks. This list gathers the best **freely accessible** resources in one place — for students, practitioners and career-switchers.

*Curated and maintained by [Eren Gülmez](https://www.linkedin.com/in/erengulmez) — selection over volume: every entry earns its place. Contributions are welcome — see [Contributing](#contributing).*

🇹🇷 *Türkçe kaynaklar için [Turkish Resources](#turkish-resources--türkçe-kaynaklar) bölümüne bakın.*

## Contents

- [Learning Resources](#learning-resources)
- [AI Agent Skills](#ai-agent-skills)
- [Books & Classics](#books--classics)
- [Optimization & Operations Research](#optimization--operations-research)
- [Simulation](#simulation)
- [Forecasting & Demand Planning](#forecasting--demand-planning)
- [Production Planning & Scheduling](#production-planning--scheduling)
- [Lean & Continuous Improvement](#lean--continuous-improvement)
- [Quality & Statistical Process Control](#quality--statistical-process-control)
- [Process Mining](#process-mining)
- [Supply Chain Analytics](#supply-chain-analytics)
- [Data Analysis & Visualization](#data-analysis--visualization)
- [Open-Source ERP / MES / WMS](#open-source-erp--mes--wms)
- [Datasets](#datasets)
- [Standards & Professional Bodies](#standards--professional-bodies)
- [Communities](#communities)
- [Related Awesome Lists](#related-awesome-lists)
- [Turkish Resources / Türkçe Kaynaklar](#turkish-resources--türkçe-kaynaklar)
- [Roadmap](#roadmap)
- [Contributing](#contributing)

## Learning Resources

- [MITx MicroMasters: Supply Chain Management](https://www.edx.org/masters/micromasters/mitx-supply-chain-management) — University-level supply chain program; course content can be audited for free.
- [Rutgers Supply Chain Management Specialization](https://www.coursera.org/specializations/supply-chain-management) — Practical introduction covering logistics, operations and sourcing (free to audit).
- [Google Data Analytics Certificate](https://www.coursera.org/professional-certificates/google-data-analytics) — The de-facto entry path into data analysis tooling (free to audit).
- [freeCodeCamp: Data Analysis with Python](https://www.freecodecamp.org/learn/data-analysis-with-python/) — Free course with certificate.
- [Khan Academy: Statistics & Probability](https://www.khanacademy.org/math/statistics-probability) — The statistical foundation every industrial engineer needs.
- [NPTEL](https://nptel.ac.in/) — Free engineering courses from the IITs, including industrial engineering and operations research.
- [The CP-SAT Primer](https://github.com/d-krupke/cpsat-primer) — Outstanding practical guide to constraint programming with Google OR-Tools.
- [Forecasting: Principles and Practice (fpp3)](https://otexts.com/fpp3/) — The free reference book on forecasting, by Hyndman & Athanasopoulos.
- [NIST/SEMATECH e-Handbook of Statistical Methods](https://www.itl.nist.gov/div898/handbook/) — Free classic covering SPC, design of experiments and reliability.
- [OpenIntro Statistics](https://www.openintro.org/book/os/) — Free, open-source statistics textbook.
- [SQLBolt](https://sqlbolt.com/) — Learn SQL interactively in an afternoon.

## AI Agent Skills

- [industrial-engineering-ai-skills](https://github.com/gulmezeren2-byte/industrial-engineering-ai-skills) — IE methodology packaged as agent skills (OTIF audit, forecast accuracy, ABC-XYZ, safety stock, Pareto discipline, reporting contracts) for Claude Code, Codex, Cursor and any LLM.

## Books & Classics

*Not free — listed because they define the field. Check your local library.*

- *The Goal* — Eliyahu M. Goldratt. Theory of Constraints, told as a novel.
- *Factory Physics* — Wallace Hopp & Mark Spearman. The science underneath factory behaviour.
- *Toyota Production System* — Taiichi Ōno. Lean, from the source.
- *Lean Thinking* — James Womack & Daniel Jones.
- *The Machine That Changed the World* — Womack, Jones & Roos.
- *Out of the Crisis* — W. Edwards Deming.
- *Introduction to Operations Research* — Hillier & Lieberman.
- *Supply Chain Management: Strategy, Planning, and Operation* — Chopra & Meindl.
- *Designing and Managing the Supply Chain* — David Simchi-Levi et al.

## Optimization & Operations Research

- [OR-Tools](https://github.com/google/or-tools) — Google's open-source suite: CP-SAT, LP/MIP and routing.
- [Pyomo](https://github.com/Pyomo/pyomo) — Algebraic modeling in Python for LP/MIP/NLP.
- [PuLP](https://github.com/coin-or/pulp) — Beginner-friendly linear programming in Python.
- [CVXPY](https://github.com/cvxpy/cvxpy) — Convex optimization modeling language.
- [HiGHS](https://github.com/ERGO-Code/HiGHS) — High-performance open LP/MIP solver.
- [SCIP](https://github.com/scipopt/scip) — One of the fastest non-commercial MIP solvers.
- [Timefold Solver](https://github.com/TimefoldAI/timefold-solver) — AI constraint solver for scheduling, rostering and routing (successor of OptaPlanner).
- [PyVRP](https://github.com/PyVRP/PyVRP) — State-of-the-art open vehicle routing solver.
- [NetworkX](https://github.com/networkx/networkx) — Graph and network analysis in Python.
- [COIN-OR](https://www.coin-or.org/) — Umbrella organization for open operations research software.

## Simulation

- [SimPy](https://gitlab.com/team-simpy/simpy) — The standard process-based discrete-event simulation library for Python.
- [salabim](https://github.com/salabim/salabim) — Discrete-event simulation with built-in animation — great for factory and logistics models.
- [JaamSim](https://github.com/jaamsim/jaamsim) — Free GUI-based simulation package (drag-and-drop, 3D).
- [Mesa](https://github.com/projectmesa/mesa) — Agent-based modeling in Python.
- [AnyLogic PLE](https://www.anylogic.com/downloads/) — Free personal edition of the commercial multimethod simulation tool.

## Forecasting & Demand Planning

- [forecast-accuracy-lab](https://github.com/gulmezeren2-byte/forecast-accuracy-lab) — Five baseline models, rolling-origin backtesting and the metrics that don't lie: WMAPE, bias and Forecast Value Added.
- [statsforecast](https://github.com/Nixtla/statsforecast) — Lightning-fast classical models (ETS, ARIMA, Croston) — ideal for SKU-level demand.
- [Prophet](https://github.com/facebook/prophet) — Business time series with trend, seasonality and holidays.
- [sktime](https://github.com/sktime/sktime) — Unified machine-learning framework for time series.
- [darts](https://github.com/unit8co/darts) — Classical and deep forecasting behind one API.
- [GluonTS](https://github.com/awslabs/gluonts) — Probabilistic and deep forecasting from AWS.
- [statsmodels](https://github.com/statsmodels/statsmodels) — Econometrics and classical statistics in Python.

## Production Planning & Scheduling

- [frePPLe](https://github.com/frePPLe/frepple) — Open-source advanced planning & scheduling (APS): MRP, capacity planning, sequencing.
- [Timefold Quickstarts](https://github.com/TimefoldAI/timefold-quickstarts) — Ready-to-run job-shop and shift-scheduling examples.
- OptaPlanner — Archived predecessor of Timefold; its documentation and examples remain a useful reference.
- [The CP-SAT Primer](https://github.com/d-krupke/cpsat-primer) — See Learning Resources; includes excellent chapters on scheduling models.

## Lean & Continuous Improvement

- [Lean Enterprise Institute](https://www.lean.org/) — Articles, workbooks and the lean lexicon.
- [ASQ Quality Resources](https://asq.org/quality-resources) — Encyclopedic free hub: DMAIC, FMEA, SPC, the 7 basic tools.
- [iSixSigma](https://www.isixsigma.com/) — Long-running practitioner community and article base.

## Quality & Statistical Process Control

- [qcc](https://github.com/luca-scr/qcc) — R package for control charts and process capability analysis.
- [NIST/SEMATECH e-Handbook](https://www.itl.nist.gov/div898/handbook/) — The free SPC/DOE reference (see Learning Resources).

## Process Mining

- [PM4Py](https://github.com/process-intelligence-solutions/pm4py) — Process mining in Python: discovery, conformance, enhancement.
- [bupaR](https://github.com/bupaverse/bupaR) — Business process analysis in R.

## Supply Chain Analytics

- [otif-analytics](https://github.com/gulmezeren2-byte/otif-analytics) — Five definitions of "on-time", one dataset: an OTIF metric-ladder study with root-cause charts and a Streamlit explorer.
- [abc-xyz-inventory](https://github.com/gulmezeren2-byte/abc-xyz-inventory) — ABC-XYZ segmentation, a 9-box policy matrix and a stress test of the safety-stock formula on volatile SKUs.
- [tensor-house](https://github.com/ikatsov/tensor-house) — Large notebook collection: pricing, inventory, demand and supply chain AI.
- [Samir Saci's repositories](https://github.com/samirsaci) — Applied case studies: route optimization, sustainability reporting, forecasting.
- [awesome-supply-chain](https://github.com/Funkmyster/awesome-supply-chain) — Earlier curation effort with complementary scope.

## Data Analysis & Visualization

- [auto-report-pipeline](https://github.com/gulmezeren2-byte/auto-report-pipeline) — A scheduled pipeline that validates operational CSVs, computes weekly KPIs and delivers a plain-language HTML management report.
- [pandas](https://github.com/pandas-dev/pandas) — The workhorse of tabular data in Python.
- [DuckDB](https://github.com/duckdb/duckdb) — Analyze large files locally with SQL, no server needed.
- [Streamlit](https://github.com/streamlit/streamlit) — Turn a Python script into a shareable web app — the fastest way to ship an operations tool.
- [Plotly Dash](https://github.com/plotly/dash) — Production-grade dashboards in Python.
- [Apache Superset](https://github.com/apache/superset) — Open-source BI platform.
- [Metabase](https://github.com/metabase/metabase) — The easiest open-source BI to self-host.
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) — Free on Windows; the de-facto BI tool in manufacturing job postings.

## Open-Source ERP / MES / WMS

- [Odoo](https://github.com/odoo/odoo) — The most-starred open ERP; includes MRP, inventory and quality modules.
- [ERPNext](https://github.com/frappe/erpnext) — Full ERP including manufacturing.
- [Tryton](https://www.tryton.org/) — Modular open business software platform.
- [GreaterWMS](https://github.com/GreaterWMS/GreaterWMS) — Open-source warehouse management system.
- [United Manufacturing Hub](https://github.com/united-manufacturing-hub/united-manufacturing-hub) — Open manufacturing data stack (IIoT to analytics).

## Datasets

- [M5 Forecasting](https://www.kaggle.com/competitions/m5-forecasting-accuracy) — Walmart hierarchical retail demand; the benchmark for demand forecasting practice.
- [DataCo Smart Supply Chain](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis) — 180k orders with shipping, customer and product data — ideal for OTIF / delivery-performance analytics.
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/) — Includes several manufacturing and quality datasets.
- [awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets) — Master index for more.

## Standards & Professional Bodies

- [ASCM (APICS)](https://www.ascm.org/) — CPIM/CSCP certifications, salary reports, the SCOR model.
- [IISE](https://www.iise.org/) — Institute of Industrial and Systems Engineers.
- [INFORMS](https://www.informs.org/) — Operations research & analytics society.

## Communities

- [r/supplychain](https://www.reddit.com/r/supplychain/) — Active practitioner community.
- [r/IndustrialEngineering](https://www.reddit.com/r/IndustrialEngineering/) — Careers, tools, coursework.
- [OR Stack Exchange](https://or.stackexchange.com/) — Q&A for optimization practitioners.
- [Cross Validated](https://stats.stackexchange.com/) — Statistics Q&A.

## Related Awesome Lists

- [awesome-quant](https://github.com/wilsonfreitas/awesome-quant) — Proof of what a professional-vertical list can become.
- [awesome-ml4co](https://github.com/Thinklab-SJTU/awesome-ml4co) — Machine learning for combinatorial optimization.
- [awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets) — Datasets across every domain.

## Turkish Resources / Türkçe Kaynaklar

- [Model Fabrika](https://www.sanayi.gov.tr/merkez-birimi/92d9c73bddbb/model-fabrika/b81208) — Uygulamalı yalın üretim ve dijital dönüşüm yetkinlik merkezleri (12 şehir).
- [KOSGEB](https://www.kosgeb.gov.tr/) — KOBİ'ler için verimlilik ve dijital dönüşüm danışmanlık destekleri.
- [TÜBİTAK DDX](https://ddx.tubitak.gov.tr/) — Dijital Dönüşüm Danışmanlığı sertifika programı ve olgunluk modeli.

## Roadmap

- [ ] Grow to 150+ resources across all sections
- [ ] Career-path section (planner / analyst / continuous-improvement ladders)
- [x] Companion repo: [AI-agent skills for industrial engineering workflows](https://github.com/gulmezeren2-byte/industrial-engineering-ai-skills)
- [ ] Turkish translations of section intros

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) first. Rule of thumb: free/open resources first, and every entry needs a one-line "why it's useful."

## License

[CC0 1.0](LICENSE) — public domain dedication.
