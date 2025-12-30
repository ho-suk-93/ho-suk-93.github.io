---
layout: default
title: "Ho Suk's Personal Website"
permalink: /
description: "Ho Suk's Personal Website"
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

<!-- ---------------------------------------------------------------------------------------------------- -->

<section id="education" class="section">
  <div class="card">
    <div class="section-title">● Education</div>
    <div class="list-item">
      <p class="item-title">Yonsei University - Ph.D. in Integrated Technology</p>
      <p class="item-desc">Seoul, South Korea</p>
      <p class="item-desc">2018.07 - 2025.02</p>
      <p class="item-desc">GPA: 4.16/4.3 (4.29/4.5)</p>
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

<!-- ---------------------------------------------------------------------------------------------------- -->

<section id="expertise" class="section">
  <div class="card">
    <div class="section-title">● Area of Expertise</div>
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

<!-- ---------------------------------------------------------------------------------------------------- -->

<section id="research" class="section">
  <div class="card">
    <div class="section-title">● Research Interests</div>
    <div class="list-item">
      <p class="item-title">Autonomous Driving / Autonomous Vehicle & Delivery Robot</p>
      <p class="item-desc">▷ Development of three autonomous vehicles to obtain autonomous driving permits from the Ministry of Land, Infrastructure and Transport of South Korea. Demonstration and deployment of autonomous agents in the dynamic real-world environment such as Seoul metropolitan area.</p>
    </div>
    <div class="list-item">
      <p class="item-title">Time-series Trajectory Prediction</p>
      <p class="item-desc">▷ Research on predicting the trajectory of agents, such as vehicles, using GNSS time-series data and images to understand their intentions and provide a basis for system's decision-making.</p>
    </div>
    <div class="list-item">
      <p class="item-title">Uncertainty Quantification</p>
      <p class="item-desc">▷ Research on quantifying the uncertainty in the predictions of deep learning models using methods such as Deep Ensembles, Monte Carlo Dropout, and Deterministic Single Forward Pass, thereby enabling robust decision-making even in ambiguous or unfamiliar data distributions.</p>
    </div>
    <div class="list-item">
      <p class="item-title">ISO Standard for Vehicle Safety (ISO 26262, ISO 21448)</p>
      <p class="item-desc">▷ Research on ISO 26262 Functional Safety, and ISO 21448 SOTIF for ensuring the safety of AI-based autonomous vehicles.</p>
    </div>
    <div class="list-item">
      <p class="item-title">Deep Reinforcement Learning</p>
      <p class="item-desc">▷ Research on training adaptive deep learning agents in environments that are difficult to define with loss functions using reward function-based reinforcement learning, and applying it to the decision systems of autonomous vehicles and autonomous delivery robots.</p>
    </div>
    <div class="list-item">
      <p class="item-title">Simulation (CARLA, MuJoCo)</p>
      <p class="item-desc">▷ Utilization of the Unreal Engine 4-based CARLA simulator for autonomous driving and the MuJoCo simulator for reinforcement learning.</p>
    </div>
    <div class="list-item">
      <p class="item-title">Positioning & Localization</p>
      <p class="item-desc">▷ Utilization of GNSS(Global Navigation Satellite System), RTK(Real-Time Kinematic), and INS(Inertial Navigation System) to achieve accurate positioning in urban areas with severe multipath phenomenon.</p>
    </div>
    <div class="list-item">
      <p class="item-title">Infrared Thermography</p>
      <p class="item-desc">▷ Utilization of LWIR(Long-Wave InfraRed) camera to perceive objects at night, in backlight, and in adverse weather conditions.</p>
    </div>
    <div class="list-item">
      <p class="item-title">VLM for Autonomous Driving</p>
      <p class="item-desc">▷ Research on fine-tuning VLM(Vision-Language Model) using LoRA(Low-Rank Adaptation) and applying VLM to autonomous driving decision-making systems.</p>
    </div>
    <div class="list-item">
      <p class="item-title">Task/Domain Generalization</p>
      <p class="item-desc">▷ Research on Meta Learning, Transfer Learning, and Domain Adaptation for AI model's generalization on various task or domain.</p>
    </div>
    <div class="list-item">
      <p class="item-title">Zero-Knowledge Proof for Vehicle</p>
      <p class="item-desc">▷ Research on ZKP(Zero-Knowledge Proof) for V2X(Vehicle to Everything).</p>
    </div>
  </div>
