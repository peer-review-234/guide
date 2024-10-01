# Note : It will only work from 7:00 am GMT to 9:00 pm GMT, as the servers on which it is running are off during night


# Automated JUnit Test Generator: Innovative Testing Solutions for Java

Welcome to the **Automated JUnit Test Generator** web application! This tool is designed to simplify and automate the process of generating JUnit test cases for Java projects, especially for Spring Boot applications. The generator will create structured and robust test cases, saving you time and effort in writing them manually.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [How to Use](#how-to-use)
  - [Step 1: Initial Input](#step-1-initial-input)
  - [Step 2: Branch & Class Selection](#step-2-branch--class-selection)
  - [Step 3: Confirmation & Test Generation](#step-3-confirmation--test-generation)
- [Notification & Download](#notification--download)
- [License](#license)

---

## Overview

The **Automated JUnit Test Generator** streamlines the creation of JUnit test cases for Spring Boot applications. Simply provide some basic information about your project, and the tool will generate fully functional test classes that follow best practices.

---

## Features

- Automatically generates JUnit test cases based on your Spring Boot project's structure.
- Customizable class selection for generating test cases.
- Provides a download link after few minutes(depends on size of class under test) to retrieve the generated tests.

---

## Prerequisites

Before using this tool, ensure that your Spring Boot project meets the following requirements:

- A valid Spring Boot project hosted in a Git repository.
- Your project must have the **spring-boot-starter-test** dependency defined in its `pom.xml`:

    ```xml
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-test</artifactId>
        <scope>test</scope>
    </dependency>
    ```

---

## How to Use

### Step 1: Initial Input

On the main page of the web application, you will be asked to fill out the following fields:

1. **Name** – Enter your name (Some random name). - optional 
2. **Email** – Enter your email address(Make a temporary anonymous email https://internxt.com/it/temporary-email
). -optional (to recieve the generated tests in email)
3. **Git URL of the project** – Provide the Git URL for the Spring Boot project. Make sure the project includes the `spring-boot-starter-test` dependency.

Click the **"Send"** button to proceed to the next step.

---

### Step 2: Branch & Class Selection

On the following page, you'll need to select the appropriate options:

1. **Branch** – Select the branch of the repository where the JUnit tests should be generated.
2. **Java Version** – Select the version of Java used in the project.
3. **Class Name** – Enter the name of the class (without the `.java` suffix) for which you want to generate tests.

After entering this information, click the **"Send"** button.

---

### Step 3: Confirmation & Test Generation

On the next page, you will be shown the details of the information you provided. Please review these fields carefully:

- JUnit generation requested by
- Project URL
- Branch
- Java Version
- Class Name

Once you've confirmed everything is correct, click the **"Start"** button to initiate the test generation process.

---

## Notification & Download

After you start the process, a notification will appear on the page:

> **If you didn't provide your email, click on the button OPEN RESULT and just wait there for few minutes(depending on the class size) untill you see a button to download your generated tests as a zip file**

> **The generation process has started successfully. You will receive an email with the link to download the project containing the JUnit tests created through this tool. Save the following link to download the generated code: "http://link"**

Make sure to save the link provided to download the generated test cases later.

---

Thank you for using **Automated JUnit Test Generator**! We hope it simplifies your testing process and enhances your productivity in developing robust Java applications.
