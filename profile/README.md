<table>
  <tr>
    <td width="220" align="center">
      <img src="https://raw.githubusercontent.com/Team-ROBIT/.github/main/images/robit_logo_kw.png" alt="RO:BIT" width="200" />
    </td>
    <td>
      <h2>RO:BIT Intelligence Robot Team</h2>
      Perception · Navigation · Manipulation — from custom hardware to VLM-driven autonomy.<br/>
      <sub>Kwangwoon University · Korea's first robot sports game team · Since 2006</sub><br/><br/>
      <a href="https://team-robit.github.io/"><img src="https://img.shields.io/badge/Website-741F2C?style=flat&logo=googlechrome&logoColor=white"/></a>
      <a href="https://www.youtube.com/@ROBIT_KOREA"><img src="https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white"/></a>
      <a href="https://www.instagram.com/robit_korea_official/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=instagram&logoColor=white"/></a>
      <a href="https://www.linkedin.com/company/kwrobit/"><img src="https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?style=flat&logo=linkedin-white&logoColor=fff"/></a>
      <a href="https://github.com/ROBIT-KOR-teamHumanoid/"><img src="https://img.shields.io/badge/Humanoid_Team-2F6FED?style=flat&logo=github&logoColor=white"/></a>
    </td>
  </tr>
</table>

<br/>

> RO:BIT is a student self-governing body of Kwangwoon University. We design, machine, build, and program robots for
> rescue, defense, and robot sports — then take them to competitions and run robot events so more students
> fall in love with robotics.

---

## 🏆 2026 Season

<table>
  <tr>
    <td align="center" width="33%">
      <img src="https://raw.githubusercontent.com/Team-ROBIT/.github/main/images/2026_rescue.png" alt="RoboCup Rescue 2026" height="320" /><br/>
      <h4>RoboCup Rescue 2026</h4>
      <sub>Eclipse · ✅ Qualification passed</sub>
    </td>
    <td align="center" width="33%">
      <img src="https://raw.githubusercontent.com/Team-ROBIT/.github/main/images/2026_defense.png" alt="Defense Robot Competition 2026" height="320" /><br/>
      <h4>Defense Robot Competition 2026</h4>
      <sub>Eclipse · 🥇 1st place</sub>
    </td>
    <td align="center" width="33%">
      <a href="https://team-robit.github.io/irc-mani-web/"><img src="https://raw.githubusercontent.com/Team-ROBIT/.github/main/images/2026_safelab_card.png" alt="SAFE LAB" height="320" /></a><br/>
      <h4>SAFE LAB</h4>
      <sub>🥈 2nd place · Intelligent Robot Competition 2026 (Manipulator)<br/>Self-built 7-DOF manipulator</sub>
    </td>
  </tr>
</table>

---

## 🦾 SAFE LAB — spec sheet

<div align="center">
<a href="https://youtu.be/OLy96QEyY1U"><img src="https://raw.githubusercontent.com/Team-ROBIT/.github/main/images/safelab_demo.jpg" alt="SAFE LAB demo video — 2026 Intelligent Robot Competition, Manipulator" width="720" /></a>
<br/>
<b>An autonomous robot that finds and clears the hazards people leave behind in a lab.</b><br/>
<a href="https://youtu.be/OLy96QEyY1U">▶ Watch the demo video</a> · <a href="https://team-robit.github.io/irc-mani-web/">Build story →</a>
</div>