</section>

<!-- ---------------------------------------------------------------------------------------------------- -->

<section id="publications" class="section">
  <div class="card">
    <div class="section-title">● Publications</div>
    <p class="muted">
      For more information, please see <a href="{{ site.social.scholar }}">Ho Suk's Google Scholar</a>
    </p>
    <div class="list-item">
      <p class="item-title">SFF Rendering-Based Uncertainty Prediction using VisionLLM</p>
      <p class="item-desc">▷ VLM (Vision Language Model) / LoRA-based Fine Tuning</p>
      <p class="item-desc">Junyong Lee*, Jeihee Cho*, <b>Ho Suk*</b>, Shiho Kim</p>
      <p class="item-desc">AAAI 2025 Workshop on Planning in the Era of LLMs (LM4Plan) [Conference Workshop]</p>
      <p class="item-desc">2025.03</p>
    </div>
    <div class="list-item">
      <p class="item-title">Automotive Software Development Methodologies and Standards</p>      
      <p class="item-desc"><b>[KOR] 자동차 소프트웨어 개발 방법론 및 표준</b></p>
      <p class="item-desc">▷ Agile / DevOps / ISO 26262 / ISO 21448 / AUTOSAR / ASPICE</p>
      <p class="item-desc"><b>Ho Suk</b></p>
      <p class="item-desc">Automotive Software [Book]</p>
      <p class="item-desc">2025.02</p>
    </div>
    <div class="list-item">
      <p class="item-title">Uncertainty-Aware Multimodal Trajectory Prediction via a Single Inference from a Single Model</p>
      <p class="item-desc">▷ Uncertainty Quantification / Trajectory Prediction / Autonomous Driving</p>
      <p class="item-desc"><b>Ho Suk</b>, Shiho Kim</p>
      <p class="item-desc">Sensors [Journal]</p>
      <p class="item-desc">2025.01</p>
      <p class="item-desc">Selected: <b>Editor's Choice Article</b></p>
    </div>
    <div class="list-item">
      <p class="item-title">Uncertainty as a criterion for SOTIF evaluation of deep learning models in autonomous driving systems</p>
      <p class="item-desc">▷ Uncertainty Quantification / Out-of-Distribution Detection / AI Safety / Trustworthy System / Autonomous Driving</p>
      <p class="item-desc"><b>Ho Suk</b>, Shiho Kim</p>
      <p class="item-desc">NeurIPS 2024 Workshop on Bayesian Decision-making and Uncertainty [Conference Workshop]</p>
      <p class="item-desc">2024.12</p>
    </div>
    <div class="list-item">
      <p class="item-title">Addressing uncertainty challenges for autonomous driving in real-world environments</p>
      <p class="item-desc">▷ Uncertainty Quantification / Aleatoric Uncertainty / Epistemic Uncertainty / Driving-related Uncertainty</p>
      <p class="item-desc"><b>Ho Suk*</b>, Yerin Lee*, Taewoo Kim, Shiho Kim</p>
      <p class="item-desc">Advances in Computers [Journal]</p>
      <p class="item-desc">2023.07</p>
    </div>
    <div class="list-item">
      <p class="item-title">Offline reinforcement learning methods for real-world problems</p>
      <p class="item-desc">▷ Reinforcement Learning / Offline Learning / Domain Generalization</p>
      <p class="item-desc">Taewoo Kim*, <b>Ho Suk*</b>, Shiho Kim</p>
      <p class="item-desc">Advances in Computers [Journal]</p>
      <p class="item-desc">2023.05</p>
    </div>
    <div class="list-item">
      <p class="item-title">Hardware Accelerators for Autonomous Vehicles</p>
      <p class="item-desc">▷ Hardware Accelerator / ISO 26262 / ISO 21448 / Autonomous Vehicle</p>
      <p class="item-desc">Junekyo Jhung*, <b>Ho Suk*</b>, Hyungbin Park*, Shiho Kim</p>
      <p class="item-desc">Artificial Intelligence and Hardware Accelerators [Book]</p>
      <p class="item-desc">2023.03</p>
    </div>
    <div class="list-item">
      <p class="item-title">Rationale-aware Autonomous Driving Policy utilizing Safety Force Field implemented on CARLA Simulator</p>
      <p class="item-desc">▷ Trajectory Prediction / Risk Assessment / Driving Policy / CARLA Simulator</p>
      <p class="item-desc"><b>Ho Suk*</b>, Taewoo Kim*, Hyungbin Park, Pamul Yadav, Junyong Lee, Shiho Kim</p>
      <p class="item-desc">NeurIPS 2022 Workshop: Machine Learning for Autonomous Driving [Conference Workshop]</p>
      <p class="item-desc">2022.12</p>
    </div>
    <div class="list-item">
      <p class="item-title">Verification and Validation of Euro NCAP Scenarios based on Simulation of Responsibility-Sensitive Safety (RSS) and Safety Force Field (SFF) Metrics</p>
      <p class="item-desc">▷ Simulation-based Validation / Driving Policy / CARLA Simulator / Scenario Generation</p>
      <p class="item-desc"><b>Ho Suk*</b>, Junekyo Jhung*, Taewoo Kim, Hyungbin Park, Minseok Won, Cheolhee Yoon, Shiho Kim</p>
      <p class="item-desc">ASAM International Conference 2022 [Conference - Oral]</p>
      <p class="item-desc">2022.11</p>
    </div>
    <div class="list-item">
      <p class="item-title">Learning unsupervised disentangled skill latents to adapt unseen task and morphological modifications</p>
      <p class="item-desc">▷ Reinforcement Learning / Variational AutoEncoder / Skill Latent Embedding / Zero-shot Adaptation</p>
      <p class="item-desc">Taewoo Kim, Pamul Yadav, <b>Ho Suk</b>, Shiho Kim</p>
      <p class="item-desc">Engineering Applications of Artificial Intelligence [Journal]</p>
      <p class="item-desc">2022.11</p>
    </div>
    <div class="list-item">
      <p class="item-title">Self-supervised Learning for Frontal Camera Input based Real-time Localization of Autonomous Vehicles</p>
      <p class="item-desc"><b>[KOR] 자율주행차를 위한 전방 카메라 이미지 기반 자가 지도 학습 실시간 위치 추정 기술</b></p>
      <p class="item-desc">▷ Positioning / HD Map</p>
      <p class="item-desc">Taewoo Kim, <b>Ho Suk</b>, Junekyo Jhung, Hyungbin Park, Shiho Kim</p>
      <p class="item-desc">Summer Annual Conference of IEIE, 2021 [Conference]</p>
      <p class="item-desc">2021.06</p>
    </div>
    <div class="list-item">
      <p class="item-title">Passenger-oriented On-Demand Mobility Services using C-ITS-based Autonomous Vehicles</p>
      <p class="item-desc"><b>[KOR] C-ITS 기반 자율주행자동차를 활용한 승객 중심의 온-디맨드 운송 서비스</b></p>
      <p class="item-desc">▷ Demand Responsive Transit / Autonomous Driving</p>
      <p class="item-desc"><b>Ho Suk</b>, Taewoo Kim, Hyungbin Park, Junekyo Jhung, Jaekwang Cha, Shiho Kim</p>
      <p class="item-desc">Summer Annual Conference of IEIE 2021 [Conference]</p>
      <p class="item-desc">2021.06</p>
      <p class="item-desc">Awarded: <b>Hyundai Motor Group Paper Award</b></p>
    </div>
    <div class="list-item">
      <p class="item-title">An open-world novelty generator for authoring reinforcement learning environment of standardized toolkits</p>
      <p class="item-desc">▷ Reinforcement Learning / Environment Generation</p>
      <p class="item-desc">Sangho Lee, Junbeom Park, <b>Ho Suk</b>, Taewoo Kim, Pamul Yadav, Shiho Kim</p>
      <p class="item-desc">International Conference on Multi-disciplinary Trends in Artificial Intelligence 2021 [Conference]</p>
      <p class="item-desc">2021.06</p>
    </div>
    <div class="list-item">
      <p class="item-title">Self-Driving like a Human driver instead of a Robocar: Personalized comfortable driving experience for autonomous vehicles</p>
      <p class="item-desc">▷ Ride Comfort / Manuever Control / Autonomous Driving</p>
      <p class="item-desc">Il Bae, Jaeyoung Moon, Junekyo Jhung, <b>Ho Suk</b>, Taewoo Kim, Hyunbin Park, Jaekwang Cha, Jinhyuk Kim, Dohyun Kim, Shiho Kim</p>
      <p class="item-desc">NeurIPS 2019 Workshop: Machine Learning for Autonomous Driving [Conference Workshop]</p>
      <p class="item-desc">2019.12</p>
    </div>
  </div>
