---
---

# Welcome to H. Eric Tseng's Lab

ETAIC (Emergent Technologies for Autonomy, Intelligence, and Control) Research laboratory focuses on the development of intelligent agents that combine Reinforcement Learning (RL), modern control theory, and game-theoretic human-robot collaboration. Our research explores cutting-edge directions such as Multi-Agent Reinforcement Learning (MARL), closed-loop integration of Large Language Models (LLMs), and trustworthy autonomy in human-cyber-physical systems.

To bridge theory and practice, ETAIC Lab emphasizes experimental validation. Researchers have full access to a comprehensive suite of robotic platforms and testing facilities, including scaled autonomous vehicles, wheeled robots, robotic arms, and UAVs, supported by a 3D motion capture system and both indoor and outdoor netted drone arenas.

ETAIC Lab is led by Professor Hongtei Eric Tseng, a member of the U.S. National Academy of Engineering (NAE) and recipient of seven Henry Ford Technology Awards. Prior to academia, Dr. Tseng spent nearly three decades at Ford Motor Company, where he served as Senior Technical Leader of Controls and Automated Systems. His innovations in vehicle dynamics, advanced powertrain control, and driver-assist technologies have been widely adopted in production vehicles, including the Ford F-150, Lightning, and Super Duty. He holds over 110 U.S. patents, many of which are in commercial use, and has coauthored more than 150 publications, including several authoritative book chapters.

ETAIC Lab welcomes collaborations across AI, robotics, and control engineering to build the next generation of intelligent, robust, and human-compatible autonomous systems.


{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
