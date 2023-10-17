## Hybrid Framework using selenium

##### Tech Stack
    - pytest
    - pytest-html
    - POM or pafe factory
    - Pytest HTML Report
    - Allure Reports
    - selenium 4.x.x
    - pytest-xdist (Parallel Execution)
    - openpyxl (Data driven testing)    

##### Framework ?

Mainitaing automation files
    - In framework all the files will communicate with each other to perform the specfic task 

##### Goal Automation
    - Re-useability ---> without duplicate code
    - Maintaining ---> git, SVN 

##### Types
    - Built Framework 
        - pytest, Robaot framework, unittest etc
    
    - Custome Framwork
        - data driven 
        - keywork driven 
        - hybrid framework
        - Design framework with cucumber

###### Before choosing frameowrk for your application

    1. Anayalsis Application
    2. Technology
    3. Team Skills
    4. Choose Test Casees

Notes : 
        Before choosing technologies which will be used  to built framwork,
        need to check what are the skills team having, suppose we team have skills
        in java , selenium,  testng so python selenium will be time consuming
        and which results in higher cost and time consuming .
        
Choose Test case for automation

can we do 100% autoamtion?
NO,

    5. Design and implementation of framwork
    6. Execution of framework
    7. Mainiataing (Git, SVN)

------------------------------------------------------------------------

###### Hydrid Framwork:

combination data driven and key driven framework

data-driven 
excel -- > get from excel then we will execute automation scripts -- > report

keyword driven -->

Components:
            . functional library
            . excel sheet to store keywords
            . design out test cases
            . object repo
            . test scripts or driven scripts
--------------------------------------------------------------------------

###### Projects Library requirements:
        - Selenium
        - python
        - pytest
        - pytest-html
        - pytest-xdist
        - openpyxl
        - allure reports

###### Project Structure
        . ProjectName
            - Project Objects
            - Test cases
            - Utilites
            - Test Data
            - Configureation
            - Screenshots
            - Reports
            - run.bat

        . automation scripts
        . capture screenshots 
        . read common values from config file
        . adding for logs
        . parallel test cases execution
        . Data test read code in utilites
        
        . commite code to git 
        . run into jenkis