</section>

<!-- ---------------------------------------------------------------------------------------------------- -->

<section id="patents" class="section">
  <div class="card">
    <div class="section-title">● Patents</div>
    <div class="list-item">
      <p class="item-title">TBA</p>
      <p class="item-desc"><b>[KOR] TBA</b></p>
      <p class="item-desc">Application Number: TBA (Korea)</p>
      <p class="item-desc">2026.01</p>
    </div>
    <div class="list-item">
      <p class="item-title">System and Method for Utilizing Deep Ensemble-based AI Model Uncertainty as a SOTIF Metric in Autonomous Driving Systems</p>
      <p class="item-desc"><b>[KOR] 딥 앙상블 기반 AI 모델의 불확실성을 자율주행시스템의 SOTIF 지표로 활용하는 장치 및 방법</b></p>
      <p class="item-desc">Application Number: 10-2025-0182105 (Korea)</p>
      <p class="item-desc">2025.11</p>
    </div>
    <div class="list-item">
      <p class="item-title">Driving Automation Apparatus and Method</p>
      <p class="item-desc"><b>[KOR] 주행 자동화 장치 및 방법</b></p>
      <p class="item-desc">Application Number: 10-2023-0005272 (Korea)</p>
      <p class="item-desc">2023.01</p>
    </div>
  </div>
