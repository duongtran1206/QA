# EPAM SYSTEMS VIETNAM - COMPLETE AUTOMATION ENGINEER INTERVIEW SCRIPT

<a id="table-of-contents"></a>
## 📌 TABLE OF CONTENTS

* [PART 1: PROFESSIONAL SELF-INTRODUCTION](#part-1-professional-self-introduction)
* [PART 2: DETAILED AUTOMATION EXPERIENCES & REAL PROJECTS (STAR METHOD)](#part-2-detailed-automation-experiences--real-projects-star-method)
    * [QUESTION 1: AI-Driven Automated Test Generation System at LG](#question-1-ai-driven-automated-test-generation-system-at-lg)
    * [QUESTION 2: API Testing in an Embedded Automotive Environment](#question-2-api-testing-in-an-embedded-automotive-environment)
    * [QUESTION 3: Setting Up CI/CD Pipelines and Managing Infrastructure](#question-3-setting-up-cicd-pipelines-and-managing-infrastructure)
* [PART 3: MIDDLE-LEVEL SCENARIO & EXPERIENCE QUESTIONS](#part-3-middle-level-scenario--experience-questions)
    * [M1: Robot Framework Project Clean & Maintainable Structure](#m1-robot-framework-project-clean--maintainable-structure)
    * [M2: Exception Handling Inside Custom Python Libraries](#m2-exception-handling-inside-custom-python-libraries)
    * [M3: Implementing Data-Driven Testing (DDT) in Robot Framework](#m3-implementing-data-driven-testing-ddt-in-robot-framework)
    * [M4: Essential ADB Commands for Everyday Android Automation](#m4-essential-adb-commands-for-everyday-android-automation)
    * [M5: Handling Dynamic UI Elements Without Hardcoded Sleeps](#m5-handling-dynamic-ui-elements-without-hardcoded-sleeps)
    * [M6: Troubleshooting Local Pass vs. Jenkins CI/CD Failures](#m6-troubleshooting-local-pass-vs-jenkins-cicd-failures)
    * [M7: Handling Authentication Tokens in Python API Testing](#m7-handling-authentication-tokens-in-python-api-testing)
    * [M8: Scripted vs. Declarative Jenkins Pipeline Choice](#m8-scripted-vs-declarative-jenkins-pipeline-choice)
    * [M9: Regression Testing Under Extreme Timeline Constraints](#m9-regression-testing-under-extreme-timeline-constraints)
    * [M10: Reopening Existing Bugs vs. Creating New Defect Spinoffs](#m10-reopening-existing-bugs-vs-creating-new-defect-spinoffs)
* [PART 4: 30 CORE QUALITY ASSURANCE QUESTIONS & SMART ANSWERS](#part-4-30-core-quality-assurance-questions--smart-answers)
    * [CORE 1: Difference Between SDLC and STLC](#core-1-difference-between-sdlc-and-stlc)
    * [CORE 2: Verification vs. Validation](#core-2-verification-vs-validation)
    * [CORE 3: Standard Fields in a High-Quality Test Case](#core-3-standard-fields-in-a-high-quality-test-case)
    * [CORE 4: Smoke, Sanity, and Regression Testing Distinctions](#core-4-smoke-sanity-and-regression-testing-distinctions)
    * [CORE 5: Severity vs. Priority with Extreme Examples](#core-5-severity-vs-priority-with-extreme-examples)
    * [CORE 6: Core States in a Standard Bug Life Cycle](#core-6-core-states-in-a-standard-bug-life-cycle)
    * [CORE 7: Black-box, White-box, and Gray-box Testing](#core-7-black-box-white-box-and-gray-box-testing)
    * [CORE 8: Functional vs. Non-functional Testing with Examples](#core-8-functional-vs-non-functional-testing-with-examples)
    * [CORE 9: Essential Components of a Great Bug Report](#core-9-essential-components-of-a-great-bug-report)
    [CORE 10: Test Plan vs. Test Strategy Documents](#core-10-test-plan-vs-test-strategy-documents)
    * [CORE 11: Applying BVA and EP on Age Field (18-60)](#core-11-applying-bva-and-ep-on-age-field-18-60)
    * [CORE 12: Essential Test Cases for a User Login Feature](#core-12-essential-test-cases-for-a-user-login-feature)
    * [CORE 13: Handling 'Cannot Reproduce' Feedback Professionally](#core-13-handling-cannot-reproduce-feedback-professionally)
    * [CORE 14: Determining When to Stop Testing (Exit Criteria)](#core-14-determining-when-to-stop-testing-exit-criteria)
    * [CORE 15: Standard Bug Tracking Workflow Inside Jira](#core-15-standard-bug-tracking-workflow-inside-jira)
    * [CORE 16: Verifying GET, POST, PUT, DELETE and HTTP Status Codes](#core-16-verifying-get-post-put-delete-and-http-status-codes)
    * [CORE 17: Focus Areas and Tools in Responsive Web Testing](#core-17-focus-areas-and-tools-in-responsive-web-testing)
    * [CORE 18: Cross-Browser Testing and Browser Selection Criteria](#core-18-cross-browser-testing-and-browser-selection-criteria)
    * [CORE 19: Handling 200 Unexecuted Test Cases with a 1-Day Deadline](#core-19-handling-200-unexecuted-test-cases-with-a-1-day-deadline)
    * [CORE 20: Test Cases for an E-commerce 'Add to Cart' Feature](#core-20-test-cases-for-an-e-commerce-add-to-cart-feature)
    * [CORE 21: Allocating Testing Scope for 5 PM Build Releasing at 9 AM](#core-21-allocating-testing-scope-for-5-pm-build-releasing-at-9-am)
    * [CORE 22: Retesting vs. Regression Suite Scope Optimization](#core-22-retesting-vs-regression-suite-scope-optimization)
    * [CORE 23: Handling Critical Defects Releasing with PM Approval](#core-23-handling-critical-defects-releasing-with-pm-approval)
    * [CORE 24: Comprehensive Test Scenarios for a File Upload Component](#core-24-comprehensive-test-scenarios-for-a-file-upload-component)
    * [CORE 25: Comprehensive Test Cases for a Website Search Box](#core-25-comprehensive-test-cases-for-a-website-search-box)
    * [CORE 26: Handling Defect Rejections Marked as 'Not a Bug'](#core-26-handling-defect-rejections-marked-as-not-a-bug)
    * [CORE 27: Test Scenario vs. Test Case Allocation Strategies](#core-27-test-scenario-vs-test-case-allocation-strategies)
    * [CORE 28: Testing a Feature with Absolute Zero Documentation](#core-28-testing-a-feature-with-absolute-zero-documentation)
    * [CORE 29: Performance, Load, Stress, and Spike Testing Metrics](#core-29-performance-load-stress-and-spike-testing-metrics)
    * [CORE 30: Processing Severe Security Flaws and Data Exposure](#core-30-processing-severe-security-flaws-and-data-exposure)

---

## <a id="part-1-professional-self-introduction"></a>PART 1: PROFESSIONAL SELF-INTRODUCTION

**[Interviewer]:** *"Hi Duong, welcome to EPAM Systems. To start, could you please introduce yourself and give us a brief overview of your background?"*

**[Your Response]:**
"Hi, thank you for having me today. I am an Automation Engineer with over 3 years of professional experience specializing in Android automation, automotive software testing, custom framework development, and end-to-end CI/CD workflows. 

I graduated from Hanoi University of Science and Technology with a Bachelor's degree in Automation and Control Engineering, which gave me a very strong foundation in systems logic and programming. 

Currently, at LG Electronics, I work as a Software Engineer focusing on building custom Python libraries for Robot Framework to test Android-based In-Vehicle Infotainment (IVI) systems. In this role, I engineered an AI-driven desktop tool utilizing the GitHub Copilot API to automate test script generation, which significantly optimized our execution flow under strict ASPICE quality standards.

Before joining LG, I spent two and a half years at Samsung Vietnam R&D Center. There, I designed and implemented Android automation frameworks using Java with UIAutomator and Python with Selenium, which successfully reduced our overall testing cycles by 30%. I was also responsible for building Python and Bash utilities to optimize our phone farm infrastructure and spent time collaborating with Korean engineers in Gumi, South Korea, to refine Google Build Approval Test workflows.

My core technical stack includes Python, Java, Robot Framework, UIAutomator, Selenium, and Jenkins pipeline scripting. I pride myself on being a proactive problem solver who bridges the gap between pure development and rigorous quality assurance. I am highly motivated to join EPAM to leverage my skills on your large-scale global projects."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

---

## <a id="part-2-detailed-automation-experiences--real-projects-star-method"></a>PART 2: DETAILED AUTOMATION EXPERIENCES & REAL PROJECTS (STAR METHOD)

### <a id="question-1-ai-driven-automated-test-generation-system-at-lg"></a>QUESTION 1: AI-Driven Automated Test Generation System at LG
**[Interviewer]:** *"Can you explain the architecture and workflow of your AI-Driven Automated Test Generation System at LG?"*

**[Your Response]:**
"Certainly. At LG Electronics, writing comprehensive Robot Framework scripts for complex automotive features was highly repetitive and time-consuming. However, we already had a very solid foundation: our team had built a mature library of custom Python test libraries and well-defined automation keywords documented in Markdown instruction files.

To solve this, I designed and developed a lightweight Windows Desktop Application using Python. The workflow is straightforward: a QA engineer inputs the test scenario details—specifically the pre-actions, test steps, and expected outputs—into the tool. Under the hood, the application communicates with the GitHub Copilot API using a secure business API key. I engineered the prompt to include our local Markdown instruction files. This strictly constraints the AI model to only generate test scripts that utilize our pre-defined, valid Robot Framework keywords. 

The tool instantly outputs a structured and syntactically correct `.robot` file. Because automotive systems demand 100% safety and compliance, we enforce a 'human-in-the-loop' workflow where engineers manually review and validate the generated scripts before triggering execution, handling exceptions manually if needed. This solution drastically reduced manual boilerplate coding and allowed our engineers to focus heavily on edge-case design and script code review."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="question-2-api-testing-in-an-embedded-automotive-environment"></a>QUESTION 2: API Testing in an Embedded Automotive Environment
**[Interviewer]:** *"How did you approach API testing in an embedded automotive environment?"*

**[Your Response]:**
"In our automotive IVI projects, we operate on an Android-based operating system running directly on an embedded hardware board. A critical challenge was ensuring flawless real-time communication between this physical hardware and the cloud backend server.

Instead of relying solely on manual tools like Postman, which cannot be easily automated alongside hardware actions, I built custom, lightweight API keywords directly inside our Robot Framework ecosystem using Python's `requests` and `WebSocket` libraries. 

A typical automated test flow involves a keyword sending an ADB command to trigger a physical action on the embedded board, followed immediately by an API keyword that queries the backend server to verify if the correct telemetry data, vehicle state, or log event was synchronized. Wrapping these technical API calls into simple Robot Framework keywords allowed our entire QA team to easily combine UI interactions and API validations within a single test suite, ensuring robust end-to-end integration testing."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="question-3-setting-up-cicd-pipelines-and-managing-infrastructure"></a>QUESTION 3: Setting Up CI/CD Pipelines and Managing Infrastructure
**[Interviewer]:** *"What was your exact role in setting up CI/CD pipelines and managing infrastructure?"*

**[Your Response]:**
"I handled the complete end-to-end configuration of our test execution infrastructure. I did not just maintain existing jobs; I actively configured Jenkins slave nodes from scratch on both Ubuntu and Windows environments. This involved setting up the entire execution runtime, managing environment paths, configuring localized ADB server environments, and ensuring stable physical connectivity to our Android devices and embedded boards.

Furthermore, I wrote the Groovy-based Jenkins Declarative Pipeline scripts. Whenever a developer or automation engineer pushes code updates to our Git repositories, a webhook automatically triggers the pipeline. The script pulls the latest code, scans for an available hardware node, provisions the environment, executes the Robot Framework test suites targeting the specific device UDID, parses the output XML data, and automatically aggregates the results into an HTML report. I also built automated error-handling routines; for instance, if a device is detected as 'unauthorized' or 'offline' via ADB prior to execution, the pipeline instantly bypasses that node and fires an immediate Slack or email notification to the infra team, effectively preventing false-negative test results."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

---

## PART 3: MIDDLE-LEVEL SCENARIO & EXPERIENCE QUESTIONS

### <a id="m1-robot-framework-project-clean--maintainable-structure"></a>M1: Robot Framework Project Clean & Maintainable Structure
**[Interviewer]:** *"How do you structure your Robot Framework project to ensure it is clean and maintainable?"*

**[Your Response]:**
"I follow a multi-layered structure to separate test logic from implementation details:
* **Tests Layer:** Contains `.robot` files with high-level test cases written in a clear, behavior-driven format (Gherkin style).
* **Keywords/Resources Layer:** Contains `.resource` files where I group reusable user keywords.
* **Libraries Layer:** Contains custom Python classes (`.py`) where I write low-level automation logic (like device control or custom API calls) that Robot Framework's native libraries don't support out of the box.
* **Data Layer:** Contains environment configurations, endpoints, variables, or localization files."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m2-exception-handling-inside-custom-python-libraries"></a>M2: Exception Handling Inside Custom Python Libraries
**[Interviewer]:** *"How do you handle exceptions or errors inside your custom Python libraries so that Robot Framework catches them correctly?"*

**[Your Response]:**
"Inside my Python library code, I wrap risky operations in standard `try-except` blocks to handle unexpected system disruptions gracefully. If an error is fatal and should break the execution flow, I explicitly raise an exception—either a standard Python `RuntimeError` or a customized domain exception. Robot Framework automatically catches any unhandled exception raised by an underlying Python library, mapping it natively to mark that specific test keyword step as 'FAILED' with the exact exception message preserved in the execution log logs."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m3-implementing-data-driven-testing-ddt-in-robot-framework"></a>M3: Implementing Data-Driven Testing (DDT) in Robot Framework
**[Interviewer]:** *"How do you implement Data-Driven Testing in Robot Framework? For example, testing the same flow with multiple inputs."*

**[Your Response]:**
"I achieve this cleanly by utilizing the native `Test Template` feature in Robot Framework. I define a standardized core keyword workflow that represents the functional path (for example, `Login With Credentials`), and then under the standard `Test Cases` header, I structure the rows representing data configurations and corresponding expected outcomes. This enables me to iterate the exact same logic repeatedly across distinct input variations (such as valid, invalid, or edge-case string boundaries) without any copy-pasting, preserving clean and DRY code."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m4-essential-adb-commands-for-everyday-android-automation"></a>M4: Essential ADB Commands for Everyday Android Automation
**[Interviewer]:** *"Since you work a lot with Android automation, what are the most common ADB commands you use in your automation scripts?"*

**[Your Response]:**
"I orchestrate device states programmatically within our automation layers using these critical commands:
* `adb devices` to assert endpoint runtime readiness.
* `adb shell am start` and `am force-stop` to programmatically open or reset target application packages.
* `adb shell input tap/text/keyevent` to simulate user physical interactions if dynamic element bindings are unresponsive.
* `adb logcat` to stream runtime diagnostic logs when an assertion fails to attach context to bug tracking systems.
* `adb push/pull` to transfer binary configurations or download execution screenshots from local phone filesystems."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m5-handling-dynamic-ui-elements-without-hardcoded-sleeps"></a>M5: Handling Dynamic UI Elements Without Hardcoded Sleeps
**[Interviewer]:** *"How do you handle dynamic UI elements or elements that take time to load on Android devices?"*

**[Your Response]:**
"I have a strict rule against using static wait times (`Sleep 5s`) because they add major lag and cause flakiness. Instead, I always implement Explicit Waits. In Java/UIAutomator, I handle this via `device.wait(Until.hasObject(...), timeout)`. In Robot Framework, I consistently leverage keywords such as `Wait Until Element Is Visible` or `Wait Until Page Contains Element` bound to an explicit timeout. This configuration guarantees the pipeline progresses the exact millisecond the resource loads."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m6-troubleshooting-local-pass-vs-jenkins-cicd-failures"></a>M6: Troubleshooting Local Pass vs. Jenkins CI/CD Failures
**[Interviewer]:** *"What is your approach when a test script passes on your local machine but fails randomly when running on the Jenkins node?"*

**[Your Response]:**
"This symptom points to environment drift or scheduling resource competition. I isolate it through these steps:
1.  **Analyze Artifact Reports:** I examine the specific Jenkins HTML logs and the failure screenshot to evaluate the exact structural layout rendering.
2.  **Audit Runtime Environment Consistency:** I verify that the Jenkins slave node has identical display parameters, orientations, network throttling boundaries, and matching ADB driver binaries.
3.  **Optimize Wait Tolerances:** If the shared Jenkins runner is heavily utilized, UI thread performance can drop, so I increase the explicit wait timeouts specifically for dynamic actions on the remote side."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m7-handling-authentication-tokens-in-python-api-testing"></a>M7: Handling Authentication Tokens in Python API Testing
**[Interviewer]:** *"When testing REST APIs with Python, how do you handle authentication tokens across multiple test steps?"*

**[Your Response]:**
"I manage state cleanly across my automation components by relying on Python's `requests.Session()` architecture. During the execution setup or authentication routine, the script fires a POST execution to the auth server, extracts the bearer token from the JSON payload, and appends it to the default headers using `session.headers.update({'Authorization': f'Bearer {token}'})`. Using this session object across all subsequent test cases automatically signs requests and minimizes boilerplate token management."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m8-scripted-vs-declarative-jenkins-pipeline-choice"></a>M8: Scripted vs. Declarative Jenkins Pipeline Choice
**[Interviewer]:** *"What is the difference between a Scripted and a Declarative Jenkins Pipeline, and which one do you prefer for automation?"*

**[Your Response]:**
"I prefer using Declarative Pipelines. Declarative pipelines follow a strict structural template enclosed in a `pipeline {}` block, offering excellent readability and built-in error interception sections via `post {}` states. Scripted pipelines use a looser syntax based on pure Groovy logic, which can become complicated and hard to maintain. For automation engineering, Declarative gives exactly what we need: clean execution phases (Pull, Compile, Run, Report) that are highly scannable."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m9-regression-testing-under-extreme-timeline-constraints"></a>M9: Regression Testing Under Extreme Timeline Constraints
**[Interviewer]:** *"How do you perform Regression Testing when a minor bug fix is delivered, and the execution time is very limited?"*

**[Your Response]:**
"I perform Impact Analysis instead of blindly running everything. I check with the development team to isolate the exact source files and modules that were changed. From there, I pull a specific subset of test cases covering those exact features, along with any highly dependent upstream and downstream systems. I finish by running our automated Smoke Test suite to ensure basic core sanity across the system before releasing."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m10-reopening-existing-bugs-vs-creating-new-defect-spinoffs"></a>M10: Reopening Existing Bugs vs. Creating New Defect Spinoffs
**[Interviewer]:** *"What do you do if a developer marks your bug as 'Fixed', but during retesting, you find the bug is still there, or it caused a new bug?"*

**[Your Response]:**
"If the original error behavior is still reproducible, I do not create a new issue. I Reopen the original Jira ticket, attach new execution logs and screenshots, and log a comment showing that the fix failed on the latest build. However, if the original defect is fully resolved but the code change broke a separate, unrelated feature, I Close the original task to confirm that specific fix and open a brand-new bug ticket for the new regression, adding a link between both tickets for clear traceability."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

---

## PART 4: 30 CORE QUALITY ASSURANCE QUESTIONS & SMART ANSWERS

### <a id="core-1-difference-between-sdlc-and-stlc"></a>CORE 1: Difference Between SDLC and STLC
**[Answer]:** "SDLC stands for Software Development Life Cycle, which covers the entire end-to-end process of planning, designing, building, testing, and deploying software. STLC stands for Software Testing Life Cycle, which is a specific phase that runs parallel inside the SDLC. STLC focuses purely on testing activities like requirement analysis, test planning, test design, test execution, and test closure to detect defects as early as possible."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-2-verification-vs-validation"></a>CORE 2: Verification vs. Validation
**[Answer]:** "Verification answers the question: 'Are we building the product right?'. It is a static testing approach that evaluates documents, requirements, and code architecture without executing the application. Validation answers the question: 'Are we building the right product?'. It is a dynamic testing approach where we execute the actual software to ensure it behaves according to user expectations."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-3-standard-fields-in-a-high-quality-test-case"></a>CORE 3: Standard Fields in a High-Quality Test Case
**[Answer]:** "A standard test case must include: Test Case ID, Title, Pre-conditions, Test Steps, Test Data, Expected Result, Actual Result, and Status (Pass/Fail/Blocked). To ensure maximum traceability, we also add fields like Priority, Severity, Module Name, Author, and Post-conditions."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-4-smoke-sanity-and-regression-testing-distinctions"></a>CORE 4: Smoke, Sanity, and Regression Testing Distinctions
**[Answer]:** "Smoke testing is performed on initial builds to verify that the critical, core functionalities work and the build is stable enough for deeper testing; it is broad and shallow. Sanity testing is a quick, focused evaluation performed after a specific bug fix or minor change to ensure that component works; it is narrow and deep. Regression testing is comprehensive testing executed after any code change to guarantee that new modifications have not broken existing, stable functionalities."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-5-severity-vs-priority-with-extreme-examples"></a>CORE 5: Severity vs. Priority with Extreme Examples
**[Answer]:** "Severity indicates the technical impact of a defect on the system's functionality, while Priority defines the business urgency of fixing that defect. A High Severity / Low Priority example is a complete application crash that only occurs when a user inputs 10,000 characters into an optional field; it is a fatal bug but highly unlikely to happen. A Low Severity / High Priority example is a misspelled company logo on the homepage; it does not break any system logic, but it severely damages corporate branding and must be fixed immediately."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-6-core-states-in-a-standard-bug-life-cycle"></a>CORE 6: Core States in a Standard Bug Life Cycle
**[Answer]:** "The lifecycle begins at 'New' when a bug is found. It transitions to 'Assigned' to a developer, then 'Open' during active investigation. Once fixed, the status becomes 'Fixed'. The QA engineer then moves it to 'Retest'. If the fix passes, it is marked as 'Verified' and finally 'Closed'. If the fix fails, it is 'Reopened'. Secondary states include 'Deferred', 'Rejected', and 'Cannot Reproduce'."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-7-black-box-white-box-and-gray-box-testing"></a>CORE 7: Black-box, White-box, and Gray-box Testing
**[Answer]:** "Black-box testing focuses entirely on software inputs and outputs based on requirements, with zero knowledge of the internal code structure. White-box testing examines the internal code logic, branches, loops, and statements, usually performed by developers via unit tests. Gray-box testing is a combination of both, where the tester has partial access to internal structures, such as databases or system architecture."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-8-functional-vs-non-functional-testing-with-examples"></a>CORE 8: Functional vs. Non-functional Testing with Examples
**[Answer]:** "Functional testing validates what the system does. Examples include checking the user login flow, verifying payment gateway integrations, and processing search queries. Non-functional testing validates how well the system operates. Examples include Performance testing under high traffic, Security penetration testing, and UI Usability testing."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-9-essential-components-of-a-great-bug-report"></a>CORE 9: Essential Components of a Great Bug Report
**[Answer]:** "A great bug report must be clear and actionable. It requires a concise Title, detailed Steps to Reproduce, the Expected vs. Actual results, complete Environment details (OS, Browser version, hardware specs), Severity and Priority levels, and concrete evidence such as screenshots, screen recordings, or ADB/crash logs."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-10-test-plan-vs-test-strategy-documents"></a>CORE 10: Test Plan vs. Test Strategy Documents
**[Answer]:** "A Test Strategy is a static, high-level document defined at the organizational or program level that dictates the overall testing philosophy and guidelines. A Test Plan is a dynamic, project-level document derived from the Test Strategy that describes the specific scope, schedule, target resources, risks, and deliverables for a particular release."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-11-applying-bva-and-ep-on-age-field-18-60"></a>CORE 11: Applying BVA and EP on Age Field (18-60)
**[Answer]:** "Using Boundary Value Analysis (BVA), I will test the exact boundary values: 17 (invalid low), 18 (valid low boundary), 19 (valid), 59 (valid), 60 (valid high boundary), and 61 (invalid high). Using Equivalence Partitioning (EP), I split inputs into distinct classes: Valid range (18 to 60), Invalid Low (<18), Invalid High (>60), and Invalid Formats such as alphabetic characters, symbols, negative values, and empty inputs."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-12-essential-test-cases-for-a-user-login-feature"></a>CORE 12: Essential Test Cases for a User Login Feature
**[Answer]:** "Beyond basic valid/invalid credentials, I must test: SQL Injection and XSS security vulnerability payloads, Brute Force protection (ensuring account lockout after N failed attempts), case-sensitivity of passwords, Remember Me cookies, Session Timeout duration, concurrent logins from multiple devices, Social Media OAuth logins, Forgot Password workflows, and UI responsiveness."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-13-handling-cannot-reproduce-feedback-professionally"></a>CORE 13: Handling 'Cannot Reproduce' Feedback Professionally
**[Answer]:** "I will remain collaborative. First, I will review my bug report to verify that the test steps, environment variables, and specific test data are completely clear. If the developer still faces issues, I will share execution recordings or system logs. If necessary, I will jump on a quick call to debug the issue together on their local environment. If it is an isolated environmental issue, I will document those specific conditions."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-14-determining-when-to-stop-testing-exit-criteria"></a>CORE 14: Determining When to Stop Testing (Exit Criteria)
**[Answer]:** "Testing is an infinite process, so we stop when predefined Exit Criteria are fully satisfied. These criteria typically include: the complete execution of all high-priority test cases, target test coverage metrics achieved, the defect density dropping below an acceptable threshold, reaching the project timeline deadline, and getting formal risk acceptance from project stakeholders."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-15-standard-bug-tracking-workflow-inside-jira"></a>CORE 15: Standard Bug Tracking Workflow Inside Jira
**[Answer]:** "I log the defect on Jira with all required steps, environment logs, and evidence. I assign the correct Epic link, component tag, and set the Severity/Priority. The ticket is assigned to the development team. Once marked as 'Fixed', I pull the latest CI build, execute comprehensive manual or automated retests, attach the new verification evidence to the ticket, and formally mark the Jira issue as 'Closed'."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-16-verifying-get-post-put-delete-and-http-status-codes"></a>CORE 16: Verifying GET, POST, PUT, DELETE and HTTP Status Codes
**[Answer]:** "For GET, I test data structure integrity and query/pagination parameters. For POST, I validate request payload constraints and verify duplicate prevention. For PUT, I verify partial/full object mutations and guarantee idempotency. For DELETE, I ensure resource destruction and proper handling of non-existent items. Common status codes include: 200 OK, 201 Created, 204 No Content, 400 Bad Request, 401 Unauthorized, 403 Forbidden, 404 Not Found, 409 Conflict, and 500 Internal Server Error."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-17-focus-areas-and-tools in-responsive-web-testing"></a>CORE 17: Focus Areas and Tools in Responsive Web Testing
**[Answer]:** "I check layout consistency across responsive breakpoints (mobile, tablet, desktop), proper execution of touch events, orientation shifts, typography scaling, image rendering, and menu transformations. I utilize Chrome DevTools for initial layout validation, combined with cloud testing execution engines like BrowserStack and real mobile handsets."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-18-cross-browser-testing-and-browser-selection-criteria"></a>CORE 18: Cross-Browser Testing and Browser Selection Criteria
**[Answer]:** "It is necessary because different browsers utilize separate rendering engines, which can interpret CSS, HTML, and JS in slightly different ways. To avoid guessing, I select target browsers by analyzing real market share data via tools like Google Analytics or StatCounter tailored to our user base. Typically, we support the latest 2 versions of Chrome, Safari, Edge, and Firefox."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-19-handling-200-unexecuted-test-cases-with-a-1-day-deadline"></a>CORE 19: Handling 200 Unexecuted Test Cases with a 1-Day Deadline
**[Answer]:** "I will immediately adopt a Risk-Based Testing strategy. I will identify and execute only critical smoke tests, major end-to-end user transactions, and regression tests on modules directly impacted by recent code changes. I will immediately and transparently report the untested scope and associated risks to the Project Manager so the business can make an informed deployment decision."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-20-test-cases-for-an-e-commerce-add-to-cart-feature"></a>CORE 20: Test Cases for an E-commerce 'Add to Cart' Feature
**[Answer]:** "I will validate: adding varying quantities (boundary limits, negative items, exceeding warehouse stock), adding out-of-stock items, guest checkout cart behavior, cart persistence after user logout and login, automatic price updates when applying promotional codes, real-time cart data synchronization across multiple open browser tabs, and system response time when handling massive cart volumes."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-21-allocating-testing-scope-for-5-pm-build-releasing-at-9-am"></a>CORE 21: Allocating Testing Scope for 5 PM Build Releasing at 9 AM
**[Answer]:** "I will first run a high-level Smoke Test suite to ensure the application doesn't crash immediately. Then, using Impact Analysis, I will isolate the specific modules affected by the latest code check-ins and run targeted regression tests. I will not attempt to rush through everything. Before leaving, I will send a concise status report highlighting what was tested, what was skipped, and the remaining risks."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-22-retesting-vs-regression-suite-scope-optimization"></a>CORE 22: Retesting vs. Regression Suite Scope Optimization
**[Answer]:** "Retesting is a targeted action to verify that a specific reported defect has been fixed successfully. Regression testing checks if the new code changes introduced unintended side effects in unrelated areas. If the suite grows too large, I prioritize tests via Impact Analysis and Risk-Based selection, while actively moving stable, highly repetitive regression cases into our automated execution pipelines."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-23-handling-critical-defects-releasing-with-pm-approval"></a>CORE 23: Handling Critical Defects Releasing with PM Approval
**[Answer]:** "As a QA professional, my role is to expose risks, not block business releases. I will professionally document the exact technical impact, potential user friction, and steps to replicate the bug directly in the Jira ticket or via an official email thread. This ensures a clear audit trail. Once the PM formally acknowledges and signs off on accepting the risk, I will assist in preparing for a hotfix patch post-release."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-24-comprehensive-test-scenarios-for-a-file-upload-component"></a>CORE 24: Comprehensive Test Scenarios for a File Upload Component
**[Answer]:** "I would cover at least 15+ scenarios: Valid and invalid extensions, file size boundary checks (0KB, maximum allowed, oversized files), filenames with special characters or extreme lengths, corrupted files, security scanning using malware signatures (like Eicar files), spoofed MIME types, unexpected network disconnections during upload, multi-file concurrent uploads, and upload cancellation flows."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-25-comprehensive-test-cases-for-a-website-search-box"></a>CORE 25: Comprehensive Test Cases for a Website Search Box
**[Answer]:** "I will test empty submissions, single-character lookups, maximum input lengths, trailing and leading whitespace stripping, injection payloads (SQLi, XSS), alphanumeric and special character inputs, localized language scripts with accents, copy-paste functionality, autocomplete suggestion timing, recent search caching, and performance under heavy database requests."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-26-handling-defect-rejections-marked-as-not-a-bug"></a>CORE 26: Handling Defect Rejections Marked as 'Not a Bug'
**[Answer]:** "I will review the original requirements and user stories. If the specification clearly aligns with my bug report, I will reopen the Jira ticket, link the official documentation, or consult the Business Analyst for confirmation. If the specification is vague, I will organize a quick alignment call with the developer and BA to resolve the ambiguity and update our product documentation."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-27-test-scenario-vs-test-case-allocation-strategies"></a>CORE 27: Test Scenario vs. Test Case Allocation Strategies
**[Answer]:** "A Test Scenario defines 'What to test' at a high level in a single sentence (e.g., Validate user checkout). A Test Case defines 'How to test' with detailed, step-by-step inputs and expected results. I use Test Scenarios in rapid Agile sprints where the team possesses high domain knowledge and speed is essential. I write detailed Test Cases for highly regulated industries (like automotive or finance) and when comprehensive audit trails are required."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-28-testing-a-feature-with-absolute-zero-documentation"></a>CORE 28: Testing a Feature with Absolute Zero Documentation
**[Answer]:** "I will perform Exploratory Testing to understand the feature's structure while executing competitor analysis to identify industry standard workflows. Simultaneously, I will conduct short interviews with the developers and product owner to map out basic flows. I will then explicitly document my testing assumptions and criteria, sharing them with the team for formal alignment before execution."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-29-performance-load-stress-and-spike-testing-metrics"></a>CORE 29: Performance, Load, Stress, and Spike Testing Metrics
**[Answer]:** "Performance testing monitors general system responsiveness under normal conditions. Load testing evaluates behavior under expected peak user volumes. Stress testing pushes the system past its structural limits to discover the breaking point. Spike testing measures stability during sudden, extreme traffic surges and sharp drops. Vital metrics include Throughput (req/s), Error Rates, hardware metrics (CPU/RAM), and 95th or 99th percentile Response Times, which are far more accurate than simple averages."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-30-processing-severe-security-flaws-and-data-exposure"></a>CORE 30: Processing Severe Security Flaws and Data Exposure
**[Answer]:** "This is a critical security vulnerability. I will act ethically and discreetly. I will never capture screenshots containing real production PII (Personally Identifiable Information), and I will never discuss the issue on open or public communication channels. I will replicate the flaw using dummy test accounts, document the issue inside a confidential Jira ticket, and directly alert the Security Lead and Project Manager immediately."

_**[⬆ Back to Table of Contents](#table-of-contents)**_