<br/>

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>Hardware <sub>(designed, machined &amp; assembled in-house)</sub></h4>
      <table>
        <tr><td><b>Arm</b></td><td>7-DOF, QDD (Quasi-Direct Drive)</td></tr>
        <tr><td><b>Payload</b></td><td>3 kg rated · 5 kg max</td></tr>
        <tr><td><b>Reach / Weight</b></td><td>77 cm · 7.3 kg</td></tr>
        <tr><td><b>Control</b></td><td>Custom low-level motor controller</td></tr>
        <tr><td><b>Sensing</b></td><td>RGB-D · thermal · wrist camera</td></tr>
        <tr><td><b>Compute</b></td><td>Jetson AGX + RTX 4060 laptop</td></tr>
      </table>
    </td>
    <td width="50%" valign="top">
      <h4>Task success rates</h4>
      <table>
        <tr><td>Hazard identification</td><td align="right"><b>98.5%</b></td></tr>
        <tr><td>Soldering-iron unplug</td><td align="right"><b>92%</b></td></tr>
        <tr><td>Battery removal</td><td align="right"><b>92%</b></td></tr>
        <tr><td>Workbench tidy-up</td><td align="right"><b>80%</b></td></tr>
        <tr><td>Power-strip off</td><td align="right"><b>70%</b></td></tr>
      </table>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td align="center" width="25%"><b>VLM</b><br/><sub>Qwen3-VL-4B<br/>task planning</sub></td>
    <td align="center" width="25%"><b>Imitation learning</b><br/><sub>ACT on LeRobot<br/>skill execution</sub></td>
    <td align="center" width="25%"><b>Vision</b><br/><sub>YOLO11n · SAM 2.1<br/>RGB-D + thermal</sub></td>
    <td align="center" width="25%"><b>Motion planner</b><br/><sub>MoveIt 2 · pick_ik<br/>ROS 2 Jazzy</sub></td>
  </tr>
</table>

<sub>Built by Min Jo Kim (controller · imitation learning · planner), Jeong Yoon Woo (arm design · machining), Ki Hong Park (wiring · demo setup · web), Soo Min Song (VLM · vision)</sub>

---

## 🧬 Generations

Every year's robot builds on the last one.

<table>
  <tr>
    <td align="center" width="20%" valign="top">
      <img src="https://raw.githubusercontent.com/Team-ROBIT/.github/main/images/canada.gif" alt="SJBot" height="200" /><br/>
      <h4>SJBot</h4>
      <code>2021</code><br/>
      <sub>First-gen tracked rescue platform with flippers and a camera mast</sub>
    </td>
    <td align="center" width="20%" valign="top">
      <img src="https://raw.githubusercontent.com/Team-ROBIT/.github/main/images/kubo.jpg" alt="KUBO" height="200" /><br/>
      <h4>KUBO</h4>
      <code>2022 – 2023</code><br/>
      <sub>Gripper arm, mast camera, VESC motor drive</sub>
    </td>
    <td align="center" width="20%" valign="top">
      <img src="https://raw.githubusercontent.com/Team-ROBIT/.github/main/images/kuls.jpg" alt="KULS" height="200" /><br/>
      <h4>KULS</h4>
      <code>2024</code><br/>
      <sub>Long-reach arm + LiDAR for autonomous perception</sub>
    </td>
    <td align="center" width="20%" valign="top">
      <img src="https://raw.githubusercontent.com/Team-ROBIT/.github/main/images/2025_luco.png" alt="LUCO" height="200" /><br/>
      <h4>LUCO</h4>
      <code>2025</code><br/>
      <sub>🥇 1st place<br/>Defense Robot Competition 2025</sub>
    </td>
    <td align="center" width="20%" valign="top">
      <img src="https://raw.githubusercontent.com/Team-ROBIT/.github/main/images/2026_rescue.png" alt="Eclipse" height="200" /><br/>
      <h4>Eclipse</h4>
      <code>2026</code><br/>
      <sub>🥇 1st place · Extreme Robot Competition 2025<br/>
      ✅ RoboCup Rescue 2026 · qualification passed<br/>
      🥇 1st place · Defense Robot Competition 2026</sub>
    </td>
  </tr>
</table>

<details>
<summary><b>More robots</b> — Sumo &amp; TurtleBot3 AutoRace</summary>
<br/>
<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://raw.githubusercontent.com/Team-ROBIT/.github/main/images/sumo.gif" alt="Sumo" height="220" /><br/>
      <b>Sumo Robot</b><br/><sub>Fast, light, and merciless in the ring.</sub>
    </td>
    <td align="center" width="50%">
      <img src="https://raw.githubusercontent.com/Team-ROBIT/.github/main/images/t3.gif" alt="TurtleBot3 AutoRace" height="220" /><br/>
      <b>TurtleBot3 AutoRace</b><br/><sub>Autonomous racing · 2023</sub>
    </td>
  </tr>
</table>
</details>

---

## 🧠 What makes them smart

