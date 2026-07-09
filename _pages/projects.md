---
layout: single
title: Projects
permalink: /projects/
author_profile: false
classes:
  - cv-modern
---

<section class="cv-page-hero">
  <p class="cv-kicker">Selected projects</p>
  <h1>Applied AI work from technical strategy to production delivery.</h1>
  <p>
    A portfolio of industry and research projects translated into senior Data Scientist, Applied Scientist, and Machine Learning Engineer language: model design, experimentation strategy, scalable data pipelines, computer vision, statistical rigor, and stakeholder-facing delivery.
  </p>
</section>

<nav class="profile-nav" aria-label="Project sections">
  <a href="#industry">Industry</a>
  <a href="#research-engineering">Research engineering</a>
  <a href="#skills">Skills</a>
  <a href="/cv/">CV</a>
</nav>

<section class="cv-section" id="industry">
  <h2>Industry Projects</h2>
  <div class="project-card-grid">
    <article class="project-card">
      <div class="project-card__header">
        <div>
          <p class="cv-kicker">E-commerce recommendations</p>
          <h3>Recommendation Systems at Mercado Libre</h3>
          <p class="project-card__subtitle">Production ranking model serving millions of users across Argentina, Brazil, and Mexico.</p>
        </div>
        <div class="project-card__visual">Ranking graph</div>
      </div>
      <p>Primary data science owner for an online ranking model used by dozens of internal clients at LATAM scale. The work combined PyTorch model development, production feature-store integration, embedding changes, CUDA and Fury pipeline optimization, MLflow experiment tracking, ONNX artifact validation, and monitoring in Datadog and Looker. I guided controlled production experiments, communicated trade-offs and risks, and supported release decisions using statistical evidence and business KPIs.</p>
      <div class="project-badges">
        <span>PyTorch</span><span>Ranking</span><span>Recommenders</span><span>MLflow</span><span>ONNX</span><span>A/B testing</span><span>Production ML</span>
      </div>
      <details>
        <summary>Read more</summary>
        <ul>
          <li><strong>Challenge:</strong> improve model behavior and release safety in a high-traffic recommendation environment.</li>
          <li><strong>Contribution:</strong> tripled training-data capacity through pipeline, framework, and CUDA optimization.</li>
          <li><strong>Transferable skills:</strong> experimentation, model governance, cross-functional delivery, monitoring, and production ownership.</li>
        </ul>
      </details>
    </article>

    <article class="project-card">
      <div class="project-card__header">
        <div>
          <p class="cv-kicker">Applied data science leadership</p>
          <h3>Data Science Lead at IThreex Global</h3>
          <p class="project-card__subtitle">Eight-person team delivering client-facing AI and analytics products.</p>
        </div>
        <div class="project-card__visual">Platform map</div>
      </div>
      <p>Led an eight-person data science team across public revenue, agriculture, retail, tourism, and international trade. I defined technical roadmaps and OKRs for the Molibdeno AI platform, designed the core Python library for reusable ML workflows, mentored and onboarded data scientists, and acted as technical contact for client projects. Delivery included tax-revenue forecasting, payment-behavior analysis, customer segmentation, computer vision for cattle-weight estimation, and a LangChain RAG support API.</p>
      <div class="project-badges">
        <span>Python</span><span>Forecasting</span><span>Computer vision</span><span>RAG</span><span>Roadmaps</span><span>OKRs</span><span>Team leadership</span>
      </div>
      <details>
        <summary>Read more</summary>
        <ul>
          <li><strong>Challenge:</strong> turn ambiguous client needs into reusable, maintainable data products.</li>
          <li><strong>Contribution:</strong> provided technical direction, mentoring, client reporting, and reusable platform foundations.</li>
          <li><strong>Transferable skills:</strong> AI solution design, stakeholder management, delivery planning, and technical leadership.</li>
        </ul>
      </details>
    </article>
  </div>
</section>

