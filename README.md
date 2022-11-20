
# Backstop testing in web app

## Requirement

*  [Ghost installed and running](https://ghost.org/docs/install/local/)
*  [BackstopJS](https://github.com/garris/BackstopJS)

### NOTE: Ghost needs to be installed from scratch.
The new version used was Ghost version: 5.23.0 and old version was 3.42.

## Steps to run the test

1. Go to the Ghost-Backstop folder.
3. Execute tests
    ```sh        
    backstop test
    ```
4. Watch regression test running.

## Results

Inside the .\backstop_data\html_report you will find the comparison screenshots and the corresponding report. 

### Ex.
![image](https://user-images.githubusercontent.com/31069035/202921966-8c15d405-36f7-4e11-a203-943a4c493584.png)
