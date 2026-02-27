<h1 align="center">BACHELOR OF SCIENCE IN MECHATRONICS ENGINEERING</h1>

## ROBOTICS 2: LABORATORY 1
### Python and Robotics Toolbox Mechanical Manipulator Simulation

---

### Objectives
By the end of this laboratory experiment, students will be able to:
1. Formulate the kinematic model of an assigned mechanical manipulator using Denavit-Hartenberg (D-H) parameters and graphical methods.
2. Develop and execute forward kinematics simulations using both Python and MATLAB (Robotics Toolbox by Peter Corke).
3. Validate simulation accuracy by cross-verifying computational outputs from both software environments across multiple joint variable test points.
4. Present technical findings effectively through professional documentation and a structured oral defense.

---

### Materials
1. Laptops
2. Visual Studio Code (VSCode) with Python extension
3. MATLAB with Robotics Toolbox by Peter Corke
  
---

<h2 align="center">6-DOF Spherical Manipulator Figure 1</h2>

### Kinematic Diagram
<div align="center">
  <img src="https://github.com/user-attachments/assets/99f05635-bfa0-4232-a9b1-e1fed063d9d4" width="800" alt="Centered 6-DOF Kinematic Diagram">
</div>


<div align="center">
  <img src="https://github.com/user-attachments/assets/254a2fed-db4b-4518-bcf3-de5bd5c8d077" width="800" alt="Centered 6-DOF Kinematic Diagram">
</div>

### D-H Parametric Table and Homogeneous Transformation Matrix
<div align="center">
  <img src="https://github.com/user-attachments/assets/97635406-1806-4f3c-9ee7-545324ed489e" width="800" alt="Centered 6-DOF Kinematic Diagram">
<h2 align="center">D-H Parametric Figure 1.1</h2>
  <img src="https://github.com/user-attachments/assets/a5af2490-e019-46ea-adf2-cff80ad8745a" width="800" alt="Centered 6-DOF Kinematic Diagram">
<h2 align="center">D-H Parametric Figure 1.2</h2>
</div>

### Matlab and Python Comparison

Test Point 1:<br>
&nbsp;&nbsp;&nbsp;&nbsp;a1 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a2 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a3 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a4 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a5 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a6 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;T1 = 0<br>
&nbsp;&nbsp;&nbsp;&nbsp;T2 = 0<br>
&nbsp;&nbsp;&nbsp;&nbsp;T4 = 0<br>
&nbsp;&nbsp;&nbsp;&nbsp;T5 = 0<br>
&nbsp;&nbsp;&nbsp;&nbsp;T6 = 0<br>
&nbsp;&nbsp;&nbsp;&nbsp;d3 = 0<br>

<div align="center">
  <table width="100%" style="table-layout: fixed; border-collapse: collapse;">
    <tr>
      <td width="50%" align="center" valign="bottom" style="padding-bottom: 10px;">
        <b>MATLAB Simulation</b>
      </td>
      <td width="50%" align="center" valign="bottom" style="padding-bottom: 10px;">
        <b>Python Implementation</b>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/ed6cc432-ea0e-4638-ad99-89096002cd36" width="100%">
      </td>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/9511fb61-9a51-47d6-bd44-a619e3b350a5" width="100%">
      </td>
    </tr>
  </table>
</div>

Test Point 2:<br>
&nbsp;&nbsp;&nbsp;&nbsp;a1 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a2 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a3 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a4 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a5 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a6 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;T1 = 10<br>
&nbsp;&nbsp;&nbsp;&nbsp;T2 = 20<br>
&nbsp;&nbsp;&nbsp;&nbsp;T4 = 30<br>
&nbsp;&nbsp;&nbsp;&nbsp;T5 = 40<br>
&nbsp;&nbsp;&nbsp;&nbsp;T6 = 60<br>
&nbsp;&nbsp;&nbsp;&nbsp;d3 = 2<br>

<div align="center">
  <table width="100%" style="table-layout: fixed; border-collapse: collapse;">
    <tr>
      <td width="50%" align="center" valign="bottom" style="padding-bottom: 10px;">
        <b>MATLAB Simulation</b>
      </td>
      <td width="50%" align="center" valign="bottom" style="padding-bottom: 10px;">
        <b>Python Implementation</b>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="3-DOF_Spherical_Manipulator_Figure1_Photos/MATLAB/1st_Test_Point.png" width="100%">
      </td>
      <td align="center">
        <img src="3-DOF_Spherical_Manipulator_Figure1_Photos/python/1st_Test_Point.png" width="100%">
      </td>
    </tr>
  </table>
