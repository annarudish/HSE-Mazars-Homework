# HSE. RPA seminar Homework
***
The link to loom video *https://www.loom.com/share/ba656ddf840f406da60d4619fed6f069*
***
This robot is used to automate the process of https://www.semanticscholar.org/ literature collection for the user-defined topic.
Result of the process is an email with attached excel with info about each found article.
***
### The robot functions
* #### Search articles by specific topic on N pages
* #### Get title, author, source, number of citations, article file (if available).

### The */conf.py* is used to configure robot
* #### query - The theme of the articles to search
* #### num_page - The number of pages
* #### receiver - The email of the receiver

### The */main.py* is the main file of robot, which is used to run it.