---
layout: about
title: about
permalink: /
# subtitle: Integrated Ph.D. Candidate, <a href='https://gsai.postech.ac.kr/'>Graduate School of Artificial Intelligence</a>, POSTECH. <a href='mailto:jyjllll1025@postech.ac.kr'>jyjllll1025@postech.ac.kr</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  # more_info: >
  #   <p>Machine Learning Lab</p>
  #   <p>Advisor: Prof. Sangdon Park</p>
  #   <p>POSTECH, Pohang, South Korea</p>

social: true # includes social icons at the bottom of the page

# 아래 두 섹션은 레이아웃이 아니라 이 파일 본문에서 직접 배치합니다.
# (레이아웃은 news -> selected publications 순서를 고정하고 그 뒤에 다른 섹션을 넣을 수 없음)
announcements:
  enabled: false # 본문에서 include 로 직접 렌더링
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

selected_papers: false # 본문에서 include 로 직접 렌더링

latest_posts:
  enabled: false
---

<!-- TODO: 이 아래에 자기소개와 연구 관심사를 직접 작성하세요. -->

I am an Integrated Ph.D. candidate at the Graduate School of Artificial Intelligence, POSTECH, where I am advised by [Prof. Sangdon Park](https://sangdon.github.io) in the Machine Learning Lab. I received my B.S. in Computer Science and Engineering from POSTECH.

My research focuses on reinforcement learning for reliable and scalable physical AI systems. I am particularly interested in developing learning algorithms that enable embodied agents to operate safely and robustly under distribution shifts and unforeseen situations in the real world. Within this broader direction, I study generative policies, such as diffusion and flow-based policies, with an emphasis on preserving diverse and multimodal behaviors during reinforcement learning rather than collapsing to a narrow set of actions. I am also interested in designing reinforcement learning algorithms that remain effective and computationally practical as policy models, datasets, and robotic systems scale up.

<div style="clear: both"></div>

## [News](/news/)

{% include news.liquid limit=true %}

## [Selected Publications](/publications/)

{% include selected_papers.liquid %}

## [Honors and awards](/cv/)
- **POSTECHIAN Fellowship** ($2,000), POSTECH. *September 2025*
- **Second Prize**, 2023 TECHATHON: WAVE, POSTECH. *February 2023*
- **Encouragement Award**, 2021 Undergraduate Group Research Program, POSTECH. *February 2022*
