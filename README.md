# Gradle-AsciidoctorJ

Travis Build Status for Master Branch: [![Build Status](https://travis-ci.org/jnorthr/gradle-asciidoctorj.svg?branch=master)](https://travis-ci.org/jnorthr/gradle-asciidoctorj)

A skeleton project for documentation users. Clone includes gradle build tool wrapper and folder structure like maven/gradle

Pre-requisites

1. Working internet connection
2. Installed Git client to copy/clone this repo
3. Ability to use terminal console

Steps  
1. open terminal console

1. change directory \( cd \) into target folder location

2. run this command to create a folder named gradle-asciidoctorj and copy down all the pieces :

   **git clone **[https://github.com/jnorthr/gradle-asciidoctorj.git](https://github.com/jnorthr/gradle-asciidoctorj.git)

3. **cd gradle-asciidoctorj**

4. **./gradlew**

5. after prior step completes, examine **gradle-asciidoctorj** folder to find the **/build/docs** folder with an html file for each asciidoctor file in the **/resources** folder

Note: Have added a gradle task called **copyImages** to copy image files from the **./images** file into **$buildDir/docs/images**