</div>

Test Point 3:<br>
&nbsp;&nbsp;&nbsp;&nbsp;a1 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a2 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a3 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a4 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a5 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a6 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;T1 = 15<br>
&nbsp;&nbsp;&nbsp;&nbsp;T2 = 30<br>
&nbsp;&nbsp;&nbsp;&nbsp;T4 = 45<br>
&nbsp;&nbsp;&nbsp;&nbsp;T5 = 60<br>
&nbsp;&nbsp;&nbsp;&nbsp;T6 = 90<br>
&nbsp;&nbsp;&nbsp;&nbsp;d3 = 4<br>

<div align="center">
  <table width="100%" style="table-layout: fixed; border-collapse: collapse;">
    <tr>
      <td width="50%" align="center" valign="bottom" style="padding-bottom: 10px;">
        <b>MATLAB Simulation</b>
      </td>
      <td width="50%" align="center" valign="bottom" style="padding-bottom: 10px;">
        <b>Python Implementation</b>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="3-DOF_Spherical_Manipulator_Figure1_Photos/MATLAB/1st_Test_Point.png" width="100%">
      </td>
      <td align="center">
        <img src="3-DOF_Spherical_Manipulator_Figure1_Photos/python/1st_Test_Point.png" width="100%">
      </td>
    </tr>
  </table>
</div>

Test Point 4:<br>
&nbsp;&nbsp;&nbsp;&nbsp;a1 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a2 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a3 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a4 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a5 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a6 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;T1 = 30<br>
&nbsp;&nbsp;&nbsp;&nbsp;T2 = 150<br>
&nbsp;&nbsp;&nbsp;&nbsp;T4 = 120<br>
&nbsp;&nbsp;&nbsp;&nbsp;T5 = 90<br>
&nbsp;&nbsp;&nbsp;&nbsp;T6 = 70<br>
&nbsp;&nbsp;&nbsp;&nbsp;d3 = 6<br>

<div align="center">
  <table width="100%" style="table-layout: fixed; border-collapse: collapse;">
    <tr>
      <td width="50%" align="center" valign="bottom" style="padding-bottom: 10px;">
        <b>MATLAB Simulation</b>
      </td>
      <td width="50%" align="center" valign="bottom" style="padding-bottom: 10px;">
        <b>Python Implementation</b>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="3-DOF_Spherical_Manipulator_Figure1_Photos/MATLAB/1st_Test_Point.png" width="100%">
      </td>
      <td align="center">
        <img src="3-DOF_Spherical_Manipulator_Figure1_Photos/python/1st_Test_Point.png" width="100%">
      </td>
    </tr>
  </table>
</div>

Test Point 5:<br>
&nbsp;&nbsp;&nbsp;&nbsp;a1 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a2 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a3 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a4 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a5 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;a6 = 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;T1 = 120<br>
&nbsp;&nbsp;&nbsp;&nbsp;T2 = 90<br>
&nbsp;&nbsp;&nbsp;&nbsp;T4 = 90<br>
&nbsp;&nbsp;&nbsp;&nbsp;T5 = 60<br>
&nbsp;&nbsp;&nbsp;&nbsp;T6 = 30<br>
&nbsp;&nbsp;&nbsp;&nbsp;d3 = 8<br>

<div align="center">
  <table width="100%" style="table-layout: fixed; border-collapse: collapse;">
    <tr>
      <td width="50%" align="center" valign="bottom" style="padding-bottom: 10px;">
        <b>MATLAB Simulation</b>
      </td>
      <td width="50%" align="center" valign="bottom" style="padding-bottom: 10px;">
        <b>Python Implementation</b>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="3-DOF_Spherical_Manipulator_Figure1_Photos/MATLAB/1st_Test_Point.png" width="100%">
      </td>
      <td align="center">
        <img src="3-DOF_Spherical_Manipulator_Figure1_Photos/python/1st_Test_Point.png" width="100%">
      </td>
    </tr>
  </table>
</div>


