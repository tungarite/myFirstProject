# myFirstProject

## How to run this Selenium Java project

0. Download and install ChromeDriver from this link: https://chromedriver.chromium.org/

0. Add chromedriver.exe environment variable into PATH. Follow this guide to do so: https://www.browserstack.com/guide/run-selenium-tests-using-selenium-chromedriver#:~:text=Click%20on%20the%20%E2%80%9CEnvironment%20Variables,OK%20to%20save%20the%20configuration.

1. Download and install Eclipse IDE for Java here (Windows link): https://www.eclipse.org/downloads/download.php?file=/technology/epp/downloads/release/2023-09/R/eclipse-java-2023-09-R-win32-x86_64.zip

2. Clone this repository into a folder. By default, the folder name is *myFirstProject*.

3. Open Eclipse IDE, then select *File* -> *Open Projects from File System...*.

4. Locate and select the *myFirstProject* folder, then click *Open*.

5. In Eclipse IDE, select *Help* -> *Eclipse Marketplace...*.

6. Search *TestNG*, then click *Install*.

7. Eclipse will prompt you to trust some sources. Select all sources and trust them.

8. When the installation is complete, Eclipse will prompt you to restart. Click *Restart*.

9. After Eclipse restarts, right-click the project name and select *Build Path* -> *Add Libraries...*.

10. Select *TestNG* and click *Next*, then *Finish*.

11. Download and extract Selenium for Java from this link: https://github.com/SeleniumHQ/selenium/releases/download/selenium-4.13.0/selenium-java-4.13.0.zip

12. In Eclipse IDE, right-click the project name and select *Build Path* -> *Configure Build Path...*.

13. Click *Classpath*, then click *Add External JARs...*.

14. Navigate to the extracted Selenium folder, and select all JAR files in that folder. Click *Open*.

15. Click *Add External JARs...* again, then select all JAR files in the *lib* folder of the extracted Selenium folder. Click *Open*

16. Click *Apply and Close*.

17. Under the project folder, expand *src* -> *(default package)*. There should be a file named *TestNG.java*. Double-click that file to open it.

18. Right click anywhere in the file's content and select *Run as...*  -> *TestNG Test*.

19. See the test result.
