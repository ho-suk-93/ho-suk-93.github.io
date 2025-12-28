---
layout: default
title: "Home"
permalink: /
description: "Ho Suk personal website"
---

<section id="about" class="section">
  <div class="hero">
    <div class="hero-inner">
      <img class="avatar" src="{{ '/assets/img/H_S_700.jpg' | relative_url }}" alt="Headshot" />
      <div>
        <h1 class="hero-title">Ho Suk</h1>
        <p class="hero-sub">
          Hello World!
        </p>
        <div class="actions">
          <a class="btn primary" href="mailto:{{ site.social.email }}">Email</a>
          <a class="btn" href="{{ site.social.scholar }}">Google Scholar</a>
          <a class="btn" href="https://github.com/{{ site.social.github }}">GitHub</a>
          <a class="btn" href="{{ site.social.linkedin }}">LinkedIn</a>
          <a class="btn" href="{{ '/assets/cv/CV.pdf' | relative_url }}">CV (PDF)</a>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="education" class="section">
  <div class="card">
    <div class="section-title">Education</div>
    <div class="list-item">
      <p class="item-title">Yonsei University - Ph.D. in Integrated Technology</p>
      <p class="item-desc">Seoul, South Korea</p>
      <p class="item-desc">2018.07 - 2025.02</p>
      <p class="item-desc">Dissertation: Autonomous driving to ensure safety under the uncertainty of artificial intelligence</p>
      <p class="item-desc">Advisor: Prof. Shiho Kim</p>
    </div>
    <div class="list-item">
      <p class="item-title">Yonsei University - B.S. in Economics & Computer Sciences (Double Major)</p>
      <p class="item-desc">Seoul, South Korea</p>
      <p class="item-desc">2012.03 - 2017.08</p>
    </div>
  </div>
</section>

<section id="expertise" class="section">
  <div class="card">
    <div class="section-title">Area of Expertise</div>
    <div class="subheading">Main</div>
    <div class="keyword-grid cols-3">
      <div class="keyword-item">Autonomous Driving</div>
      <div class="keyword-item">Autonomous Vehicle & Delivery Robot</div>
      <div class="keyword-item">Time-series Trajectory Prediction</div>
      <div class="keyword-item">Uncertainty Quantification</div>
      <div class="keyword-item">ISO Standard for Vehicle Safety</div>
      <div class="keyword-item">Deep Reinforcement Learning</div>
    </div>
    <div style="height:14px;"></div>
    <div class="subheading">Sub</div>
    <div class="keyword-grid cols-3">
      <div class="keyword-item">Simulation (CARLA, MuJoCo)</div>
      <div class="keyword-item">Positioning & Localization</div>
      <div class="keyword-item">Infrared Thermography</div>
      <div class="keyword-item">VLM for Autonomous Driving</div>
      <div class="keyword-item">Task/Domain Generalization</div>
      <div class="keyword-item">Zero-Knowledge Proof for Vehicle</div> 
    </div>
  </div>
</section>

<section id="research" class="section">
  <div class="card">
    <div class="section-title">Research Interests</div>
    <div class="list-item">
      <p class="item-title">Autonomous Driving / Autonomous Vehicle & Delivery Robot</p>
      <p class="item-desc">Development of three autonomous vehicles to obtain autonomous driving permits from the Ministry of Land, Infrastructure and Transport of South Korea. Demonstration and deployment of autonomous agents in the dynamic real-world environment such as Seoul metropolitan area.</p>
    </div>
    <div class="list-item">
      <p class="item-title">Time-series Trajectory Prediction</p>
      <p class="item-desc">Research on predicting the trajectory of agents, such as vehicles, using GNSS time-series data and images to understand their intentions and provide a basis for system's decision-making.</p>
    </div>
    <div class="list-item">
      <p class="item-title">Uncertainty Quantification</p>
      <p class="item-desc">Research on quantifying the uncertainty in the predictions of deep learning models using methods such as Deep Ensembles, Monte Carlo Dropout, and Deterministic Single Forward Pass, thereby enabling robust decision-making even in ambiguous or unfamiliar data distributions.</p>
    </div>
    <div class="list-item">
      <p class="item-title">ISO Standard for Vehicle Safety (ISO 26262, ISO 21448)</p>
      <p class="item-desc">Research on ISO 26262 Functional Safety, and ISO 21448 SOTIF for ensuring the safety of AI-based autonomous vehicles.</p>
    </div>
    <div class="list-item">
      <p class="item-title">Deep Reinforcement Learning</p>
      <p class="item-desc">Research on training adaptive deep learning agents in environments that are difficult to define with loss functions using reward function-based reinforcement learning, and applying it to the decision systems of autonomous vehicles and autonomous delivery robots.</p>
    </div>
    <div class="list-item">
      <p class="item-title">Simulation (CARLA, MuJoCo)</p>
      <p class="item-desc">Utilization of the Unreal Engine 4-based CARLA simulator for autonomous driving and the MuJoCo simulator for reinforcement learning.</p>
    </div>
    <div class="list-item">
      <p class="item-title">Positioning & Localization</p>
      <p class="item-desc">Utilization of GNSS(Global Navigation Satellite System), RTK(Real-Time Kinematic), and INS(Inertial Navigation System) to achieve accurate positioning in urban areas with severe multipath phenomenon.</p>
    </div>
    <div class="list-item">
      <p class="item-title">Infrared Thermography</p>
      <p class="item-desc">Utilization of LWIR(Long-Wave InfraRed) camera to perceive objects at night, in backlight, and in adverse weather conditions.</p>
    </div>
    <div class="list-item">
      <p class="item-title">VLM for Autonomous Driving</p>
      <p class="item-desc">Research on fine-tuning VLM(Vision-Language Model) using LoRA(Low-Rank Adaptation) and applying VLM to autonomous driving decision-making systems.</p>
    </div>
    <div class="list-item">
      <p class="item-title">Task/Domain Generalization</p>
      <p class="item-desc">Research on Meta Learning, Transfer Learning, and Domain Adaptation for AI model's generalization on various task or domain.</p>
    </div>
    <div class="list-item">
      <p class="item-title">Zero-Knowledge Proof for Vehicle</p>
      <p class="item-desc">Research on ZKP(Zero-Knowledge Proof) for V2X(Vehicle to Everything).</p>
    </div>
  </div>
