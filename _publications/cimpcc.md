---
title: "Reduce Lap Time for Autonomous Racing with Curvature-Integrated MPCC Local Trajectory Planning Method"
collection: publications
category: conferences
permalink: /publication/cimpcc
excerpt: '
<strong style="font-size: 20px;">Graphical abstract</strong>

<img src="/media/cimpcc/Graphical_Abstract.jpg" alt="cimpcc" style="width: 100%; height: auto;">

'
date: 2024-07-10
venue: '<em><a href="https://ieee-itsc.org/2024/">27th IEEE International Conference on Intelligent Transportation Systems (ITSC 2024)</a></em>'
citation: 'TBA'
---

<div style="text-align: center;">
    <p>
  		Authors: <strong>Zhouheng Li</strong><sup>1</sup>, Lei Xie<sup>1</sup>, Cheng Hu<sup>1</sup>, Hongye Su<sup>1</sup>
    </p>
    <p>
      <sup>1</sup>Zhejiang University, Hangzhou, China
    </p>
    <p>
      [paper]
    </p>
  <strong style="font-size: 30px;">Abstract</strong>
</div>

<div style="text-align: justify;">
    <p style="font-size: 15px;">
        <span style="display: inline-block; text-indent: 2em;">
            The widespread application of autonomous driving technology has significantly advanced the field of autonomous racing. Model Predictive Contouring Control (MPCC) is a highly effective local trajectory planning method for autonomous racing. However, the traditional MPCC method struggles with racetracks that have significant curvature changes, limiting the performance of the vehicle during autonomous racing. <strong>To address this issue, we propose a curvature-integrated MPCC (CiMPCC) local trajectory planning method for autonomous racing. This method optimizes the velocity of the local trajectory based on the curvature of the racetrack centerline. </strong>strong>The specific implementation involves mapping the curvature of the racetrack centerline to a reference velocity profile, which is then incorporated into the cost function for optimizing the velocity of the local trajectory. This reference velocity profile is created by normalizing and mapping the curvature of the racetrack centerline, thereby ensuring efficient and performance-oriented local trajectory planning in racetracks with significant curvature. The proposed CiMPCC method has been experimented on a self-built 1:10 scale F1TENTH racing vehicle deployed with ROS platform. The experimental results demonstrate that the proposed method achieves outstanding results on a challenging racetrack with sharp curvature, improving the overall lap time by <strong>11.4%</strong>-<strong>12.5%</strong> compared to other autonomous racing trajectory planning methods. Our code is available at <a href="https://github.com/zhouhengli/CiMPCC">https://github.com/zhouhengli/CiMPCC</a>.
        </span>
    </p>
</div>

