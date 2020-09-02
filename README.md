# Leading-Causes-of-Death-in-the-US

[Live Demo, Please Click Here](http://leading-cause-of-death-in-the-us.s3-website-us-west-1.amazonaws.com/)

![Homepage](/images/Homepage.png)

![Details](/images/Details111.png)

### About

The Data Visualization web application was created using node.js, datamaps.js, d3.js, Javascript, HTML, CSS

The dataset consisting of the leading causes of death in the United States of America for a period between 2005-2019 was pulled from data.gov.

The data was preprocessed using custom Javascript Json scripts and the visualization platform was built to show relevant information.

The UI and functionality is simple, the UI consists of the state map of the US, a drop dop menu to select the year to represent the data for and a highlights column which shows relevant information regarding the highest cause of death, state with the highest death toll, etc.,.

On selecting a particular year and hovering over a particular state, a tooltip displays contextual information about the particular state

On clicking on a each state a summary bar chart showing the number of deaths due to various causes is displayed in a pop up.

---

### Steps to Run:

1. Clone the repository

2. Ensure you have node.js installed in the repo, otherwise install nodeJS using npm. 
To install: `npm install -g http-server`

3. To run:  `http-server & `

This will start the server on http://localhost:8080 from the current working directory.

