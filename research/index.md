---
title: Research
nav:
  order: 1
  tooltip: 연구 분야
---

# <i class="fas fa-lightbulb"></i> Research Overview

## 연구 소개

본 연구실은 복잡한 산업 시스템에서 발생하는 설계, 계획, 운영상의 의사결정 문제를 해결하기 위한 최적화 기법을 연구합니다. 특히 정수최적화와 불확실성 하에서의 순차적 의사결정 방법론을 중심으로, 스마트 생산 시스템, 에너지 시스템, 공급망 관리 분야의 문제를 다루고 있습니다. 구체적인 연구 내용은 아래와 같습니다.

<div style="margin: 30px 0; text-align: center;">
  <img src="/images/research_summary/overview2.png"
       alt="Research Framework Overview"
       style="max-width: 100%; width: 860px; " />
</div>

<p style="text-align: center; color: #6b7280; font-size: 0.95rem; margin: 0.2rem 0 0.8rem;">Interested in our projects and papers? Jump directly to the pages below.</p>

{%
  include link.html
  type="link"
  icon="fas fa-book-open"
  text="View Publications"
  link="/pubs/"
  style="button"
%}
{%
  include link.html
  type="link"
  icon="fas fa-folder-open"
  text="View Projects"
  link="/projects/"
  style="button"
%}
{:.center}

{% include section.html %}

---

<div class="category-divider">
  <i class="fas fa-cogs"></i>
  <div>
    <div class="category-en">Methodology</div>
    <div class="category-ko">방법론</div>
  </div>
</div>

{% include section.html %}

{% capture text %}

### 정수 최적화 이론 및 알고리즘

**Integer Optimization Theory and Algorithms**

현실의 다양한 의사결정 문제는 설비 선택, 작업 순서 결정, 자원 배분과 같은 이산적인(discrete) 선택을 포함하며, 이러한 문제는 정수최적화 모형으로 표현 가능합니다. 본 연구실은 복잡한 의사결정 문제를 효과적으로 해결하기 위한 정수최적화 이론과 알고리즘을 연구합니다. 이론적으로는 **polyhedral analysis, valid inequalities, extended formulations** 등을 통해 문제의 구조를 깊이 있게 이해하고, 이를 바탕으로 보다 강한 최적화 모형을 설계하는 데 관심이 있습니다. 또한 **cutting planes, branch-and-cut, branch-and-price, Benders decomposition** 등의 알고리즘을 활용하여 대규모 최적화 문제를 효과적으로 해결하는 방법을 다룹니다. 이를 통해 수리적으로 엄밀하면서도 실제 산업 문제에 적용 가능한 최적화 방법론을 개발하는 것을 목표로 합니다.

<!-- Many real-world decision-making problems involve discrete choices, such as selecting facilities, determining processing sequences, and allocating limited resources. These problems can often be formulated as integer optimization models. Our research focuses on the theory and algorithms needed to solve such complex decision problems effectively. On the theoretical side, we are interested in polyhedral analysis, valid inequalities, and extended formulations, with the goal of gaining deeper structural insights and developing stronger optimization models. On the algorithmic side, we study approaches such as cutting planes, branch-and-cut, branch-and-price, and Benders decomposition for solving large-scale optimization problems efficiently. Through this line of research, we aim to develop optimization methodologies that are both mathematically rigorous and practically relevant to real industrial applications.-->

{% endcapture %}

{%
  include feature.html
  image="images/research_summary/ip.png"
  text=text
%}

{% include section.html %}

{% capture text %}

### 불확실성 하에서의 순차적 의사결정

**Sequential Decision-Making under Uncertainty**

현실의 많은 산업 문제에서는 수요, 처리시간, 시스템 상태, 외부 환경과 같은 요소들이 불확실하며, 의사결정 또한 시간의 흐름에 따라 순차적으로 이루어집니다. 본 연구실은 이러한 복잡한 의사결정 문제를 효과적으로 해결하기 위한 방법론을 연구합니다. 먼저 **stochastic programming**과 **robust optimization** 방법론을 중심으로 다양한 형태의 불확실성을 수리모형에 반영하고, 이에 대응할 수 있는 해법을 개발하는 데 관심이 있습니다. 또한 **approximate dynamic programming**과 **reinforcement learning**을 활용하여, 시간에 따라 시스템 상태가 변화하는 환경에서 현재의 선택이 미래에 미치는 영향을 고려하는 고차원의 순차적 의사결정 문제를 연구합니다.

<!-- Many real-world industrial problems involve uncertainty in factors such as demand, processing times, system conditions, and external environments, while decisions must often be made sequentially over time. Our research focuses on methodologies for addressing these complex decision-making problems effectively. In particular, we are interested in stochastic programming and robust optimization as frameworks for incorporating various forms of uncertainty into optimization models and developing solution approaches that can address them. We also study high-dimensional sequential decision-making problems using approximate dynamic programming and reinforcement learning, with an emphasis on settings where system states evolve over time and current decisions influence future outcomes.-->

