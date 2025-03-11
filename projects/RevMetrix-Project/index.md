---
layout: default
course_number: CS402
title: CS Capstone II (RevMetrix Project)
---

--- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---

## CS402: CS Capstone II (RevMetrix Project)

## Spring 2025

--- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---

This is the web page for the RevMetrix Project for CS402 Spring 2024 at [York College of Pennsylvania](http://www.ycp.edu).  All information specifically related to the RevMetrix Project will be posted here.

## Links

* [CS402-Fa24 Website](../../index.html)
* [Syllabus](../../syllabus.html)
* [Schedule](schedule.html)
* [RevMetrix Bowler User Interface Requirements](RevMetrix.html)
* [RevMetrix Project Wiki](https://docs.revmetrix.io)
* [RevMetrix Research](https://research.revmetrix.io)

## RevMetrix Project Description

You will be continuing development of the RevMetrix Project, building upon the accomplishments from the [RevMetrix Project Capstone I (CS400) Team from Fall 2024](https://ycpcs.github.io/cs400-fall2024/projects/RevMetrix-Project).

Your basic goals for the semester are to:

*	Develop a functional RevMetrix **Bowler** User Interface (RMxB-UI) that allows for bowler input to be collected, stored, retrieved, and displayed, utilizing the RevMetrix User Back-End Database (RMxB-DB). The RMxB-UI is a multi-platform phone application.  If the cross-platform development tools support it, a Windows PC version of the RMxB-UI application would also be useful (but not a high priority).  Here is the description for the [RevMetrix Bowler UI Requirements](RevMetrix.html).  It does **NOT** cover the Research User Interface.  And here is a [Prototype Shot Entry Page](RevMetrix-Bowler-UI-Shot-Entry.html) to give you a basic idea of user workflow and functionality.  This is a prototype.  It is, **by no means**, quality code, as it contains the first JS I've ever written - with a lot of help from ChatGPT.  It should however, give you an idea of how the user will enter the results for each shot.

*	Develop a similar functional RevMetrix **Research** User Interface (RmxR-UI) that allows for research data input to be collected, stored, retrieved, and displayed, utilizing the RevMetrix Research Back-End Database (RMxR-DB). The RMxR-UI will be a Windows laptop touchscreen application.  The data stored in the RMxR-DB will be a superset of the data stored in the RMxB-DB.

*	Continue development of the RevMetrix Back-End, including both databases (RMxB-UI and RMxR-UI).

*	Continue development and maintenance of the RevMetrix Wiki, including accurate and detailed instructions on how to set up all of the various development environments, and the various deployments to Digital Ocean.

*	Continue development on the Unity Simulator that is intended to generate animated ball paths that can be used to create known video frame and ball path data for use by Ciclopes.

*	Continue to develop BLE (Bluetooth Low-Energy) connectivity between BLE sensor hardware (3-axis accelerometer, 3-axis gyroscope, ambient light sensor) and a phone application so that the BLE sensor suite can upload live data to a phone application.

TBD based on the Final Team Project Proposal and Design Document

<!-- Commenting out News until it's needed - and the dates could change, anyway
*	Develop automated algorithms for frame-by-frame video processing of the Unity Simulation animation to extract the lane boundaries and ball locations within those boundaries.  Confirm the accuracy of the above algorithms by comparing their output with the Unity Simulation data that generated the frames for the animation.
real video and start to modify, as necessary.

*	Test the applicability of the above Ciclopes algorithms on real bowler video, using similar camera angles as were used on the Unity animations.

*	Develop algorithms that will extract relevant ball path and velocity data from the frame-by-frame analysis of the video, after transforming the lane boundaries and the ball location within each frame into a collection of normalized rectilinear frames.

*	Refine the Ciclopes algorithms above to work reliably with real bowler video.

-->

## RevMetrix Master's Thesis and Presentation

Here are links to the previous research that Professor Hake conducted as part of his MEng Engineering Science Master's Thesis at Penn State Harrisburg:

*	[RevMetrix MEng ESci Thesis](Hake-MEngESci-Masters-Thesis.pdf)

*	[RevMetrix MEng ESci Final Presentation](Hake-MEngESci-Masters-Defense-Presentation.pdf)

## SmartDot Raw Data

Here is a set of raw data from an actual bowling session:

*	A [text version](./resources/Shots(0-19)-Suburban(8-29-10).txt) that contains the EEPROM contents, as well as a CSV extraction of the raw data from those EEPROM contents.

*	An [Excel Spreadsheet](./resources/Shots(0-19)-Suburban(8-29-10).xlsx) that also contains graphs of the extracted raw data for each shot in the session.

*	Here is an an [Updated Excel Spreadsheet](./resources/Shots(0-19)-Suburban(8-29-10)-BallRecord00002-annotated.xlsx) that contains annotations explaining the various components of the raw data.  A second page has been added for Ball Record 00002 that contains the actual 32-bit RTC (Real Time Clock) time stamps for all of the ADXL Pages, the Light Pages, and the SmartDot Events to be sent to the phone application.  The SmartDot Event time stamps could be used to send event signals via BLE in real time (during simulation) from the SmartDot simulator to the phone application.  For Ball Record 00002, all of the individual ADXL and Light sample time stamps have been recalculated based on the actual RTC captures for each page.  You can use these RTC time stamps to generate the exact time stamp values captured in the raw data when running the simulator.  Please look in the **Notes** for the cells for additional information.  

## News
<!-- Commenting out News until it's needed - and the dates could change, anyway

* 5-1-25: Our end-of-semester bowling party will be held on Thursday/Friday 5-15-25/5-16-25 at Suburban Bowlerama starting at TBD.  There will be two hours of bowling, all-you-can eat pizza, pretzels, chips, and soda.  Please let us know if you do NOT plan on attending.

* 5-1-25: Assignment 7 (Final Peer Evals) - The Final Peer Eval forms will be sent out immediately after the final presentation, and are due by Noon, Wednesday, 5-14-25.

* 5-1-25: Assignment 7 (Final Technical Report): due by Noon Thursday, 5-15-25 in your Google Team Folder

* 5-1-25: Milestone 4 Final Presentation: Monday, 5-12-25, 12:45p to 2:45p (during the Final Exam period).

* 4-2-25: Capstone Expo: Thursday, 4-24-25, from 3:00p to 6:00p in KEC (with team photos)

* 4-2-25: Milestone 3 Final Presentation: Wednesday, 4-16-25

-->

* 3-11-25: Milestone 2 Presentation: Wednesday, 4-2-25

* 2-28-25: Mid-semester Peer Evals are two days after your Milestone 1 presentation: by Noon, Friday, 3-14-25.  We will send the peer evaluation forms out via email after your presentation.

* 2-28-25: Milestone 1 Presentation: Wednesday, 3-12-25.

* 2-13-25: The due dates for your project's **draft** and **final** [Detailed Proposal and Design (assign03)](./assign/assign03.html) have been updated.  Check the RevMetrix project page for details.

* 2-5-25: Weekly journal entries start this week, with presentations every Wednesday of the following week

* 1-31-25: All of the Project Milestone assignments and the Final Report assignment have been posted.  Please review the RevMetrix assignment schedule for the assignment descriptions and the due dates.

* 1-31-25: The due dates for your project's [Detailed Proposal and Design (assign03)](./assign/assign03.html) have been posted.  Check the RevMetrix project page for details.

* 1-31-25: The due dates for your [Individual Proposal and Wish List (assign01)](./assign/assign01.html) have been posted.  Check the RevMetrix project page for details.

* 1-27-25: The returning members of the RevMetrix team will give a full demo of the current state of the RevMetrix project on Friday, 1-31-25 for the benefit of the new members of the team, as well as to verify that the project is still in a working state after the semester break.

* 1-27-25: CS402 meets on M-W-F from 12:00p to 1:30p.  The RevMetrix project team will meet on a weekly basis on Wednesdays in KEC 119 for stand ups and assignment and Milestone presentations.  The remaining two weekly class sessions are reserved for team project workdays in KEC 118 and/or KEC119.

* 1-27-25: All students in CS402 will be meeting on the first day of class (Mon, 1-27-25) in KEC 119 to go over our expectations and requirements for the course.

* 1-27-25: There is only one project this semester - all students will be working on some aspect of the RevMetrix project.

* 1-27-25: Welcome back to Kinsley Engineering Center and CS402 - where your academic endeavors converge (and/or collide) with the real world.  And where you will continue to discover just how "pesky" real world clients can be... :-)