</section>

<!-- ---------------------------------------------------------------------------------------------------- -->

<section id="projects" class="section">
  <div class="card">
    <div class="section-title">● Projects</div>
    <div class="list-item">
      <p class="item-title">Development of digital innovation elements to enhance the safety of complex autonomous mobility</p>
      <p class="item-desc"><b>[KOR] 복합 자율 모빌리티 안전성 향상을 위한 디지털 혁신요소기술 개발</b></p>
      <p class="item-desc">▷ Research and development of fault tolerant autonomous driving systems based on redundancy and deep learning uncertainty quantification.</p>
      <p class="item-desc">▷ Research and development of zero-knowledge proof-based inter-mobility communication.</p>
      <p class="item-desc">Sponsor: Ministry of Science and ICT of Korea</p>
      <p class="item-desc">2025.04 - In Progress</p>
    </div>
    <div class="list-item">
      <p class="item-title">Development of an AI processor based on reinforcement learning that can adapt to dynamic environmental changes</p>
      <p class="item-desc"><b>[KOR] 동적 환경 변화에 적응 가능한 강화학습 기반의 인공지능 프로세서 개발</b></p>
      <p class="item-desc">▷ Researching the reinforcement learning-based autonomous driving decision algorithms for delivery robots.</p>
      <p class="item-desc">Sponsor: Ministry of Science and ICT of Korea</p>
      <p class="item-desc">2022.04 - 2025.12</p>
    </div>
    <div class="list-item">
      <p class="item-title">Development of technology to verify the effectiveness of service scenarios for responding to autonomous driving-related laws and regulations</p>
      <p class="item-desc"><b>[KOR] 자율주행 관련 법규 및 규제 대응 서비스 시나리오 실효성 검증 기술 개발</b></p>
      <p class="item-desc">▷ Researching the autonomous driving path prediction algorithms based on uncertainty in deep neural network model output.</p>
      <p class="item-desc">Sponsor: Ministry of Science and ICT of Korea</p>
      <p class="item-desc">2021.04 - 2024.12</p>
    </div>
    <div class="list-item">
      <p class="item-title">Development of AI technology that continuously self-improves in response to changing real-world situations</p>
      <p class="item-desc"><b>[KOR] 현실 세계에서 변화하는 상황에 따라 지속적으로 자가 개선하는 인공지능 기술 개발</b></p>
      <p class="item-desc">▷ Researching the reinforcement learning algorithms that adapt to changes in environment and agent form.</p>
      <p class="item-desc">Sponsor: Ministry of Science and ICT of Korea</p>
      <p class="item-desc">2020.04 - 2021.12</p>
    </div>
    <div class="list-item">
      <p class="item-title">Establishment and demonstration of an autonomous car-sharing service linked to the Seoul C-ITS autonomous cooperative driving testbed</p>
      <p class="item-desc"><b>[KOR] 서울 C-ITS 자율협력주행 테스트베드와 연계한 자율주행 카셰어링 공유서비스 구축 및 실증</b></p>
      <p class="item-desc">▷ Connecting the Seoul's C-ITS (Cooperative Intelligent Transport Systems) and autonomous vehicles via 5G.</p>
      <p class="item-desc">▷ Establishing an autonomous car sharing service.</p>
      <p class="item-desc">Sponsor: Seoul Metropolitan Government</p>
      <p class="item-desc">2019.12 - 2021.02</p>
    </div>
    <div class="list-item">
      <p class="item-title">Seoul Smart Mobility Expo public test drive event</p>
      <p class="item-desc"><b>[KOR] 서울 스마트 모빌리티 엑스포 공개시승행사</b></p>
      <p class="item-desc">▷ Verifying the deep learning-based autonomous driving systems in complex scenarios.</p>
      <p class="item-desc">Sponsor: Seoul Metropolitan Government</p>
      <p class="item-desc">2019.10 - 2019.11</p>
    </div>
    <div class="list-item">
      <p class="item-title">Sangam Autonomous Driving Festival public test drive event</p>
      <p class="item-desc"><b>[KOR] 상암 자율주행 페스티벌 공개시승행사</b></p>
      <p class="item-desc">▷ Implementing the multipath-robust INS (Inertial Navigation System) positioning system by integrating IMU (Inertial Measurement Unit) and RTK (Real-Time Kinematic) with GNSS (Global Navigation Satellite System)</p>
      <p class="item-desc">Sponsor: Seoul Metropolitan Government / Ministry of Land, Infrastructure and Transport of Korea / Ministry of Science and ICT of Korea</p>
      <p class="item-desc">2019.05 - 2019.06</p>
    </div>
    <div class="list-item">
      <p class="item-title">Autonomous driving-based car sharing test operation event</p>
      <p class="item-desc"><b>[KOR] 자율주행 기반 카셰어링 시험운영행사</b></p>
      <p class="item-desc">▷ Implementing the GNSS-based autonomous driving call function.</p>
      <p class="item-desc">Sponsor: Ministry of Land, Infrastructure and Transport of Korea / SK Telecom / Socar</p>
      <p class="item-desc">2018.10 - 2018.11</p>
    </div>
    <div class="list-item">
      <p class="item-title">Development of autonomous driving path planning and driving control technology</p>
      <p class="item-desc"><b>[KOR] 자율주행 경로계획 및 주행제어 기술 개발</b></p>
      <p class="item-desc">▷ Developing the deep learning-based autonomous vehicles.</p>
      <p class="item-desc">▷ Implementing the camera-based perception and GNSS (Global Navigation Satellite System)-based positioning systems.</p>
      <p class="item-desc">Sponsor: SK Telecom</p>
      <p class="item-desc">2018.07 - 2020.02</p>
    </div>
  </div>