{% endcapture %}

{%
  include feature.html
  image="images/research_summary/sdm.png"
  text=text
  flip=true
%}

{% include section.html %}

<div class="category-divider">
  <i class="fas fa-rocket"></i>
  <div>
    <div class="category-en">Application Area</div>
    <div class="category-ko">응용 분야</div>
  </div>
</div>

{% include section.html %}

{% capture text %}

### 스마트 생산 시스템 운영

**Smart Production Systems**

현대의 제조환경에서는 제품 다양성의 증가, 수요 변동, 생산설비의 유연성 요구 등으로 인해 생산시스템의 설계와 운영이 점점 더 복잡해지고 있습니다. 본 연구실은 이러한 스마트 생산시스템에서 발생하는 다양한 의사결정 문제를 최적화 관점에서 연구합니다. 구체적으로는 반도체 및 디스플레이와 같은 **첨단 제조시스템의 생산계획 및 스케줄링**, **재구성형 제조시스템(Reconfigurable Manufacturing System, RMS)**의 최적 설계 및 운영, 그리고 **데이터 기반 생산용량 추정**과 이를 반영한 운영 최적화 등에 관심이 있습니다. 이를 통해 변화하는 생산 환경에 효과적으로 대응할 수 있으면서도 실제 제조시스템에 적용 가능한 계획 및 운영 방법론을 개발하는 것을 목표로 합니다.

{% endcapture %}

{%
  include feature.html
  image="/images/research_summary/sps.png"
  text=text
%}

{% include section.html %}

{% capture text %}

### 에너지 시스템 최적화

**Energy Systems Optimization**

전기차, 배터리, 에너지 저장장치와 같이 다양한 자원이 상호작용하는 현대 에너지 시스템에서는 운영 효율성과 안정성을 동시에 고려한 의사결정이 중요해지고 있습니다. 본 연구실은 이러한 에너지 시스템의 계획, 운영, 관리와 관련된 최적화 문제를 연구합니다. 특히 Vehicle-to-Grid 기술 및 모바일 충전 로봇을 고려한 **전기차 충전시스템 운영 최적화**, 배터리 효율과 수요의 불확실성을 반영한 **에너지 저장장치(Energy Storage System, ESS)의 충·방전 계획 수립** 등에 관심이 있습니다. 이를 통해 불확실성과 시스템 간 상호작용을 고려하면서도 실제 에너지 시스템에 적용 가능한 효율적이고 안정적인 운영 방법론을 개발하는 것을 목표로 합니다.

{% endcapture %}

{%
  include feature.html
  image="/images/research_summary/grid.png"
  text=text
  flip=true
%}

{% include section.html %}

{% capture text %}

### 공급망 관리

**Supply Chain Management**

생산, 물류, 재고, 유통, 서비스 운영이 유기적으로 연결된 공급망 시스템에서는 다양한 의사결정이 서로 밀접하게 영향을 주고받으며, 제한된 자원과 불확실한 환경 속에서 전체 시스템의 효율성과 유연성을 높이는 것이 중요합니다. 본 연구실은 이러한 공급망의 설계, 계획, 운영과 관련된 최적화 문제를 연구합니다. 구체적으로는 **폐쇄형 공급망(Closed-loop Supply Chain)**의 계획 및 운영 최적화, **자동화된 물류 창고**의 운영 최적화, 그리고 **해운물류 시스템**의 계획 및 운영 최적화 등에 관심이 있습니다. 이를 통해 복잡한 공급망 환경에서 실제 산업 문제에 적용 가능한 분석 및 운영 방법론을 개발하는 것을 목표로 합니다.

{% endcapture %}

{%
  include feature.html
  image="/images/research_summary/scm.png"
  text=text
%}

{% include section.html %}

---

## <i class="fas fa-compass"></i> Explore Our Work

출판 논문 목록과 수행 프로젝트를 확인해보세요.
{:.center}

{%
  include link.html
  type="link"
  icon="fas fa-book-open"
  text="View Publications"
  link="/pubs/"
  style="button"
%}
{%
  include link.html
  type="link"
  icon="fas fa-folder-open"
  text="View Projects"
  link="/projects/"
  style="button"
%}
{:.center}

{% include section.html %}

---

## <i class="fas fa-user-graduate"></i> Prospective Students

### 대학원 진학에 관심 있으신가요?

수리 최적화와 실제 운영 문제의 접점에서 연구를 함께 수행할 **대학원생** 을 모집하고 있습니다. 관심 있으신 분은 편하게 이메일로 문의해 주세요.

We are actively recruiting **Graduate students** who are motivated to tackle challenging problems at the interface of mathematical optimization and real-world operations. If you are interested in joining SPS Lab, please feel free to reach out by email.

{%
  include link.html
  type="email"
  icon=""
  text="younsoo.lee@ssu.ac.kr"
  tooltip="문의 이메일"
  link="younsoo.lee@ssu.ac.kr"
  style="button"
%}
{:.center}