</section>

<section id="publications" class="section">
  <div class="card">
    <div class="section-title">Publications</div>
    <p class="muted">
      For more information, please see <a href="{{ site.social.scholar }}">Ho Suk's Google Scholar</a>
    </p>
    <div class="list-item">
      <p class="item-title">SFF Rendering-Based Uncertainty Prediction using VisionLLM</p>
      <p class="item-desc">Junyong Lee*, Jeihee Cho*, <b>Ho Suk*</b>, Shiho Kim</p>
      <p class="item-desc">AAAI 2025 Workshop on Planning in the Era of LLMs (LM4Plan) [Workshop]</p>
      <p class="item-desc">2025.03</p>
    </div>
    <div class="list-item">
      <p class="item-title">Uncertainty-Aware Multimodal Trajectory Prediction via a Single Inference from a Single Model</p>
      <p class="item-desc"><b>Ho Suk</b>, Shiho Kim</p>
      <p class="item-desc">Sensors [Journal]</p>
      <p class="item-desc">2025.01</p>
      <p class="item-desc">Selected: <b>Editor's Choice Article</b></p>
    </div>
    <div class="list-item">
      <p class="item-title">Uncertainty as a criterion for SOTIF evaluation of deep learning models in autonomous driving systems</p>
      <p class="item-desc"><b>Ho Suk</b>, Shiho Kim</p>
      <p class="item-desc">NeurIPS 2024 Workshop on Bayesian Decision-making and Uncertainty [Workshop]</p>
      <p class="item-desc">2024.12</p>
    </div>
    <div class="list-item">
      <p class="item-title">Addressing uncertainty challenges for autonomous driving in real-world environments</p>
      <p class="item-desc"><b>Ho Suk*</b>, Yerin Lee*, Taewoo Kim, Shiho Kim</p>
      <p class="item-desc">Advances in Computers [Journal]</p>
      <p class="item-desc">2023.07</p>
    </div>
    <div class="list-item">
      <p class="item-title">Offline reinforcement learning methods for real-world problems</p>
      <p class="item-desc">Taewoo Kim*, <b>Ho Suk*</b>, Shiho Kim</p>
      <p class="item-desc">Advances in Computers [Journal]</p>
      <p class="item-desc">2023.05</p>
    </div>
    <div class="list-item">
      <p class="item-title">Hardware Accelerators for Autonomous Vehicles</p>
      <p class="item-desc">Junekyo Jhung*, <b>Ho Suk*</b>, Hyungbin Park*, Shiho Kim</p>
      <p class="item-desc">Artificial Intelligence and Hardware Accelerators [Book]</p>
      <p class="item-desc">2023.03</p>
    </div>
    <div class="list-item">
      <p class="item-title">Rationale-aware Autonomous Driving Policy utilizing Safety Force Field implemented on CARLA Simulator</p>
      <p class="item-desc"><b>Ho Suk*</b>, Taewoo Kim*, Hyungbin Park, Pamul Yadav, Junyong Lee, Shiho Kim</p>
      <p class="item-desc">NeurIPS 2022 Workshop: Machine Learning for Autonomous Driving [Workshop]</p>
      <p class="item-desc">2022.12</p>
    </div>
    <div class="list-item">
      <p class="item-title">Verification and Validation of Euro NCAP Scenarios based on Simulation of Responsibility-Sensitive Safety (RSS) and Safety Force Field (SFF) Metrics</p>
      <p class="item-desc"><b>Ho Suk*</b>, Junekyo Jhung*, Taewoo Kim, Hyungbin Park, Minseok Won, Cheolhee Yoon, Shiho Kim</p>
      <p class="item-desc">ASAM International Conference 2022 [Conference - Oral]</p>
      <p class="item-desc">2022.11</p>
    </div>
    <div class="list-item">
      <p class="item-title">Learning unsupervised disentangled skill latents to adapt unseen task and morphological modifications</p>
      <p class="item-desc">Taewoo Kim, Pamul Yadav, <b>Ho Suk</b>, Shiho Kim</p>
      <p class="item-desc">Engineering Applications of Artificial Intelligence [Journal]</p>
      <p class="item-desc">2022.11</p>
    </div>
    <div class="list-item">
      <p class="item-title">Self-supervised Learning for Frontal Camera Input based Real-time Localization of Autonomous Vehicles</p>
      <p class="item-desc">Taewoo Kim, <b>Ho Suk</b>, Junekyo Jhung, Hyungbin Park, Shiho Kim</p>
      <p class="item-desc">Summer Annual Conference of IEIE, 2021 [Conference]</p>
      <p class="item-desc">2021.06</p>
    </div>
    <div class="list-item">
      <p class="item-title">Passenger-oriented On-Demand Mobility Services using C-ITS-based Autonomous Vehicles</p>
      <p class="item-desc"><b>Ho Suk</b>, Taewoo Kim, Hyungbin Park, Junekyo Jhung, Jaekwang Cha, Shiho Kim</p>
      <p class="item-desc">Summer Annual Conference of IEIE, 2021 [Conference]</p>
      <p class="item-desc">2021.06</p>
      <p class="item-desc">Awarded: <b>Hyundai Motor Group Paper Award</b></p>
    </div>
  </div>