</section>

<!-- ---------------------------------------------------------------------------------------------------- -->

<section id="awards" class="section">
  <div class="card">
    <div class="section-title">● Awards</div>
    <div class="list-item">
      <p class="item-title">Hyundai Motor Group Paper Award</p>
      <p class="item-desc">Summer Annual Conference of IEIE 2021</p>
      <p class="item-desc">2021.07</p>
    </div>
    <div class="list-item">
      <p class="item-title">Yonsei University President Award Certificate</p>
      <p class="item-desc">Yonsei University Leadership Development Certificate - Platinum Veritas Rank</p>
      <p class="item-desc">2017.01</p>
    </div>
    <div class="list-item">
      <p class="item-title">SERI (Samsung Economic Research Institute) 2nd Prize</p>
      <p class="item-desc">SERI (Samsung Economic Research Institute) EU Academy 6th Course</p>
      <p class="item-desc">2015.05</p>
    </div>
  </div>
</section>

<!-- ---------------------------------------------------------------------------------------------------- -->

<section id="academic-services" class="section">
  <div class="card">
    <div class="section-title">● Academic Services</div>
    <div class="list-item">
      <p class="item-title">ACM WWW 2026 Workshop - Zero-knowledge proof And Blockchain for WEB 4.0: Advancing the Post-quantum And Decentralized era</p>
      <p class="item-desc"><b>Organizer</b></p>
      <p class="item-desc">Dubai, United Arab Emirates</p>
      <p class="item-desc">2026.04</p>
    </div>
    <div class="list-item">
      <p class="item-title">NeurIPS 2023 Workshop - Machine Learning for Autonomous Driving</p>
      <p class="item-desc">Committee</p>
      <p class="item-desc">New Orleans, United States</p>
      <p class="item-desc">2023.12</p>
    </div>
    <div class="list-item">
      <p class="item-title">IEEE IV (Intelligent Vehicles) 2023</p>
      <p class="item-desc">Reviewer</p>
      <p class="item-desc">Anchorage, United States</p>
      <p class="item-desc">2023.06</p>
    </div>
    <div class="list-item">
      <p class="item-title">NeurIPS 2022 Workshop - Machine Learning for Autonomous Driving</p>
      <p class="item-desc">Committee</p>
      <p class="item-desc">New Orleans, United States</p>
      <p class="item-desc">2022.12</p>
    </div>
    <div class="list-item">
      <p class="item-title">IEEE ITSC (Intelligent Transportation Systems Conference) 2022</p>
      <p class="item-desc">Reviewer</p>
      <p class="item-desc">Macau, China</p>
      <p class="item-desc">2022.10</p>
    </div>
    <div class="list-item">
      <p class="item-title">IEEE IV (Intelligent Vehicles) 2022</p>
      <p class="item-desc">Reviewer</p>
      <p class="item-desc">Aachen, Germany</p>
      <p class="item-desc">2022.06</p>
    </div>
    <div class="list-item">
      <p class="item-title">IEEE ICRA (International Conference on Robotics and Automation) 2022 Workshop - Fresh Perspectives on the Future of Autonomous Driving</p>
      <p class="item-desc">Committee</p>
      <p class="item-desc">Philadelphia, United States</p>
      <p class="item-desc">2022.05</p>
    </div>
    <div class="list-item">
      <p class="item-title">NeurIPS 2021 Workshop - Machine Learning for Autonomous Driving</p>
      <p class="item-desc">Committee</p>
      <p class="item-desc">Virtual</p>
      <p class="item-desc">2021.12</p>
    </div>
  </div>
