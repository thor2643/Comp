# P1 winning competition code
<a href="#sec_contributors"><img src="https://img.shields.io/badge/Authors-Group_176-blue.svg"></a> ![](https://img.shields.io/badge/C++-20-brightgreen.svg) 


As part of a basic introduction to embedded programming using c++, we were to make a mini-project,
that would culminate into a competition against the other 1st semester groups of Robotics. 
The project’s main objective was to sort cans as fast as possible using a Zumo32U4 robot. An illustration of the platform, 
where the sorting process would go about, can be seen in the figure below. As the figure shows, the platform consists of a conveyor belt, where the cans
would be placed, and a few lines that would serve as a guideline for the Zumo32U4 to follow, in order
to be placed on top of an IR-receiver that would turn on the conveyor belt. The cans should be pushed
into Bucket 1 if they were placed far away from the robot and into Bucket 2 if they were placed close
to the robot. In this way, it was possible for the Zumo32U4 to sort the cans using its proximity sensors
that can estimate distances from the brightness levels of the reflected IR-lights. The competition was
divided into two parts, where the first part would test the sorting accuracy of the solution by giving it
10 cans and observing how many were sorted correctly. The second part was testing the efficiency of
the robot by giving it two minutes to correctly sort as many cans as possible. The groups’ tasks were
to write a program that would interact with the various sensors and other hardware components of the
Zumo32U4 needed to complete this competition. The written solution ended up winning the competition🏆

<img src="Sorting-Platform.png" width="540">

## Flowcharts
The following flowcharts illustrates the code flow of the solution. The first flowchart depicts the workflow of the two basic functions that enables the the Zumo to drive straight between two coordinates.
The other flowchart gives an overview of the main program.

<img src="drive_to_coordinate()%20%26%20drive_straight()-drive_straight_comp.png" width="400"><img src="Main.drawio.png" width="400">

## Contributors
This project was developed by group 176 on Aalborg University, Robot Technology at 1st semester.

<section id="sec_contributors">
<table>
  <tr> 
    <td align="center"><a target="_blank" rel="noreferrer noopener" href="https://github.com/signeskuldbol"><img src="https://avatars.githubusercontent.com/u/117270262?v=4" width="100px;" alt=""/><br/><sub><b>Signe Møller-Skuldbøl</b></sub></a></br><a href="gttps://github.com/signeskuldbol" title="">👧</a></td>
    <td align="center"><a target="_blank" rel="noreferrer noopener" href="https://github.com/thor2643"><img src="https://avatars.githubusercontent.com/u/66319719?v=4" width="100px;" alt=""/><br/><sub><b>Thor Iversen</b></sub></a></br><a href="gttps://github.com/thor2643" title="">👨‍🌾</a></td>
    <td align="center"><a target="_blank" rel="noreferrer noopener" href="https://github.com/silasjensen2001"><img src="https://avatars.githubusercontent.com/u/54105795?v=4" width="100px;" alt=""/><br/><sub><b>Silas Jensen</b></sub></a></br><a href="gttps://github.com/silasjensen2001" title="">🤠</a></td>
  <td align="center"><a target="_blank" rel="noreferrer noopener" href="https://github.com/nicopiko"><img src="https://avatars.githubusercontent.com/u/117265455?v=4" width="100px;" alt=""/><br/><sub><b>Nicolai Fosmark Stallknecht</b></sub></a></br><a href="gttps://github.com/nicopiko" title="">🐻</a></td>
  <td align="center"><a target="_blank" rel="noreferrer noopener" href="https://github.com/nikkokid"><img src="https://avatars.githubusercontent.com/u/117265782?v=4" width="100px;" alt=""/><br/><sub><b>Nikolai Buurgaard Jørgensen</b></sub></a></br><a href="gttps://github.com/nikkokid" title="">😎</a></td>

  </tr>
</table>