<section class="cv-section" id="research-engineering">
  <h2>Research Engineering Projects</h2>
  <div class="project-card-grid">
    <article class="project-card">
      <div class="project-card__header">
        <div>
          <p class="cv-kicker">Real-time event detection</p>
          <h3>TOROS: Gravitational-Wave Counterpart Detection</h3>
          <p class="project-card__subtitle">Real-time computer vision pipeline for rare-event discovery.</p>
        </div>
        <div class="project-card__visual">Alert pipeline</div>
      </div>
      <p>Developed software and machine learning workflows for identifying visible-light signals associated with gravitational-wave alerts during the LIGO/Virgo O1 and O2 follow-up campaigns. After an alert, the pipeline processed telescope images within hours, compared new observations against references, detected candidate changes, ranked them statistically, and supported follow-up decisions across observatories. TOROS responded to three O2 alerts, including GW170104 and GW170817, translating directly to anomaly detection settings where speed, false-positive control, and human-in-the-loop validation matter.</p>
      <div class="project-highlights">
        <span>4,853 labeled examples</span>
        <span>Random Forest F1 = 0.89</span>
        <span>39 candidates from 2,375 rejected bogus detections</span>
      </div>
      <div class="project-badges">
        <span>Python</span><span>Computer vision</span><span>Random Forest</span><span>Difference imaging</span><span>Real-time alerts</span><span>Human-in-the-loop ML</span>
      </div>
      <details>
        <summary>Read more</summary>
        <ul>
          <li><strong>Challenge:</strong> find rare signals in noisy images under tight follow-up windows, while controlling subtraction artifacts and false positives.</li>
          <li><strong>Contribution:</strong> difference imaging, candidate detection, statistical prioritization, and validation workflow design using 2,414 bogus artifacts and 2,439 injected transients.</li>
          <li><strong>Scale:</strong> three observing facilities in Argentina and Chile; 26 galaxies followed during the first two nights after GW170817.</li>
          <li><strong>Source:</strong> <a href="https://arxiv.org/pdf/1901.02960">TOROS O2 paper</a>.</li>
          <li><strong>Industry analogues:</strong> fraud detection, medical alerting, security monitoring, and manufacturing anomaly detection.</li>
        </ul>
      </details>
    </article>

    <article class="project-card">
      <div class="project-card__header">
        <div>
          <p class="cv-kicker">Data-intensive pipeline framework</p>
          <h3>Corral Framework</h3>
          <p class="project-card__subtitle">SQL-backed Python framework for reproducible data-processing pipelines.</p>
        </div>
        <div class="project-card__visual">Pipeline engine</div>
      </div>
      <p>Contributed to Corral, a Python framework for building data-intensive astronomical pipelines around an MVC architecture on top of SQL relational databases. Corral supports custom data models, staged processing, communication alerts, multiprocessing, distributed computing, and unit-test-based quality metrics. In industry terms, this is platform engineering for reproducible data workflows: structure the data model, orchestrate transformations, track quality, and make complex pipelines maintainable by teams.</p>
      <div class="project-highlights">
        <span>SQL-backed MVC architecture</span>
        <span>Multiprocessing and distributed computing</span>
        <span>7-author public framework paper</span>
      </div>
      <div class="project-badges">
        <span>Python</span><span>SQL</span><span>Pipeline orchestration</span><span>Testing</span><span>Distributed processing</span><span>Data models</span>
      </div>
      <details>
        <summary>Read more</summary>
        <ul>
          <li><strong>Challenge:</strong> standardize complex data-processing workflows while preserving flexibility for different scientific pipelines.</li>
          <li><strong>Contribution:</strong> framework design, public code, pipeline patterns, quality metrics, and reproducible workflow practices.</li>
          <li><strong>Source:</strong> public GitHub code and a 19-page Astronomy and Computing paper.</li>
          <li><strong>Industry analogues:</strong> ML/data platform engineering, ETL orchestration, analytics infrastructure, and quality-controlled batch processing.</li>
        </ul>
      </details>
    </article>

    <article class="project-card">
      <div class="project-card__header">
        <div>
          <p class="cv-kicker">Public-interest analytics</p>
          <h3>Arcovid19 Decision-Support Platform</h3>
          <p class="project-card__subtitle">Open-data pipelines and dashboards during the COVID-19 pandemic.</p>
        </div>
        <div class="project-card__visual">Dashboard</div>
      </div>
      <p>Co-developed Arcovid19, a multidisciplinary open-data initiative integrating epidemiological datasets, statistical analyses, and interactive visualizations during the COVID-19 pandemic. The project was organized around five freely available products and work axes, including automated official-data curation, reconciliation workflows, error calculation, epidemiological scenario generation, benchmarking, and reporting. Its value was not only modeling, but also building transparent workflows that could support public-facing interpretation and institutional decision-making under uncertainty.</p>
      <div class="project-highlights">
        <span>5 open products/work axes</span>
        <span>Brooks spreadsheet-ingestion tool</span>
        <span>Official-data curation and reconciliation</span>
      </div>
      <div class="project-badges">
        <span>ETL</span><span>Open data</span><span>Forecasting</span><span>Dashboards</span><span>Noisy data ingestion</span><span>Public health</span>
      </div>
      <details>
        <summary>Read more</summary>
        <ul>
          <li><strong>Challenge:</strong> integrate fast-changing public data into reliable analytical products despite spreadsheet errors, duplicate records, and source inconsistencies.</li>
          <li><strong>Contribution:</strong> data engineering, statistical analysis, visualization, reproducibility, and scientific communication.</li>
          <li><strong>Engineering detail:</strong> Brooks was designed for rapid epidemiological loading from spreadsheets while tolerating errors and duplicates.</li>
          <li><strong>Industry analogues:</strong> healthcare analytics, business intelligence, executive dashboards, and risk monitoring.</li>
        </ul>
      </details>
    </article>

    <article class="project-card">
      <div class="project-card__header">
        <div>
          <p class="cv-kicker">Computer vision at scale</p>
          <h3>Automatic Galaxy Detection in Infrared Images</h3>
          <p class="project-card__subtitle">Object detection in extremely crowded and noisy image data.</p>
        </div>
        <div class="project-card__visual">Image detector</div>
      </div>
      <p>Designed computer vision methods for detecting galaxies hidden behind dense foreground stars in near-infrared survey images. In plain terms, the task was to identify faint extended objects in images where the background is crowded, noisy, and uneven. This work contributed to VVV/VVVX catalog efforts spanning hundreds to thousands of square degrees, using CNNs on image data and XGBoost on photometric and morphological features. The same methods map naturally to medical imaging, satellite imagery, and industrial defect detection.</p>
      <div class="project-highlights">
        <span>VVV: 562 sq. deg.</span>
        <span>VVVX: 1,700 sq. deg.</span>
        <span>CNN + XGBoost classifiers</span>
      </div>
      <div class="project-badges">
        <span>Computer vision</span><span>CNN</span><span>XGBoost</span><span>Feature engineering</span><span>Quality control</span><span>Catalog generation</span>
      </div>
      <details>
        <summary>Read more</summary>
        <ul>
          <li><strong>Challenge:</strong> distinguish faint extended objects from dense backgrounds and artifacts.</li>
          <li><strong>Contribution:</strong> object detection, morphological analysis, ML classification, and automated validation workflows.</li>
          <li><strong>Scale:</strong> the Southern Galactic disc catalogue covered 1,080 square degrees and contains 167,559 galaxy candidates.</li>
          <li><strong>Validation:</strong> 14% of catalogue objects were confirmed through visual inspection or cross-match with previous catalogues.</li>
          <li><strong>Transferable skills:</strong> noisy-image modeling, defect detection, visual QA, and scalable labeling support.</li>
        </ul>
      </details>
    </article>

    <article class="project-card">
      <div class="project-card__header">
        <div>
          <p class="cv-kicker">Time-series machine learning</p>
          <h3>Variable Star Classification</h3>
          <p class="project-card__subtitle">Supervised learning from irregular time-series observations.</p>
        </div>
        <div class="project-card__visual">Time series</div>
      </div>
      <p>Developed machine learning methods for classifying variable objects from repeated observations over time. The technical problem was similar to many industrial time-series tasks: observations are irregular, noisy, incomplete, and must be transformed into robust features before classification. The project involved signal processing, feature extraction, supervised learning, and model evaluation, with emphasis on reliability rather than a single metric. It also required deciding which features were stable enough to generalize across instruments, observing conditions, and object classes.</p>
      <div class="project-badges">
        <span>Time series</span><span>Signal processing</span><span>Supervised learning</span><span>Feature extraction</span><span>Model evaluation</span>
      </div>
      <details>
        <summary>Read more</summary>
        <ul>
          <li><strong>Challenge:</strong> learn from irregular sequences with missing observations and variable signal quality.</li>
          <li><strong>Contribution:</strong> feature design, classifier development, validation, and scientific interpretation.</li>
          <li><strong>Industry analogues:</strong> predictive maintenance, IoT analytics, finance, and customer behavior modeling.</li>
        </ul>
      </details>
    </article>

    <article class="project-card">
      <div class="project-card__header">
        <div>
          <p class="cv-kicker">Large-scale catalog engineering</p>
          <h3>VVV Near-Infrared Galaxy Catalogue</h3>
          <p class="project-card__subtitle">Automated catalog construction from millions of survey detections.</p>
        </div>
        <div class="project-card__visual">Data catalog</div>
      </div>
      <p>Contributed to one of the largest catalogs of galaxies hidden behind the Galactic Plane by processing infrared detections from the VISTA Variables in the Via Lactea survey and its VVVX extension. The engineering work included extraction, filtering, automated validation, metadata organization, and statistical characterization. The project is best understood as a data-platform problem: converting noisy raw detections into a reliable, searchable, documented dataset suitable for downstream analysis.</p>
      <div class="project-highlights">
        <span>167,559 galaxy candidates</span>
        <span>1,080 sq. deg. Southern catalogue</span>
        <span>1,003 new Northern galaxies</span>
      </div>
      <div class="project-badges">
        <span>Data engineering</span><span>Python</span><span>Databases</span><span>ETL</span><span>Metadata</span><span>Data quality</span>
      </div>
      <details>
        <summary>Read more</summary>
        <ul>
          <li><strong>Challenge:</strong> transform massive observational output into a trusted structured catalog while replacing large parts of manual inspection with scalable ML and quality control.</li>
          <li><strong>Contribution:</strong> automated extraction, catalog generation, quality validation, and statistical summaries.</li>
          <li><strong>Discovery:</strong> the Northern Galactic disc catalogue identified 1,003 new galaxies, with only two previously known.</li>
          <li><strong>Industry analogues:</strong> product catalogs, data warehouses, metadata platforms, and master-data workflows.</li>
        </ul>
      </details>
    </article>

    <article class="project-card">
      <div class="project-card__header">
        <div>
          <p class="cv-kicker">Regression under uncertainty</p>
          <h3>DEEPz Photometric Redshift Estimation</h3>
          <p class="project-card__subtitle">Machine learning for distance estimation from noisy observations.</p>
        </div>
        <div class="project-card__visual">Regression</div>
      </div>
      <p>Worked on machine learning models for estimating galaxy distances from photometric measurements, a lower-cost alternative to more expensive direct measurements. Technically, this is a regression problem with noisy, incomplete, high-dimensional inputs and uncertainty that must be communicated honestly. DEEPz produced photometric redshifts for more than 1.3 million galaxies over 50.38 square degrees, using deep-learning techniques such as transfer learning, mixture density networks, autoencoders, and ensemble models.</p>
      <div class="project-highlights">
        <span>1,341,559 galaxy predictions</span>
        <span>50.38 sq. deg. survey area</span>
        <span>20-50% smaller scatter for faint galaxies</span>
      </div>
      <div class="project-badges">
        <span>Deep learning</span><span>Regression</span><span>Uncertainty</span><span>Calibration</span><span>Transfer learning</span><span>Ensembles</span>
      </div>
      <details>
        <summary>Read more</summary>
        <ul>
          <li><strong>Challenge:</strong> infer continuous quantities from indirect measurements with known noise and bias.</li>
          <li><strong>Contribution:</strong> model development, uncertainty-aware validation, calibration, and robust feature handling.</li>
          <li><strong>Performance:</strong> for faint galaxies, DEEPz achieved 20-50% smaller scatter than BCNz2 in several fields; earlier work reported a 50% reduction in σ68 scatter at i_AB = 22.5.</li>
          <li><strong>Industry analogues:</strong> price prediction, demand forecasting, credit scoring, and risk modeling.</li>
        </ul>
      </details>
    </article>

    <article class="project-card">
      <div class="project-card__header">
        <div>
          <p class="cv-kicker">Spatial analytics</p>
          <h3>Large-Scale Structure of the Universe</h3>
          <p class="project-card__subtitle">Statistical modeling of massive three-dimensional spatial datasets.</p>
        </div>
        <div class="project-card__visual">Spatial map</div>
      </div>
      <p>Developed statistical methods to study how galaxies are distributed across very large volumes of space using observational data and simulation outputs. Stripped of domain jargon, the work involved spatial pattern discovery, clustering, simulation, Bayesian inference, and model comparison on massive 3D datasets. I worked with SDSS observational data and the Millennium Simulation, whose public database represents 10^10 simulated particles in a 500 h^-1 Mpc box. The transferable value maps to geospatial analytics, network analysis, and spatial intelligence platforms.</p>
      <div class="project-highlights">
        <span>SDSS + Millennium data</span>
        <span>10^10 simulated particles</span>
        <span>Jackknife uncertainty estimation</span>
      </div>
      <div class="project-badges">
        <span>Spatial statistics</span><span>Bayesian inference</span><span>Monte Carlo</span><span>Correlation functions</span><span>R</span><span>Python</span>
      </div>
      <details>
        <summary>Read more</summary>
        <ul>
          <li><strong>Challenge:</strong> extract reliable structure from sparse, biased, and high-dimensional spatial data.</li>
          <li><strong>Contribution:</strong> statistical methodology, simulations, inference workflows, and publication-quality validation.</li>
          <li><strong>Methods:</strong> correlation functions, jackknife uncertainty estimation, friends-of-friends/percolation, and minimal spanning trees.</li>
          <li><strong>Industry analogues:</strong> location intelligence, logistics, market mapping, and network analytics.</li>
        </ul>
      </details>
    </article>

    <article class="project-card">
      <div class="project-card__header">
        <div>
          <p class="cv-kicker">Unsupervised discovery</p>
          <h3>Cosmic Void Detection</h3>
          <p class="project-card__subtitle">Finding low-density regions in massive 3D datasets.</p>
        </div>
        <div class="project-card__visual">Clustering</div>
      </div>
      <p>Designed algorithms to discover large low-density regions inside complex three-dimensional point-cloud data. In industry language, this is unsupervised structure discovery: estimating density, finding meaningful segments, handling geometry, and validating whether detected patterns are real or artifacts. The analysis compared observational and simulated datasets, including 252 voids in SDSS and 4,015 voids in the full Millennium simulation box, with radii from 6 to 24 h^-1 Mpc.</p>
      <div class="project-highlights">
        <span>252 SDSS voids</span>
        <span>4,015 simulation voids</span>
        <span>Density below 10% of cosmic mean</span>
      </div>
      <div class="project-badges">
        <span>Unsupervised learning</span><span>Clustering</span><span>Density estimation</span><span>Geometry</span><span>Scientific computing</span>
      </div>
      <details>
        <summary>Read more</summary>
        <ul>
          <li><strong>Challenge:</strong> identify meaningful low-density regions without labels or simple ground truth.</li>
          <li><strong>Contribution:</strong> algorithm design, validation, simulation, and interpretation of detected structures.</li>
          <li><strong>Method detail:</strong> used density-contrast thresholds below -0.8 and total density below 10% of the cosmic mean.</li>
          <li><strong>Transferable skills:</strong> segmentation, anomaly discovery, spatial modeling, and unsupervised validation.</li>
        </ul>
      </details>
    </article>

    <article class="project-card">
      <div class="project-card__header">
        <div>
          <p class="cv-kicker">Experimentation and inference</p>
          <h3>Galaxy Spin Alignment Analysis</h3>
          <p class="project-card__subtitle">Hypothesis testing over large observational datasets.</p>
        </div>
        <div class="project-card__visual">A/B testing</div>
      </div>
      <p>Performed statistical analyses of orientation patterns to test whether measured directions correlate with the surrounding environment. The business translation is experimentation under observational constraints: define a hypothesis, construct a reliable null model, estimate significance, and avoid over-interpreting noisy correlations. The work required Monte Carlo simulations, correlation analysis, uncertainty quantification, and careful communication of statistical evidence. This kind of reasoning is directly useful when product or model changes appear promising but the evidence is subtle.</p>
      <div class="project-badges">
        <span>Hypothesis testing</span><span>Monte Carlo</span><span>Correlation analysis</span><span>Bayesian statistics</span><span>Experimentation</span>
      </div>
      <details>
        <summary>Read more</summary>
        <ul>
          <li><strong>Challenge:</strong> separate weak statistical signals from random alignments and selection effects.</li>
          <li><strong>Contribution:</strong> significance estimation, simulation-based validation, and evidence communication.</li>
          <li><strong>Industry analogues:</strong> A/B testing, causal inference, marketing analytics, and model-impact analysis.</li>
        </ul>
      </details>
    </article>

    <article class="project-card">
      <div class="project-card__header">
        <div>
          <p class="cv-kicker">Entity resolution</p>
          <h3>Cross-Matching Astronomical Catalogs</h3>
          <p class="project-card__subtitle">Matching millions of records across heterogeneous data sources.</p>
        </div>
        <div class="project-card__visual">Record linkage</div>
      </div>
      <p>Developed scalable methods for matching objects across catalogs produced by different instruments and surveys. The technical problem is entity resolution: multiple sources describe overlapping real-world objects, with different errors, formats, missing values, and uncertainty. The work involved approximate nearest-neighbor search, large database integration, reconciliation rules, and quality checks. These are directly relevant to customer identity resolution, CRM integration, master data management, and data fusion.</p>
      <div class="project-badges">
        <span>Entity resolution</span><span>Nearest neighbors</span><span>Database integration</span><span>Record linkage</span><span>Data quality</span>
      </div>
      <details>
        <summary>Read more</summary>
        <ul>
          <li><strong>Challenge:</strong> join uncertain records at scale when exact keys do not exist.</li>
          <li><strong>Contribution:</strong> matching algorithms, reconciliation logic, validation, and scalable search design.</li>
          <li><strong>Transferable skills:</strong> identity resolution, deduplication, metadata handling, and source integration.</li>
        </ul>
      </details>
    </article>

    <article class="project-card">
      <div class="project-card__header">
        <div>
          <p class="cv-kicker">Reproducible data platforms</p>
          <h3>Automated Scientific Catalog Construction</h3>
          <p class="project-card__subtitle">ETL pipelines for validated, publishable datasets.</p>
        </div>
        <div class="project-card__visual">ETL flow</div>
      </div>
      <p>Designed reproducible pipelines for extracting, validating, enriching, and publishing structured datasets from heterogeneous observational sources. The work maps closely to modern analytics engineering: define data contracts, automate transformations, validate output quality, preserve metadata, and make results reproducible for downstream users. The scientific setting increased the rigor because published datasets must remain auditable long after the original analysis is complete.</p>
      <div class="project-badges">
        <span>ETL</span><span>Pipeline automation</span><span>Metadata</span><span>Validation</span><span>Reproducibility</span><span>Database design</span>
      </div>
      <details>
        <summary>Read more</summary>
        <ul>
          <li><strong>Challenge:</strong> turn heterogeneous raw inputs into durable, auditable data products.</li>
          <li><strong>Contribution:</strong> pipeline design, validation rules, metadata handling, and publication workflows.</li>
          <li><strong>Industry analogues:</strong> enterprise ETL, analytics platforms, data governance, and data products.</li>
        </ul>
      </details>
    </article>

    <article class="project-card">
      <div class="project-card__header">
        <div>
          <p class="cv-kicker">Visual analytics</p>
          <h3>Scientific Visualization</h3>
          <p class="project-card__subtitle">Visual tools for exploration, communication, and uncertainty.</p>
        </div>
        <div class="project-card__visual">Visual analytics</div>
      </div>
      <p>Created visual analytics tools for exploring high-dimensional scientific datasets and communicating uncertainty to technical and non-technical audiences. The work involved exploratory analysis, statistical storytelling, plots that reveal model behavior, and visual checks that make data quality problems visible. This is the same communication layer needed in product analytics, BI dashboards, model monitoring, and executive reporting. The emphasis was on helping people make better decisions from complex data, not just producing attractive figures.</p>
      <div class="project-badges">
        <span>EDA</span><span>Visualization</span><span>Data storytelling</span><span>Uncertainty</span><span>Dashboards</span><span>Communication</span>
      </div>
      <details>
        <summary>Read more</summary>
        <ul>
          <li><strong>Challenge:</strong> make complex models and uncertainty understandable without oversimplifying them.</li>
          <li><strong>Contribution:</strong> exploratory visualization, communication assets, and visual model diagnostics.</li>
          <li><strong>Industry analogues:</strong> executive dashboards, BI visualization, product analytics, and model reporting.</li>
        </ul>
      </details>
    </article>

    <article class="project-card">
      <div class="project-card__header">
        <div>
          <p class="cv-kicker">Reusable software</p>
          <h3>Open-Source Scientific Software</h3>
          <p class="project-card__subtitle">Reusable libraries, documented pipelines, and collaborative tools.</p>
        </div>
        <div class="project-card__visual">Library</div>
      </div>
      <p>Designed and contributed to reusable scientific software supporting statistical analysis, machine learning workflows, reproducible research, and collaboration. Projects include HEARSAY, AEGIS, PINNACLE, PROPERIMAGE, GriSPy, and related repositories. Across these tools, the emphasis was repeatability, documentation, automation, package structure, and long-term usability by other researchers. This is directly comparable to internal ML platforms, data science libraries, and developer tools.</p>
      <div class="project-badges">
        <span>Python</span><span>Open source</span><span>Documentation</span><span>Testing</span><span>Reusable libraries</span><span>ML workflows</span>
      </div>
      <details>
        <summary>Read more</summary>
        <ul>
          <li><strong>Challenge:</strong> make research code reusable, documented, and robust enough for collaborators.</li>
          <li><strong>Contribution:</strong> library design, automation, documentation, software packaging, and reproducibility practices.</li>
          <li><strong>Transferable skills:</strong> platform thinking, developer experience, maintainability, and collaborative engineering.</li>
        </ul>
      </details>
    </article>

    <article class="project-card">
      <div class="project-card__header">
        <div>
          <p class="cv-kicker">Probabilistic modeling under uncertainty</p>
          <h3>OTHER: Modeling Contact Between Civilizations</h3>
          <p class="project-card__subtitle">Simulation-based reasoning for rare events with extreme uncertainty.</p>
        </div>
        <div class="project-card__visual">Simulation</div>
      </div>
      <p>Developed and simulated a computational model for estimating probabilities of causal contact between civilizations in the Milky Way. The model was intentionally simple and interpretable, organized around three core questions: how rare civilizations are, how long they last, and how far their signals can be detected. The project combined astronomy, anthropology, biology, philosophy, architecture, and theology/religion, requiring probabilistic reasoning and clear communication across disciplines.</p>
      <div class="project-highlights">
        <span>3-parameter interpretable model</span>
        <span>Interdisciplinary research team</span>
        <span>Simulation-based public communication</span>
      </div>
      <div class="project-badges">
        <span>Monte Carlo</span><span>Simulation</span><span>Probabilistic modeling</span><span>Uncertainty</span><span>Communication</span><span>Interdisciplinary work</span>
      </div>
      <details>
        <summary>Read more</summary>
        <ul>
          <li><strong>Challenge:</strong> reason quantitatively about a rare-event problem where direct empirical data are extremely limited.</li>
          <li><strong>Contribution:</strong> computational modeling, simulations, interdisciplinary framing, and public explanation of uncertainty.</li>
          <li><strong>Team:</strong> included Marcelo Lares, José Funes, Luciana Gramajo, and broader OTHER contributors.</li>
          <li><strong>Industry analogues:</strong> scenario modeling, strategic risk analysis, simulation under uncertainty, and decision support with scarce data.</li>
        </ul>
      </details>
    </article>

    <article class="project-card">
      <div class="project-card__header">
        <div>
          <p class="cv-kicker">Technical enablement</p>
          <h3>University Data Science Program</h3>
          <p class="project-card__subtitle">Curriculum design, teaching, and mentoring in data science.</p>
        </div>
        <div class="project-card__visual">Learning path</div>
      </div>
      <p>Designed and taught undergraduate and graduate material in statistics, machine learning, pattern recognition, scientific computing, and data science over a 20-year teaching career. The work includes original course material, technical mentoring, research supervision, and translating formal mathematical ideas into practical modeling workflows. For industry, this demonstrates AI enablement: developing talent, explaining complex systems, and raising the technical quality of teams. It also shows long-term practice communicating trade-offs, uncertainty, and modeling assumptions clearly.</p>
      <div class="project-badges">
        <span>Teaching</span><span>Mentoring</span><span>Statistics</span><span>Machine learning</span><span>Curriculum design</span><span>Technical leadership</span>
      </div>
      <details>
        <summary>Read more</summary>
        <ul>
          <li><strong>Challenge:</strong> teach rigorous statistical and computational thinking across different skill levels.</li>
          <li><strong>Contribution:</strong> curriculum design, graduate supervision, technical mentoring, and course leadership.</li>
          <li><strong>Industry analogues:</strong> internal training, AI enablement, developer education, and technical leadership.</li>
        </ul>
      </details>
    </article>
  </div>
</section>

<section class="cv-section" id="skills">
  <h2>Cross-Cutting Skills</h2>
  <div class="tag-cloud">
    <span>Supervised learning</span>
    <span>Unsupervised learning</span>
    <span>Regression</span>
    <span>Classification</span>
    <span>Feature engineering</span>
    <span>Model evaluation</span>
    <span>Uncertainty estimation</span>
    <span>ETL pipelines</span>
    <span>Large-scale processing</span>
    <span>Data validation</span>
    <span>Computer vision</span>
    <span>Image segmentation</span>
    <span>Bayesian inference</span>
    <span>Monte Carlo methods</span>
    <span>Hypothesis testing</span>
    <span>Spatial statistics</span>
    <span>Reproducible research</span>
    <span>Technical mentoring</span>
  </div>
</section>