</section>

<!-- ---------------------------------------------------------------------------------------------------- -->

<section id="skills" class="section">
  <div class="card">
    <div class="section-title">● Skills</div>
    <div class="list-item">
      <p class="item-title">Project Planning and Management</p>
      <p class="item-desc">In charge of five national projects of the Ministry of Science and ICT of Korea.</p>
    </div>
    <div class="list-item">
      <p class="item-title">Programming</p>
      <p class="item-desc">Main: Python</p>
      <p class="item-desc">Sub: C/C++, Java</p>
    </div>
    <div class="list-item">
      <p class="item-title">Machine Learning</p>
      <p class="item-desc">Main: PyTorch</p>
      <p class="item-desc">Sub: TensorFlow</p>
    </div>
    <div class="list-item">
      <p class="item-title">Simulation</p>
      <p class="item-desc">Main: CARLA (Unreal Engine 4)</p>
      <p class="item-desc">Sub: MuJoCo</p>
    </div>
  </div>
</section>

<!-- ---------------------------------------------------------------------------------------------------- -->

<section id="certificates" class="section">
  <div class="card">
    <div class="section-title">● Certificates</div>
    <div class="list-item">
      <p class="item-title">TOEIC (Test Of English for International Communication)</p>
      <p class="item-desc">970/990 Points (Top 2%)</p>
      <p class="item-desc">Institution: ETS (Educational Testing Service)</p>
      <p class="item-desc">Issue Number: 039249-0314001501</p>
      <p class="item-desc">2016.08.28</p>
    </div>
    <div class="list-item">
      <p class="item-title">TEPS (Test of English Proficiency developed by Seoul national university)</p>
      <p class="item-desc">462/600 Points (Top 9.52%)</p>
      <p class="item-desc">Institution: Seoul National University</p>
      <p class="item-desc">Issue Number: RNEKQ8510EKFG</p>
      <p class="item-desc">2020.12.06</p>
    </div>    
    <div class="list-item">
      <p class="item-title">Engineer Information Processing</p>
      <p class="item-desc"><b>[KOR] 정보처리기사</b></p>
      <p class="item-desc">Institution: Ministry of Science and ICT of Korea</p>
      <p class="item-desc">Issue Number: 18201050949Z</p>
      <p class="item-desc">2018.05.25</p>
    </div>
    <div class="list-item">
      <p class="item-title">Computer Specialist in Spreadsheet & Database Level-2</p>
      <p class="item-desc"><b>[KOR] 컴퓨터활용능력 2급</b></p>
      <p class="item-desc">Institution: Ministry of Employment and Labor of Korea</p>
      <p class="item-desc">Issue Number: 15-K9-040429</p>
      <p class="item-desc">2015.07.17</p>
    </div>
    <div class="list-item">
      <p class="item-title">MOS (Microsoft Office Specialist) PowerPoint</p>
      <p class="item-desc">Institution: Microsoft</p>
      <p class="item-desc">Issue Number: wnm33-4Svc</p>
      <p class="item-desc">2015.05.23</p>
    </div>
  </div>
