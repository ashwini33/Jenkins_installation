# Jenkins_installation
## Installation  Guide for Jenkins on Redhat Linux 8 (AWS EC2)

<p> 
  Jenkins is a self-contained, open source automation server which can be used to automate all sorts of tasks related to building, testing, and delivering or deploying software.
<br>
 Features :- 
<ul>
  
<li> Can be installed through native system packages, Docker, or even run standalone by any machine with a Java Runtime Environment (JRE) installed.
 <li> Highly extensible product whose functionality can be extended through the installation of plugins.
 <li> Used to automate the non-human part of the software development process, with continuous integration and facilitating technical aspects of continuous delivery.
  <li> Supports version control tools, including AccuRev, CVS, Subversion, Git, Mercurial, Perforce, TD/OMS, ClearCase and RTC, and can execute Apache Ant, Apache Maven and sbt based projects as well as arbitrary shell scripts and Windows batch commands
 </ul>
 </p>
 <h2>
  AWS security group configuration for Jenkins : - 
 </h2>
 
 
 |Port | Protocol/Service |
 |-----|------------------|
 |22   |             SSh  |
 |8080 |   Custom TCP     |