<table>
  <tr>
    <td align="center" width="33%">
      <img src="https://raw.githubusercontent.com/Team-ROBIT/.github/main/images/slam.png" alt="LiDAR SLAM" width="100%" /><br/>
      <b>SLAM &amp; Navigation</b><br/><sub>LiDAR mapping (A-LOAM / LOAM-Livox) and autonomous path planning</sub>
    </td>
    <td align="center" width="33%">
      <img src="https://raw.githubusercontent.com/Team-ROBIT/.github/main/images/vision.png" alt="Vision" height="170" /><br/>
      <b>Computer Vision</b><br/><sub>Scene understanding with RGB-D &amp; thermal cameras</sub>
    </td>
    <td align="center" width="33%">
      <img src="https://raw.githubusercontent.com/Team-ROBIT/.github/main/images/t2.gif" alt="Costmap" height="170" /><br/>
      <b>Autonomous Driving</b><br/><sub>Costmap navigation &amp; mission execution</sub>
    </td>
  </tr>
</table>

---

## 👥 Team

<h4>Currently active</h4>

<table>
  <tr>
    <td align="center" width="16%"><a href="https://github.com/beomsuchoi"><img src="https://github.com/beomsuchoi.png?size=100" width="80"/><br/><b>Beom Su Choi</b></a><br/><sub>19th · 2026 Team Leader<br/>Software</sub></td>
    <td align="center" width="16%"><a href="https://github.com/jammay123"><img src="https://github.com/jammay123.png?size=100" width="80"/><br/><b>Jae Min Ha</b></a><br/><sub>19th<br/>Software</sub></td>
    <td align="center" width="16%"><a href="https://github.com/kinesis19"><img src="https://github.com/kinesis19.png?size=100" width="80"/><br/><b>Ki Hong Park</b></a><br/><sub>19th<br/>Circuit design</sub></td>
    <td align="center" width="16%"><a href="https://github.com/kmj060703"><img src="https://github.com/kmj060703.png?size=100" width="80"/><br/><b>Min Jo Kim</b></a><br/><sub>20th<br/>Software</sub></td>
    <td align="center" width="16%"><a href="https://github.com/mikissm"><img src="https://github.com/mikissm.png?size=100" width="80"/><br/><b>Soo Min Song</b></a><br/><sub>20th<br/>Software</sub></td>
    <td align="center" width="16%"><a href="https://github.com/JeongyoonWoo7"><img src="https://github.com/JeongyoonWoo7.png?size=100" width="80"/><br/><b>Jeong Yoon Woo</b></a><br/><sub>20th<br/>Circuit design</sub></td>
  </tr>
</table>

<details>
<summary><b>Alumni</b> (click to expand)</summary>
<br/>

| Gen | Name | Role | |
|:---:|---|---|:---:|
| 18th | Jae Woong So · *2025 Team Leader* | Hardware design | [GitHub](https://github.com/jaewwong) |
| 18th | Jung Uk Byeon | Circuit design | [GitHub](https://github.com/Jeong042) |
| 18th | Sun Kyoung Lee | Software | [GitHub](https://github.com/lee-sunkyoung) |
| 18th | Ji Hyeon Hong | Software | [GitHub](https://github.com/mkdir-sweetiepie) |
| 17th | Seung Hun Lee · *2024 Team Leader* | Software, Hardware design | [GitHub](https://github.com/Leeseunghun03) |
| 17th | Min Seok Lee | Software, Circuit design | [GitHub](https://github.com/minseokle) |
| 17th | Ji Heng Lee | Hardware design | |
| 17th | Myeong Jin Lee | Software | [GitHub](https://github.com/mjlee111) |
| 16th | In Yeop Beak · *2023 Team Leader* | Software | [GitHub](https://github.com/INYUP-BAEK) |
| 16th | Jong Uk Beak | Hardware design | [GitHub](https://github.com/baekjongwook) |

</details>

<br/>

## 📮 Contact

<table>
  <tr>
    <td width="100" align="center"><img src="https://raw.githubusercontent.com/Team-ROBIT/.github/main/images/kw_unv.jpg" alt="Kwangwoon University" width="80" /></td>
    <td>
      <b>Kwangwoon University</b> · Room 201, Saebitgwan, 20 Gwangun-ro, Nowon-gu, Seoul 01897, Republic of Korea<br/>
      ✉️ GitHub admin — <a href="mailto:robitintelligence@gmail.com">robitintelligence@gmail.com</a>
    </td>
  </tr>
</table>
