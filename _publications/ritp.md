---
title: "A rapid iterative trajectory planning method for automated parking through differential flatness"
collection: publications
category: manuscripts
permalink: /publication/ritp
excerpt: '
<strong style="font-size: 20px;">Graphical abstract</strong>

<img src="/media/ritp/ga1.png" alt="ritp" style="width: 100%; height: auto;">

<strong style="font-size: 20px;">Highlights</strong>

<ul style="font-size: 15px;">

<li>An efficient collision avoidance framework is designed with parallel computing for real-time, collision-free trajectory planning, achieving an average computation time of <strong>0.042–0.065</strong> seconds.</li>

  <li>Differential flatness-based polynomials ensure the integration of the planned paths with the vehicle kinematics model, theoretically ensuring the control feasibility of the trajectories.</li>

  <li>Terminal smoothing constraints are incorporated at gear shifting points, improving the control feasibility of planned trajectories by <strong>8.9%–33.3%</strong> across different scenarios.</li>

</ul>


'
date: 2024-9-23
venue: '<em><a href="https://www.sciencedirect.com/science/article/pii/S0921889024002008">Robotics and Autonomous Systems</a></em>'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0921889024002008'
citation: |
 @article{li2024rapid,
    title={A rapid iterative trajectory planning method for automated parking through differential flatness},
    author={Li, Zhouheng and Xie, Lei and Hu, Cheng and Su, Hongye},
    journal={Robotics and Autonomous Systems},
    pages={104816},
    year={2024},
    publisher={Elsevier}
  }
---



<div style="text-align: center;">
    <p>
  		Authors: <strong>Zhouheng Li</strong><sup>1</sup>, Lei Xie<sup>1</sup>, Cheng Hu<sup>1</sup>, Hongye Su<sup>1</sup>
    </p>
    <p>
      <sup>1</sup>Zhejiang University, Hangzhou, China
    </p>
    <p>
      <a href="https://www.sciencedirect.com/science/article/abs/pii/S0921889024002008">[paper]</a>
    </p>
  <strong style="font-size: 30px;">Abstract</strong>
</div>

<div style="text-align: justify;">
    <p style="font-size: 15px;">
        <span style="display: inline-block; text-indent: 2em;">As autonomous driving continues to advance, automated parking is becoming increasingly essential. However, significant challenges arise when implementing path velocity decomposition (PVD) trajectory planning for automated parking. The primary challenge is ensuring rapid and precise collision-free trajectory planning, which is often in conflict. The secondary challenge involves maintaining sufficient control feasibility of the planned trajectory, particularly at gear shifting points (GSP). <strong>This paper proposes a PVD-based rapid iterative trajectory planning (RITP) method to solve the above challenges. The proposed method effectively balances the necessity for time efficiency and precise collision avoidance through a novel collision avoidance framework. Moreover, it enhances the overall control feasibility of the planned trajectory by incorporating the vehicle kinematics model and including terminal smoothing constraints (TSC) at GSP during path planning.</strong> Specifically, the proposed method leverages differential flatness to ensure the planned path adheres to the vehicle kinematic model. Additionally, it utilizes TSC to maintain curvature continuity at GSP, thereby enhancing the control feasibility of the overall trajectory. The simulation results demonstrate superior time efficiency and tracking errors compared to model-integrated and other iteration-based trajectory planning methods. In the real-world experiment, the proposed method was implemented and validated on a ROS-based vehicle, demonstrating the applicability of the RITP method for real vehicles.</span>
    </p>
</div>

<div style="text-align: center;">
    <img src="../media/ritp/pipeline2.png" alt="racing" style="width: 50%; height: auto;">
    <img src="../media/ritp/pipeline3.png" alt="racing" style="width: 45%; height: auto;">
	<br>
</div>



<div style="text-align: center;">
    <img src="../media/ritp/code1.png" alt="racing" style="width: 35%; height: auto;">
    <img src="../media/ritp/code2.png" alt="racing" style="width: 60%; height: auto;">
	<br>
</div>

<div style="text-align: center;">
  <strong style="font-size: 30px;">Qualitative Results</strong>
</div>

<div style="text-align: center;">
    <img src="../media/ritp/exp1.png" alt="racing" style="width: 100%; height: auto;">
	<br>
</div>



<div style="text-align: center;">
    <img src="../media/ritp/exp2.png" alt="racing" style="width: 100%; height: auto;">
	<br>
</div>





<div style="display: flex; justify-content: center; align-items: flex-start;">
  <div style="display: flex; flex-direction: column; width: 41%;">
    <img src="../media/ritp/exp4.png" alt="racing" style="width: 100%; height: auto; margin-bottom: 10px;">
    <img src="../media/ritp/exp5.png" alt="racing" style="width: 100%; height: auto;">
  </div>
	<div style="width: 47%; margin-left: 20px;">
    <img src="../media/ritp/exp6.png" alt="racing" style="width: 100%; height: auto;">
  </div>
</div>


<div style="text-align: center;">
  <strong style="font-size: 30px;">Qualitative Results</strong>
</div>
<div style="text-align: center;">
    <img src="../media/ritp/exp3.png" alt="racing" style="width: 100%; height: auto;">
	<br>
</div>

<div style="text-align: center;">
    <img src="../media/ritp/exp7.png" alt="racing" style="width: 40%; height: auto;">
    <img src="../media/ritp/exp8.png" alt="racing" style="width: 55%; height: auto;">
	<br>
</div>



<div style="text-align: center;">
    <img src="../media/ritp/exp11.png" alt="racing" style="width: 90%; height: auto;">
	<br>
</div>



<div style="display: flex; justify-content: center; align-items: flex-start;">
  <div style="display: flex; flex-direction: column; width: 41%;">
    <img src="../media/ritp/exp9.png" alt="racing" style="width: 100%; height: auto; margin-bottom: 10px;">
    <img src="../media/ritp/exp10.png" alt="racing" style="width: 100%; height: auto;">
  </div>
	<div style="width: 45%; margin-left: 20px;">
    <img src="../media/ritp/exp12.png" alt="racing" style="width: 100%; height: auto;">
  </div>
</div>







<div style="text-align: center;">
    <img src="../media/ritp/exp13.png" alt="racing" style="width: 40%; height: auto;">
    <img src="../media/ritp/exp14.png" alt="racing" style="width: 40%; height: auto;">
	<br>
</div>



<div style="text-align: center;">
    <img src="../media/ritp/real_parallel.gif" alt="racing" style="width: 50%; height: auto;">
    <img src="../media/ritp/real_reverse.gif" alt="racing" style="width: 41%; height: auto;">
	<br>
</div>



<div style="text-align: center;">
  <strong style="font-size: 30px;">BibTeX</strong>
</div>

```json
@article{li2024rapid,
  title={A rapid iterative trajectory planning method for automated parking through differential flatness},
  author={Li, Zhouheng and Xie, Lei and Hu, Cheng and Su, Hongye},
  journal={Robotics and Autonomous Systems},
  pages={104816},
  year={2024},
  publisher={Elsevier}
}
```