</section>

<section id="patents" class="section">
  <div class="card">
    <div class="section-title">Patents</div>

    <div class="list-item">
      <p class="item-title">(Patent title)</p>
      <p class="item-desc">(Filing/Registration info, Year)</p>
    </div>
  </div>
</section>

<section id="projects" class="section">
  <div class="card">
    <div class="section-title">Projects</div>

    <div class="list-item">
      <p class="item-title">(Project 1)</p>
      <p class="item-desc">(Role / Outcome / Tech)</p>
    </div>

    <div class="list-item">
      <p class="item-title">(Project 2)</p>
      <p class="item-desc">(Role / Outcome / Tech)</p>
    </div>

    <div class="list-item">
      <p class="item-title">(Project 3)</p>
      <p class="item-desc">(Role / Outcome / Tech)</p>
    </div>
  </div>
</section>

<section id="awards" class="section">
  <div class="card">
    <div class="section-title">Awards</div>

    <div class="list-item">
      <p class="item-title">(Award name)</p>
      <p class="item-desc">(Year, Organization)</p>
    </div>
  </div>
</section>

<section id="academic-services" class="section">
  <div class="card">
    <div class="section-title">Academic Services</div>

    <div class="list-item">
      <p class="item-title">(Reviewer / PC / Workshop role)</p>
      <p class="item-desc">(Venue, Year)</p>
    </div>

    <div class="list-item">
      <p class="item-title">(Reviewer / PC / Workshop role)</p>
      <p class="item-desc">(Venue, Year)</p>
    </div>
  </div>
</section>

<section id="skills" class="section">
  <div class="card">
    <div class="section-title">Skills</div>

    <div class="list-item">
      <p class="item-title">(Category)</p>
      <p class="item-desc">(e.g., Programming / Tools / Platforms)</p>
    </div>
  </div>
</section>

<section id="certificates" class="section">
  <div class="card">
    <div class="section-title">Certificates</div>

    <div class="list-item">
      <p class="item-title">(Certificate name)</p>
      <p class="item-desc">(Year, Issuer)</p>
    </div>
  </div>
</section>

<section id="education-programs" class="section">
  <div class="card">
    <div class="section-title">Education Programs</div>

    <div class="list-item">
      <p class="item-title">(Program name)</p>
      <p class="item-desc">(Year, Provider)</p>
    </div>
  </div>
</section>

<section id="other-services" class="section">
  <div class="card">
    <div class="section-title">Other Services</div>

    <div class="list-item">
      <p class="item-title">(Service item)</p>
      <p class="item-desc">(Year, Detail)</p>
    </div>
  </div>
</section>