</section>

<!-- ---------------------------------------------------------------------------------------------------- -->

<section id="educational-programs" class="section">
  <div class="card">
    <div class="section-title">● Educational Programs</div>
    <div class="list-item">
      <p class="item-title">Samsung - SCSC (Samsung Convergence Software Course)</p>
      <p class="item-desc"><b>[KOR] 삼성 - SCSC</b></p>
      <p class="item-desc">4th Course</p>
      <p class="item-desc">2015.09 - 2017.08</p>
    </div>
    <div class="list-item">
      <p class="item-title">SERI (Samsung Economic Research Institute) - EU Academy</p>
      <p class="item-desc"><b>[KOR] 삼성경제연구소 - EU 아카데미</b></p>
      <p class="item-desc">6th Course (10 Classes)</p>
      <p class="item-desc">2015.03 - 2015.05</p>
      <p class="item-desc">Awarded: <b>2nd Prize</b></p>
    </div>
    <div class="list-item">
      <p class="item-title">Financial Supervisory Service of Korea - FSS Financial Academy</p>
      <p class="item-desc"><b>[KOR] 금융감독원 - FSS 금융아카데미</b></p>
      <p class="item-desc">General Course (5 Classes)</p>
      <p class="item-desc">2015.03 - 2015.05</p>
    </div>
    <div class="list-item">
      <p class="item-title">Bank of Korea - Friday Lecture</p>
      <p class="item-desc"><b>[KOR] 한국은행 - 금요강좌</b></p>
      <p class="item-desc">Basic Economics Course (25 Classes)</p>
      <p class="item-desc">2015.01 - 2016.02</p>
    </div>
  </div>
</section>

<!-- ---------------------------------------------------------------------------------------------------- -->

<section id="other-services" class="section">
  <div class="card">
    <div class="section-title">● Other Services</div>
    <div class="list-item">
      <p class="item-title">Bank of Korea - Economic Education Volunteer Group</p>
      <p class="item-desc"><b>[KOR] 한국은행 - 경제교육 봉사단</b></p>
      <p class="item-desc">2016.03 - 2016.12</p>
    </div>
    <div class="list-item">
      <p class="item-title">Yonsei University - Volunteer Coordinators (Volunteer Club)</p>
      <p class="item-desc"><b>[KOR] 연세대학교 - 학생봉사팀장단</b></p>
      <p class="item-desc"><b>13th Head</b></p>
      <p class="item-desc">100 Hours of Service</p>
      <p class="item-desc">2015.03 - 2016.02</p>
    </div>
    <div class="list-item">
      <p class="item-title">Ministry of Strategy and Finance of Korea - University Student Economic Education Volunteer Group</p>
      <p class="item-desc"><b>[KOR] 기획재정부 - 대학생 경제교육봉사단</b></p>
      <p class="item-desc">47 Hours of Service</p>
      <p class="item-desc">2014.09 - 2014.12</p>
    </div>
  </div>
</section>
