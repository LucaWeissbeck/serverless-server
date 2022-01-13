# Performance Comparison IBM Cloud Code Engine & IBM Virtual Server for VPC

### Description
This repository contains the results of the <b>API-Performancetests</b> conducted as part of my research paper. 
A NodeJS API was deployed on the  IBM Cloud products <b>"Code Engine"</b> and <b>"Virtual Server for VPC"</b>. The services were 
then subjected to an API Performancetest containing a <b>Baseline-, Load-, and Stresstest</b> using <b>Apache JMeter</b>.
The <a href="https://github.com/LucaWeissbeck/serverless-server/tree/main/data">result datasets</a> are contained within this repository as well as a visulations of the results inside the <a href="https://github.com/LucaWeissbeck/serverless-server/blob/main/Results.ipynb">Python Notebook</a>.

### Setup
While this is not necessary and not the purpose of this repository, a `requirements.txt` is inlcuded to install the dependencies used within
`Results.ipynb`.

### Simplified Result Overview
If you are interested in the result of the experiment please take the time to look into the full experiments in `Results.ipynb`. Below is a simplified version of some of the API-Performancetests conducted on the two IBM Cloud offerings.<img width="976" alt="Screenshot 2022-01-13 at 23 41 52" src="https://user-images.githubusercontent.com/62757957/149420653-11a87302-2576-4939-be56-1784497aa9c6.png">
