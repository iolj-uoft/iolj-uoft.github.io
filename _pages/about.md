---
layout: about
title: about
permalink: /
subtitle: M.Eng, Mechanical & Industrial Engineering · <a href='https://www.utoronto.ca/'>University of Toronto</a>

# profile block is rendered in the page body below so the social icons can sit under the portrait

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # social icons are shown under the portrait instead (see body)

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<div class="profile float-right">
  <img src="{{ 'assets/img/prof_pic.jpg' | relative_url }}" class="img-fluid z-depth-1 rounded" alt="Portrait of Austin (Yang-Chen) Lin">
  <div class="more-info">
    <p>Taoyuan, TW &amp;</p>
    <p>Toronto, ON</p>
  </div>
  <div class="profile-socials">{% social_links %}</div>
</div>

<style>
  .profile-socials {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    width: 100%;
    margin-top: 0.75rem;
    padding: 0 0.5rem;
    font-size: 2rem;
    line-height: 1;
  }
  .profile-socials a {
    color: var(--global-text-color);
    opacity: 0.85;
    transition: color 0.15s ease, opacity 0.15s ease, transform 0.15s ease;
  }
  .profile-socials a:hover {
    color: var(--global-theme-color);
    opacity: 1;
    transform: translateY(-2px);
  }
  .profile-socials img,
  .profile-socials svg {
    width: 2rem;
    height: 2rem;
  }
</style>

I'm Austin (Yang-Chen) Lin, an M.Eng student in Mechanical and Industrial Engineering at the University of Toronto (2024–2026). I work on robotics software: perception, state estimation, sensor fusion, and autonomy for aerial and ground vehicles.

At aUToronto, U of T's self-driving car team, I was a perception software developer on the tracking team. I added yaw-rate estimation to our C++/ROS 2 multi-sensor Kalman-filter tracker and built curve-based trajectory prediction for dynamic obstacles. For my M.Eng capstone, I built a **vision-based drone interceptor** that combines stereo depth, YOLO detection, a delayed-measurement Kalman filter, and proportional navigation guidance in one ROS 2 pipeline. In simulation it reached a 0.99 m terminal miss distance.

Other recent work includes efficient YOLO11 detection for UAV surveillance, gait optimization for an underactuated biped, and RRT\*-based UAV path planning. I'm currently building a 5-inch FPV quadcopter from parts and writing bare-metal STM32 firmware for its IMU and magnetometer.

Before U of T, I earned a B.Sc in Mechanical Engineering at National Chung-Cheng University in Taiwan. There I was a research assistant in the Fuel Cell Lab and led a team to 2nd place in the Chenbro–Syntec industrial automation competition.

Outside engineering, I take on carpentry projects such as building a tote box rack, go kayaking, and weight lifting.

**Interests:** state estimation · sensor fusion · perception · control · path planning · UAVs · autonomous systems
