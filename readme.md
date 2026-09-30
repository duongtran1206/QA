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
    * [CORE 10: Test Plan vs. Test Strategy Documents](#core-10-test-plan-vs-test-strategy-documents)
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
* [PART 5: TEST LEVELS & TEST TYPES](#part-5-test-levels--test-types)
    * [LEVEL 1: What Are Test Levels?](#level-1-what-are-test-levels)
    * [LEVEL 2: Unit Testing](#level-2-unit-testing)
    * [LEVEL 3: Integration Testing](#level-3-integration-testing)
    * [LEVEL 4: System Testing](#level-4-system-testing)
    * [LEVEL 5: Acceptance Testing (UAT) vs. SIT](#level-5-acceptance-testing-uat-vs-sit)
    * [LEVEL 6: Test Pyramid and Shift-Left](#level-6-test-pyramid-and-shift-left)

---

## <a id="part-1-professional-self-introduction"></a>PART 1: PROFESSIONAL SELF-INTRODUCTION

**[Interviewer]:** *"Hi Duong, welcome to EPAM Systems. To start, could you please introduce yourself and give us a brief overview of your background?"*

**[Your Response]:**
> "Hi, thank you for having me today. Let me introduce myself in a few points.
>
> First, my background. I am an Automation Engineer with more than three years of experience in Android automation, automotive software testing, and CI/CD. I graduated from Hanoi University of Science and Technology in Automation and Control Engineering, so I have a strong foundation in programming and system logic.
>
> Second, my current job. At LG Electronics, I work as a Software Engineer. I build custom Python libraries for Robot Framework to test Android-based In-Vehicle Infotainment systems. In this role, I also built an AI-driven desktop tool with the GitHub Copilot API to generate test scripts automatically, following our strict ASPICE quality standards.
>
> Third, my previous job. Before LG, I worked for two and a half years at Samsung Vietnam R&D Center. There I built Android automation frameworks with Java and UIAutomator, and with Python and Selenium, and we reduced the testing cycle by about 30 percent. I also wrote Python and Bash tools for our phone farm, and I worked with Korean engineers in Gumi on the Google Build Approval Test.
>
> My main technical stack is Python, Java, Robot Framework, UIAutomator, Selenium, and Jenkins pipeline scripting.
>
> In short: I am an automation engineer who connects development and quality, and I want to bring that experience to EPAM's global projects."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

---

## <a id="part-2-detailed-automation-experiences--real-projects-star-method"></a>PART 2: DETAILED AUTOMATION EXPERIENCES & REAL PROJECTS (STAR METHOD)

### <a id="question-1-ai-driven-automated-test-generation-system-at-lg"></a>QUESTION 1: AI-Driven Automated Test Generation System at LG
**[Interviewer]:** *"Can you explain the architecture and workflow of your AI-Driven Automated Test Generation System at LG?"*

**[Your Response]:**
> "Sure, let me explain the architecture with a simple story.
>
> **Situation:** At LG, we wrote a lot of Robot Framework scripts for automotive features. The work was very repetitive, so it took a lot of time.
>
> **Task:** I wanted to reduce the manual coding, but the scripts still had to follow our strict ASPICE quality rules.
>
> **Action:** I built a small Windows desktop application with Python. The QA engineer types in the pre-actions, the test steps, and the expected results. The tool sends this to the GitHub Copilot API with a secure business key. In the prompt, I also sent our local Markdown instruction files, so the AI could only use our own valid Robot Framework keywords. The tool then returns a clean and syntactically correct `.robot` file.
>
> **Result:** Our engineers spent much less time writing boilerplate code, and more time on edge-case design and code review. Because it is automotive software, we still keep a human in the loop: every generated script is reviewed before execution.
>
> In short: the AI does the boring typing, and the engineers do the thinking."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="question-2-api-testing-in-an-embedded-automotive-environment"></a>QUESTION 2: API Testing in an Embedded Automotive Environment
**[Interviewer]:** *"How did you approach API testing in an embedded automotive environment?"*

**[Your Response]:**
> "Sure, let me walk you through it.
>
> **Situation:** In our automotive projects, the system ran on an Android board, and it had to communicate with the cloud backend server in real time.
>
> **Task:** I had to check that data from the physical board really reached the backend. Manual tools like Postman were not good enough, because we could not easily automate them together with hardware actions.
>
> **Action:** I built custom API keywords inside our Robot Framework project, using Python's `requests` and `WebSocket` libraries. The flow is very simple: first, a keyword sends an ADB command to trigger a real action on the board. Right after that, an API keyword queries the backend to verify the telemetry data, vehicle state, or log event.
>
> **Result:** The whole QA team could combine UI interactions and API validations in one test suite, so our end-to-end testing became faster and more reliable.
>
> In short: I wrapped technical API calls into simple keywords, so anyone in the team can use them."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="question-3-setting-up-cicd-pipelines-and-managing-infrastructure"></a>QUESTION 3: Setting Up CI/CD Pipelines and Managing Infrastructure
**[Interviewer]:** *"What was your exact role in setting up CI/CD pipelines and managing infrastructure?"*

**[Your Response]:**
> "Sure. I was responsible for the full setup of our test infrastructure, not just for maintaining existing jobs.
>
> **Situation:** We needed to run Android and automotive tests automatically, every time a developer pushed code.
>
> **Task:** I had to set up the pipeline from scratch and keep it stable on both Ubuntu and Windows machines.
>
> **Action:** First, I configured the Jenkins slave nodes from scratch: the execution runtime, environment paths, a local ADB server, and the physical connection to the devices and boards. Second, I wrote the Groovy Declarative Pipeline. When someone pushes code, a webhook triggers the job, and the pipeline pulls the code, scans for an available hardware node, runs the Robot Framework suites on that device UDID, parses the XML output, and publishes an HTML report. Finally, I added error handling: if ADB reports a device as 'offline' or 'unauthorized', the pipeline skips that node and sends a Slack or email alert to the infra team.
>
> **Result:** The pipeline ran reliably, and we avoided false-negative results from broken devices.
>
> In short: I built the pipeline, and I made it smart enough to skip bad devices instead of reporting fake failures."

_**[⬆ Back to Table of Contents](#table-of-contents)**_

---

## PART 3: MIDDLE-LEVEL SCENARIO & EXPERIENCE QUESTIONS

### <a id="m1-robot-framework-project-clean--maintainable-structure"></a>M1: Robot Framework Project Clean & Maintainable Structure
**[Interviewer]:** *"How do you structure your Robot Framework project to ensure it is clean and maintainable?"*

**[Your Response]:**
> "I split the project into layers, so test logic is separate from implementation details.
>
> First, the Tests layer: `.robot` files with high-level test cases, written in Gherkin style.
>
> Second, the Keywords/Resources layer: `.resource` files with reusable keywords.
>
> Third, the Libraries layer: custom Python classes (`.py`) for low-level logic, like device control or API calls that Robot Framework cannot do by itself.
>
> Finally, the Data layer: environment configs, endpoints, variables, and localization files.
>
> In short: Tests say what to do, Resources and Libraries say how to do it, and Data says with which data."

* **Ví dụ:** `tests/login.robot` chỉ gọi keyword; `resources/login.resource` chứa keyword dùng lại; `libraries/adb_lib.py` chứa code ADB; `data/staging.yaml` chứa URL và tài khoản.
* **🧠 Nhớ nhanh:** Tests = *cái gì*; Resources = *dùng lại*; Libraries = *việc nặng*; Data = *dữ liệu*.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m2-exception-handling-inside-custom-python-libraries"></a>M2: Exception Handling Inside Custom Python Libraries
**[Interviewer]:** *"How do you handle exceptions or errors inside your custom Python libraries so that Robot Framework catches them correctly?"*

**[Your Response]:**
> "I use `try-except` in my Python library to handle small problems quietly.
>
> First, for a minor issue, I catch it and handle it, so the test can continue.
>
> Second, if the error is serious and must stop the test, I raise an exception — a normal `RuntimeError` or my own custom exception.
>
> Third, Robot Framework catches that exception automatically, marks the keyword step as FAILED, and keeps the exact message in the log.
>
> In short: small errors I handle, serious errors I raise, and Robot Framework reports them clearly."

* **Ví dụ:** mất kết nối ADB → `raise RuntimeError('Device offline')` → step hiện FAILED, log ghi rõ 'Device offline'.
* **🧠 Nhớ nhanh:** Lỗi nhỏ → bắt và xử lý; lỗi nghiêm trọng → `raise` để Robot Framework đánh FAILED.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m3-implementing-data-driven-testing-ddt-in-robot-framework"></a>M3: Implementing Data-Driven Testing (DDT) in Robot Framework
**[Interviewer]:** *"How do you implement Data-Driven Testing in Robot Framework? For example, testing the same flow with multiple inputs."*

**[Your Response]:**
> "I use the built-in `Test Template` feature of Robot Framework.
>
> First, I write one keyword that does the full flow, for example `Login With Credentials`.
>
> Second, under the `Test Cases` header, I only list data rows: username, password, and the expected result.
>
> Finally, the same logic runs again for every row, so I never copy and paste test steps.
>
> In short: one keyword plus many data rows — that is a Test Template."

* **Ví dụ:** `valid/valid → Success`; `valid/wrong → 'Invalid password'`; `locked user → 'Account locked'`.
* **🧠 Nhớ nhanh:** 1 keyword + nhiều dòng dữ liệu = `Test Template`.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m4-essential-adb-commands-for-everyday-android-automation"></a>M4: Essential ADB Commands for Everyday Android Automation
**[Interviewer]:** *"Since you work a lot with Android automation, what are the most common ADB commands you use in your automation scripts?"*

**[Your Response]:**
> "These are the ADB commands I use most in automation.
>
> First, `adb devices` — to check the device is connected and ready.
>
> Second, `adb shell am start` and `am force-stop` — to open or reset the app package.
>
> Third, `adb shell input tap / text / keyevent` — to simulate touches and typing when normal element locators fail.
>
> Fourth, `adb logcat` — to pull logs when a test fails, so I can attach evidence to the bug ticket.
>
> Finally, `adb push` and `adb pull` — to copy config files into the phone, or download screenshots from it.
>
> In short: check the device, control the app, simulate the user, and collect the evidence."

* **Ví dụ:** test treo ở màn hình loading → `adb logcat` để xem app báo lỗi gì trước khi log bug.
* **🧠 Nhớ nhanh:** Xem máy – Mở/tắt app – Chạm/gõ – Xem log – Copy file.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m5-handling-dynamic-ui-elements-without-hardcoded-sleeps"></a>M5: Handling Dynamic UI Elements Without Hardcoded Sleeps
**[Interviewer]:** *"How do you handle dynamic UI elements or elements that take time to load on Android devices?"*

**[Your Response]:**
> "My rule is simple: no hard-coded sleeps like `Sleep 5s`, because they waste time and make tests flaky. I always use explicit waits.
>
> First, in Java with UIAutomator, I use `device.wait(Until.hasObject(...), timeout)`.
>
> Second, in Robot Framework, I use `Wait Until Element Is Visible` or `Wait Until Page Contains Element` with a timeout.
>
> With this, the test moves on the moment the element appears, so we never wait longer than needed.
>
> In short: I do not sleep and hope — I wait for a condition."

* **Ví dụ:** nút Login cần 2s để hiện → set timeout 10s → test đi tiếp sau 2s, không chờ đủ 10s.
* **🧠 Nhớ nhanh:** Không `Sleep` cứng — chỉ `Wait` có điều kiện.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m6-troubleshooting-local-pass-vs-jenkins-cicd-failures"></a>M6: Troubleshooting Local Pass vs. Jenkins CI/CD Failures
**[Interviewer]:** *"What is your approach when a test script passes on your local machine but fails randomly when running on the Jenkins node?"*

**[Your Response]:**
> "When a test passes locally but fails on Jenkins, it is usually an environment difference. I check it in three steps.
>
> First, I read the evidence: the Jenkins log and the failure screenshot, to see what really happened.
>
> Second, I compare the environments: display size and rotation, network speed, and the ADB version or driver on that node.
>
> Third, I adjust the waits. Jenkins machines are often shared and busy, so the UI reacts more slowly. I increase the explicit timeouts for the dynamic steps.
>
> In short: compare the two environments, and give the slower machine more time."

* **Ví dụ:** máy local màn hình 1080p, node Jenkins 720p → nút nằm ngoài màn hình → phải cuộn hoặc set cùng độ phân giải.
* **🧠 Nhớ nhanh:** Xem log/screenshot → so sánh môi trường → tăng timeout nếu máy yếu hơn.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m7-handling-authentication-tokens-in-python-api-testing"></a>M7: Handling Authentication Tokens in Python API Testing
**[Interviewer]:** *"When testing REST APIs with Python, how do you handle authentication tokens across multiple test steps?"*

**[Your Response]:**
> "I use Python's `requests.Session()`.
>
> First, I log in once with a POST request and take the token from the JSON response.
>
> Second, I put the token into the session headers: `session.headers.update({'Authorization': f'Bearer {token}'})`.
>
> Third, from then on, every request with that session already carries the token.
>
> In short: log in once, store the token in the session, and forget about it."

* **Ví dụ:** login → token `eyJhb...` → gán vào session → các request GET/POST sau không cần nhắc token.
* **🧠 Nhớ nhanh:** Login 1 lần → lấy token → nhét vào `session.headers` → xài lại cho mọi request.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m8-scripted-vs-declarative-jenkins-pipeline-choice"></a>M8: Scripted vs. Declarative Jenkins Pipeline Choice
**[Interviewer]:** *"What is the difference between a Scripted and a Declarative Jenkins Pipeline, and which one do you prefer for automation?"*

**[Your Response]:**
> "I prefer Declarative pipelines.
>
> First, Declarative pipelines must follow a fixed template inside a `pipeline {}` block. That makes them easy to read, and they have built-in `post {}` sections for success, failure, and cleanup.
>
> Second, Scripted pipelines use free Groovy code. They are more flexible, but harder to read and maintain.
>
> For test automation, Declarative gives exactly what we need: pull the code, compile, run the tests, and report.
>
> In short: Declarative for clear structure, Scripted only when I really need free logic."

* **Ví dụ:** `post { failure { slackSend ... } }` tự gửi cảnh báo khi test fail, không cần viết `try/catch`.
* **🧠 Nhớ nhanh:** Declarative = có khuôn, dễ đọc, có `post {}`; Scripted = Groovy tự do, khó bảo trì.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m9-regression-testing-under-extreme-timeline-constraints"></a>M9: Regression Testing Under Extreme Timeline Constraints
**[Interviewer]:** *"How do you perform Regression Testing when a minor bug fix is delivered, and the execution time is very limited?"*

**[Your Response]:**
> "When time is short, I do not run everything. I do an Impact Analysis.
>
> First, I ask the developer which files or modules were changed.
>
> Second, I pick a small group of test cases: only the changed features and the systems that are connected to them.
>
> Finally, I run our automated Smoke suite to confirm the core system is still stable before release.
>
> In short: test the changed parts deeply, and do a quick smoke check for the rest of the system."

* **Ví dụ:** fix nút 'Forgot Password' → test lại flow quên mật khẩu + gửi email + đăng nhập, rồi chạy smoke.
* **🧠 Nhớ nhanh:** Hỏi dev sửa gì → test đúng vùng đó + vùng liên quan → chạy smoke.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m10-reopening-existing-bugs-vs-creating-new-defect-spinoffs"></a>M10: Reopening Existing Bugs vs. Creating New Defect Spinoffs
**[Interviewer]:** *"What do you do if a developer marks your bug as 'Fixed', but during retesting, you find the bug is still there, or it caused a new bug?"*

**[Your Response]:**
> "There are two different cases, and I handle them differently.
>
> First, if the old bug is still there, I do not create a new ticket. I reopen the original Jira ticket, attach the new logs and screenshots, and comment that the fix failed on this build.
>
> Second, if the old bug is fixed but the change broke another feature, I close the original ticket and open a new bug ticket for the new issue. Then I link the two tickets for traceability.
>
> In short: old bug still there — reopen it; new bug caused by the fix — create a new ticket and link it."

* **Ví dụ:** bug login còn lỗi → Reopen; login hết lỗi nhưng nút Logout mới bị vỡ → ticket mới cho Logout + link với ticket cũ.
* **🧠 Nhớ nhanh:** Lỗi cũ còn → Reopen; lỗi mới do sửa → ticket mới + link.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

---

## PART 4: 30 CORE QUALITY ASSURANCE QUESTIONS & SMART ANSWERS

> **Cách học:** mỗi câu trả lời đi theo 3 nhịp — **First / Second / Finally** rồi chốt bằng **In short:** (câu ngắn nhất, dễ nhớ nhất). Sau đó đọc **Ví dụ** để hiểu ý, và **🧠 Nhớ nhanh** để nhắc lại trước khi vào phòng phỏng vấn.

### <a id="core-1-difference-between-sdlc-and-stlc"></a>CORE 1: Difference Between SDLC and STLC
**[Answer]:**
> "To explain it simply, SDLC is the big picture and STLC is a part inside it.
>
> First, SDLC means Software Development Life Cycle. It covers the whole process of building software: planning, designing, coding, testing, and releasing.
>
> Second, STLC means Software Testing Life Cycle. It is a smaller phase inside SDLC that focuses only on testing: analysing requirements, planning tests, writing test cases, running them, and closing the testing phase.
>
> In short: SDLC is for building the software, and STLC is for testing it."

* **Ví dụ:** SDLC giống xây cả căn nhà (từ bản vẽ đến bàn giao); STLC là bước kiểm tra chất lượng của căn nhà đó.
* **🧠 Nhớ nhanh:** SDLC = cả vòng đời; STLC = vòng đời của testing, chạy song song bên trong SDLC.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-2-verification-vs-validation"></a>CORE 2: Verification vs. Validation
**[Answer]:**
> "The easiest way is to remember two questions.
>
> First, Verification asks: 'Are we building the product right?' This is static testing, so we do not run the software. We check the documents, the requirements, and the code to find mistakes early.
>
> Second, Validation asks: 'Are we building the right product?' This is dynamic testing, so we actually run the software and use it like a real user, to make sure it meets the user's expectations.
>
> In short: verification checks the documents, and validation checks the working product."

* **Ví dụ:** Verification = đọc bản thiết kế xem đúng chuẩn chưa (chưa chạy gì). Validation = lắp xong cho người dùng chạy thử.
* **🧠 Nhớ nhanh:** Verification = *không chạy app*, chỉ đọc tài liệu; Validation = *phải chạy app* như người dùng thật.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-3-standard-fields-in-a-high-quality-test-case"></a>CORE 3: Standard Fields in a High-Quality Test Case
**[Answer]:**
> "A good test case has a clear ID and title, plus these fields.
>
> First, the setup: Test Case ID, Title, and Pre-condition.
>
> Second, the action: Test Steps and Test Data.
>
> Third, the result: Expected Result, Actual Result, and Status (Pass, Fail, or Blocked).
>
> Finally, for traceability we also add Priority, Severity, Module, Author, and Post-condition.
>
> In short: prepare, do it, compare expected with actual, and give a status."

* **Ví dụ:** ID `TC-01` | Title `Login with valid account` | Pre-condition `user đã đăng ký` | Data `user1 / 123456` | Expected `vào trang Home` | Actual `vào trang Home` | Status `Pass`.
* **🧠 Nhớ nhanh:** nhớ theo dòng chảy: **Chuẩn bị → Làm → Dữ liệu → Mong đợi → Thực tế → Kết luận** (Pass/Fail/Blocked).

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-4-smoke-sanity-and-regression-testing-distinctions"></a>CORE 4: Smoke, Sanity, and Regression Testing Distinctions
**[Answer]:**
> "Here is how I make it simple to understand.
>
> First, Smoke testing runs on a new build. We check that the core functions work and the build is stable. It is broad and shallow.
>
> Second, Sanity testing runs after a small bug fix. We check only that changed area carefully. It is narrow and deep.
>
> Third, Regression testing runs after any code change. It is full testing to make sure the new code did not break old features.
>
> In short: Smoke is for build stability, Sanity is for one specific fix, and Regression is for overall safety."

* **Ví dụ:** Smoke = mở app, thử đăng nhập / thanh toán / tìm kiếm xem còn chạy. Sanity = chỉ test lại nút 'Forgot Password' vừa sửa. Regression = chạy lại bộ test cũ sau khi sửa.
* **🧠 Nhớ nhanh:** Smoke = build mới (rộng, nông); Sanity = sửa 1 chỗ (hẹp, sâu); Regression = sợ vỡ chỗ khác.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-5-severity-vs-priority-with-extreme-examples"></a>CORE 5: Severity vs. Priority with Extreme Examples
**[Answer]:**
> "Severity is how badly the bug breaks the system, and Priority is how soon the business needs it fixed.
>
> First, High Severity but Low Priority: the app crashes only when a user types 10,000 characters into an optional field. It is a serious bug, but very rare, so it can wait.
>
> Second, Low Severity but High Priority: a typo in the company logo on the homepage. Nothing breaks, but the brand looks bad, so we fix it now.
>
> In short: severity is the technical damage, and priority is the business urgency."

* **Ví dụ:** App crash khi nhập 10.000 ký tự = nặng nhưng hiếm → Severity cao, Priority thấp. Sai chính tả logo trang chủ = nhẹ nhưng ảnh hưởng thương hiệu → Severity thấp, Priority cao.
* **🧠 Nhớ nhanh:** Severity = *hỏng nặng đến đâu*; Priority = *phải sửa gấp đến đâu*. Nặng chưa chắc gấp, gấp chưa chắc nặng.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-6-core-states-in-a-standard-bug-life-cycle"></a>CORE 6: Core States in a Standard Bug Life Cycle
**[Answer]:**
> "A bug moves through these states.
>
> First, New — I found it. Then Assigned — it goes to a developer.
>
> Second, Open while the developer is working on it, and Fixed when the developer says it is done.
>
> Third, Retest — I test it again on the new build. If it passes, it becomes Verified and then Closed. If it fails, it goes back to Reopened.
>
> There are also other states: Deferred (fix later), Rejected (not accepted), and Cannot Reproduce.
>
> In short: New, Assigned, Open, Fixed, Retest, Verified, Closed — and Reopen if the fix fails."

* **Ví dụ:** giống xử lý khiếu nại: tiếp nhận → chuyển bộ phận → xử lý → trả lời → khách kiểm tra lại → đóng.
* **🧠 Nhớ nhanh:** **Mới → Giao → Mở → Sửa → Test lại → Xác nhận → Đóng**; fail thì Reopen.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-7-black-box-white-box-and-gray-box-testing"></a>CORE 7: Black-box, White-box, and Gray-box Testing
**[Answer]:**
> "The difference is how much of the code we can see.
>
> First, Black-box: I only check inputs and outputs against requirements. I know nothing about the code inside.
>
> Second, White-box: I look inside the code — branches, loops, and statements. Developers usually do this with unit tests.
>
> Third, Gray-box: in between. I know some internals, like the database or the system architecture, but I still test from the outside.
>
> In short: black is outside, white is inside, and gray is a bit of both."

* **Ví dụ:** Black-box = thử đồ hộp mà không biết công thức; White-box = biết rõ công thức từng bước; Gray-box = biết vài nguyên liệu chính nhưng không biết hết.
* **🧠 Nhớ nhanh:** Đen = không thấy code; Trắng = thấy hết code; Xám = thấy một phần.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-8-functional-vs-non-functional-testing-with-examples"></a>CORE 8: Functional vs. Non-functional Testing with Examples
**[Answer]:**
> "The easiest way is to ask WHAT and HOW WELL.
>
> First, Functional testing checks WHAT the system does. For example: can the user log in? Does the payment go through? Does the search return the right items?
>
> Second, Non-functional testing checks HOW WELL it does it. For example: is it fast under high traffic (performance)? Is it safe from hackers (security)? Is it easy to use (usability)?
>
> In short: functional testing checks that the car can drive, and non-functional testing checks how fast and safe it is."

* **Ví dụ:** Functional = đăng nhập đúng tài khoản có vào được không? Non-functional = đăng nhập mất bao lâu, có chặn brute force không?
* **🧠 Nhớ nhanh:** Functional = *LÀM ĐƯỢC GÌ*; Non-functional = *LÀM TỐT ĐẾN ĐÂU*.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-9-essential-components-of-a-great-bug-report"></a>CORE 9: Essential Components of a Great Bug Report
**[Answer]:**
> "A good bug report must be clear and actionable, so I always include six things.
>
> First, a short clear Title.
>
> Second, the Steps to Reproduce, and the Environment — for example OS, browser version, and device.
>
> Third, the Expected result and the Actual result.
>
> Finally, Severity and Priority, plus Evidence: screenshots, a screen recording, or logs.
>
> In short: title, steps, expected versus actual, environment, levels, and evidence."

* **Ví dụ:** Title 'Login fails with valid account on Android 12' + 5 bước + 2 ảnh chụp + file `logcat`.
* **🧠 Nhớ nhanh:** **Tiêu đề – Bước – Mong đợi/Thực tế – Môi trường – Mức độ – Bằng chứng**.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-10-test-plan-vs-test-strategy-documents"></a>CORE 10: Test Plan vs. Test Strategy Documents
**[Answer]:**
> "Think of the Test Strategy as the company's rulebook, and the Test Plan as the map for one project.
>
> First, the Test Strategy is a high-level document for the whole company. It is static, so it rarely changes. It defines the general approach, the standards, and the tools we use for testing.
>
> Second, the Test Plan is a document for one specific project or release. It is dynamic, so it can change. It takes the rules from the strategy and adds the details: scope, schedule, resources, risks, and deliverables.
>
> In short: the strategy is general and stable, and the plan is specific and changes with each release."

* **Ví dụ:** Strategy = 'luật chơi chung của công ty'; Plan = 'kế hoạch cho đợt release này'.
* **🧠 Nhớ nhanh:** Strategy = cấp công ty, ít đổi; Plan = cấp dự án, đổi theo từng release.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-11-applying-bva-and-ep-on-age-field-18-60"></a>CORE 11: Applying BVA and EP on Age Field (18-60)
**[Answer]:**
> "I use two techniques here.
>
> First, Boundary Value Analysis: I test the edges. For an age field from 18 to 60, I test 17 (invalid), 18 (valid minimum), 19 (valid), 59 (valid), 60 (valid maximum), and 61 (invalid).
>
> Second, Equivalence Partitioning: I split the inputs into groups and test one value from each group — valid 18 to 60, too low (under 18), too high (over 60), and wrong format like letters, symbols, a negative number, or an empty field.
>
> In short: BVA tests the edges, and EP tests one value for each group."

* **Ví dụ:** nhập 18 → OK; nhập 17 → báo lỗi; nhập 61 → báo lỗi; nhập 'abc' → báo lỗi.
* **🧠 Nhớ nhanh:** BVA = test đúng mép và sát mép; EP = test 1 giá trị đại diện cho cả nhóm.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-12-essential-test-cases-for-a-user-login-feature"></a>CORE 12: Essential Test Cases for a User Login Feature
**[Answer]:**
> "Login needs more than correct and wrong passwords, so I test five groups.
>
> First, functionality: valid and invalid credentials, empty fields, and password case sensitivity.
>
> Second, security: SQL Injection and XSS payloads, and brute force protection, for example the account locks after N failed attempts.
>
> Third, session: Remember Me, session timeout, and login from many devices at the same time.
>
> Then, other flows: social login like Google or Facebook, and the Forgot Password flow.
>
> Finally, the UI on small screens.
>
> In short: function, security, session, devices, and layout."

* **Ví dụ:** nhập sai mật khẩu 5 lần → tài khoản bị khóa 15 phút.
* **🧠 Nhớ nhanh:** 5 nhóm — **Chức năng – Bảo mật – Phiên đăng nhập – Nhiều thiết bị – Giao diện**.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-13-handling-cannot-reproduce-feedback-professionally"></a>CORE 13: Handling 'Cannot Reproduce' Feedback Professionally
**[Answer]:**
> "I stay friendly, never defensive, and I follow four steps.
>
> First, I re-read my bug report and check that the steps, the test data, and the environment are clear.
>
> Second, I send a screen recording or the logs.
>
> Third, if it still cannot be reproduced, I debug together with the developer on their machine.
>
> Finally, if it only happens in a special environment, I write those exact conditions into the ticket.
>
> In short: check my report, share evidence, debug together, and document the environment."

* **Ví dụ:** bug chỉ xảy ra trên Android 11 → ghi rõ model, phiên bản OS, phiên bản app vào ticket.
* **🧠 Nhớ nhanh:** Kiểm tra lại report → gửi bằng chứng → debug cùng nhau → ghi lại điều kiện đặc biệt.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-14-determining-when-to-stop-testing-exit-criteria"></a>CORE 14: Determining When to Stop Testing (Exit Criteria)
**[Answer]:**
> "Testing never really ends, so we agree the Exit Criteria in advance and stop when they are met.
>
> First, all high-priority test cases are executed, and the coverage target is reached.
>
> Second, the number of open defects is below the allowed limit — for example, zero Critical bugs and fewer than five Minor bugs.
>
> Finally, the deadline is reached, and the stakeholders accept the remaining risk.
>
> In short: enough testing, enough coverage, few bugs, and someone formally accepts the risk."

* **Ví dụ:** '0 bug Critical, còn ≤ 5 bug Minor, chạy 100% test P1 → được dừng'.
* **🧠 Nhớ nhanh:** Đủ test → đủ coverage → ít bug → hết thời gian → có người ký nhận rủi ro.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-15-standard-bug-tracking-workflow-inside-jira"></a>CORE 15: Standard Bug Tracking Workflow Inside Jira
**[Answer]:**
> "My Jira workflow is very practical.
>
> First, I log the defect with clear steps, evidence, and environment. I set the Epic, Component, Severity, and Priority, then assign it to the dev team.
>
> Second, when the ticket is marked Fixed, I pull the latest build and retest it.
>
> Finally, I attach the new verification evidence and close the ticket.
>
> In short: log it clearly, retest on the latest build, then close it with evidence."

* **Ví dụ:** ticket đang ở trạng thái Fixed → QA retest → Pass → chuyển sang Closed kèm ảnh chụp mới.
* **🧠 Nhớ nhanh:** **Log → Gán → Fix → Retest → Đóng**.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-16-verifying-get-post-put-delete-and-http-status-codes"></a>CORE 16: Verifying GET, POST, PUT, DELETE and HTTP Status Codes
**[Answer]:**
> "I check each method for what it is supposed to do.
>
> First, GET reads data. I check the response structure, the filters, and the pagination.
>
> Second, POST creates data. I check the required fields, wrong data types, and duplicate prevention.
>
> Third, PUT updates data, so I check the data really changes. DELETE removes data, and deleting something that does not exist must give a clear error, not a crash.
>
> For status codes: 200 OK, 201 Created, and 204 No Content mean success. 400 Bad Request, 401 Unauthorized, 403 Forbidden, 404 Not Found, and 409 Conflict are client errors. 500 Internal Server Error is a server error.
>
> In short: GET reads, POST creates, PUT updates, DELETE removes — and 2xx is fine, 4xx is the client's fault, 5xx is the server's fault."

* **Ví dụ:** POST thiếu email → 400 Bad Request; POST trùng email → 409 Conflict; DELETE id không tồn tại → 404.
* **🧠 Nhớ nhanh:** **GET = đọc, POST = tạo, PUT = sửa, DELETE = xóa**; mã: 2xx thành công, 4xx lỗi phía client, 5xx lỗi server.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-17-focus-areas-and-tools in-responsive-web-testing"></a>CORE 17: Focus Areas and Tools in Responsive Web Testing
**[Answer]:**
> "I check the layout at every breakpoint: mobile, tablet, and desktop.
>
> First, the visual parts: text scaling, images, and the menu changing into a hamburger icon.
>
> Second, the interactions: touch events and screen rotation.
>
> Finally, for tools I use Chrome DevTools for quick checks, BrowserStack for many real devices, and a real phone for the final confirmation.
>
> In short: layout, touch, rotation, text and images — checked in DevTools, on real devices, and on a real phone."

* **Ví dụ:** màn 375px thì menu phải thành hamburger; màn 1440px thì menu nằm ngang.
* **🧠 Nhớ nhanh:** Bố cục – Cảm ứng – Xoay màn hình – Chữ/hình – Menu. Tools: DevTools + BrowserStack + máy thật.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-18-cross-browser-testing-and-browser-selection-criteria"></a>CORE 18: Cross-Browser Testing and Browser Selection Criteria
**[Answer]:**
> "We need it because browsers use different rendering engines, so the same CSS, HTML, and JS can behave differently.
>
> First, I do not guess. I pick the browsers by looking at real data about our users, from tools like Google Analytics or StatCounter.
>
> Second, in most projects we support the latest two versions of Chrome, Safari, Edge, and Firefox.
>
> In short: browsers render things differently, so we choose them based on our own user data."

* **Ví dụ:** nút Submit bị lệch 2px trên Safari — chỉ phát hiện khi test trên Safari.
* **🧠 Nhớ nhanh:** Khác engine → khác kết quả; chọn browser theo dữ liệu người dùng thật, không đoán.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-19-handling-200-unexecuted-test-cases-with-a-1-day-deadline"></a>CORE 19: Handling 200 Unexecuted Test Cases with a 1-Day Deadline
**[Answer]:**
> "With 200 cases and only one day, I switch to Risk-Based Testing.
>
> First, I run the critical Smoke tests to make sure the app is not broken.
>
> Second, I run the main end-to-end user flows, and the regression tests for the modules that changed recently.
>
> Finally, I report clearly to the PM: what was tested, what was not, and what risks are left, so the business can decide.
>
> In short: test the most important things first, and report the rest honestly."

* **Ví dụ:** 200 case còn lại → chọn 30 case quan trọng nhất (đăng nhập, thanh toán, đặt hàng) để chạy trước.
* **🧠 Nhớ nhanh:** Smoke → luồng chính → module vừa thay đổi → báo cáo minh bạch.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-20-test-cases-for-an-e-commerce-add-to-cart-feature"></a>CORE 20: Test Cases for an E-commerce 'Add to Cart' Feature
**[Answer]:**
> "For Add to Cart, I check the cart from many angles.
>
> First, quantities: add 1, add many, add 0, add a negative number, add more than the warehouse has, and add an out-of-stock item.
>
> Second, users and state: guest checkout, and whether the cart is still there after logout and login again.
>
> Third, prices and data: does the price update when a promo code is applied, and does the cart stay in sync between two browser tabs?
>
> Finally, performance: how fast is the page when the cart is huge?
>
> In short: quantity, stock, user state, price, sync, and speed."

* **Ví dụ:** thêm 5 sản phẩm khi kho chỉ còn 3 → hệ thống phải báo 'chỉ còn 3'.
* **🧠 Nhớ nhanh:** Số lượng – Tồn kho – Khách/Guest – Đăng nhập lại – Khuyến mãi – Đồng bộ tab – Hiệu năng.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-21-allocating-testing-scope-for-5-pm-build-releasing-at-9-am"></a>CORE 21: Allocating Testing Scope for 5 PM Build Releasing at 9 AM
**[Answer]:**
> "With a build at 5 PM and a release at 9 AM, I work in three steps.
>
> First, I run a quick Smoke Test to confirm the app starts and the core features still work.
>
> Second, I use Impact Analysis. I find the modules changed by the latest commits and run regression tests only on those modules and the features connected to them.
>
> Finally, before I leave, I send a short status report: what was tested, what was skipped, and what risks remain.
>
> In short: smoke first, then targeted regression, and a clear report before the release."

* **Ví dụ:** build chỉ sửa phần thanh toán → test thanh toán + đơn hàng liên quan, bỏ qua module chat không đổi.
* **🧠 Nhớ nhanh:** Smoke nhanh → Impact Analysis → báo cáo trước khi về.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-22-retesting-vs-regression-suite-scope-optimization"></a>CORE 22: Retesting vs. Regression Suite Scope Optimization
**[Answer]:**
> "The difference is the target.
>
> First, Retesting checks the exact bug I reported, to confirm the fix really works.
>
> Second, Regression testing checks that this fix did not break other features.
>
> Third, when the regression suite becomes too big, I prioritise with Impact Analysis and risk-based selection, and I automate the stable, repetitive cases so they run in the pipeline.
>
> In short: retest asks 'is my bug fixed?', and regression asks 'did we break something else?'"

* **Ví dụ:** Retest = login đã OK chưa; Regression = sau khi sửa login, nút Logout có còn chạy?
* **🧠 Nhớ nhanh:** Retest = *'bug của tôi đã hết chưa?'*; Regression = *'sửa nó có làm vỡ chỗ khác không?'*.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-23-handling-critical-defects-releasing-with-pm-approval"></a>CORE 23: Handling Critical Defects Releasing with PM Approval
**[Answer]:**
> "My job is to show the risk, not to block the release.
>
> First, I document the bug clearly in Jira: the impact, how to reproduce it, and the effect on users.
>
> Second, I email the stakeholders, so there is a clear audit trail.
>
> Finally, when the PM formally accepts the risk and signs off, I help prepare a hotfix for after the release.
>
> In short: I make the risk visible, the PM owns the decision, and we prepare a hotfix."

* **Ví dụ:** bug chỉ ảnh hưởng 1% người dùng iOS cũ → PM ký chấp nhận → release, kèm kế hoạch hotfix.
* **🧠 Nhớ nhanh:** Ghi rõ rủi ro → để PM ký nhận → chuẩn bị hotfix.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-24-comprehensive-test-scenarios-for-a-file-upload-component"></a>CORE 24: Comprehensive Test Scenarios for a File Upload Component
**[Answer]:**
> "For file upload I cover five areas.
>
> First, the file type: valid and invalid extensions, and a fake MIME type, for example an `.exe` renamed to `.png`.
>
> Second, the size: 0 KB, exactly the maximum, and over the maximum.
>
> Third, the file name: special characters and very long names, plus corrupted files.
>
> Then, security: a malware scan with an Eicar test file.
>
> Finally, the network: connection lost in the middle of the upload, many files at once, and cancelling an upload.
>
> In short: type, size, name, virus, and network."

* **Ví dụ:** upload file 0 KB → hệ thống phải báo lỗi rõ ràng, không được treo.
* **🧠 Nhớ nhanh:** Loại file – Kích thước – Tên file – File lỗi/virus – Giả MIME – Mạng – Nhiều file – Hủy.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-25-comprehensive-test-cases-for-a-website-search-box"></a>CORE 25: Comprehensive Test Cases for a Website Search Box
**[Answer]:**
> "For a search box, I check the input first, and then the behaviour.
>
> First, the input cases: empty search, one character, the maximum length, spaces before and after the keyword, special characters, and Vietnamese with accents.
>
> Second, the security cases: SQLi and XSS strings.
>
> Third, the behaviour: copy-paste, the autocomplete suggestion time, and the recent search history.
>
> Finally, performance under heavy load.
>
> In short: input, security, behaviour, and speed."

* **Ví dụ:** gõ `  tai nghe  ` (có khoảng trắng 2 đầu) → kết quả phải giống `tai nghe`.
* **🧠 Nhớ nhanh:** Rỗng – 1 ký tự – Dài nhất – Khoảng trắng – Bảo mật – Ký tự đặc biệt – Gợi ý – Hiệu năng.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-26-handling-defect-rejections-marked-as-not-a-bug"></a>CORE 26: Handling Defect Rejections Marked as 'Not a Bug'
**[Answer]:**
> "I always go back to the requirement, not to opinions.
>
> First, I read the requirement or user story again.
>
> Second, if the specification supports my bug, I reopen the ticket and attach the document, or ask the BA to confirm.
>
> Finally, if the specification is unclear, I book a short call with the developer and the BA, we agree on the correct behaviour, and we update the documentation.
>
> In short: check the specification first, then either reopen with evidence or clarify it together."

* **Ví dụ:** spec ghi 'mật khẩu tối thiểu 8 ký tự' nhưng app cho nhập 6 → reopen ticket + link spec.
* **🧠 Nhớ nhanh:** Xem yêu cầu → có bằng chứng thì reopen + gắn link → chưa rõ thì họp 3 bên (Dev–BA–QA) → cập nhật tài liệu.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-27-test-scenario-vs-test-case-allocation-strategies"></a>CORE 27: Test Scenario vs. Test Case Allocation Strategies
**[Answer]:**
> "The difference is the level of detail.
>
> First, a Test Scenario says WHAT to test, in one line. For example: 'Validate user checkout'.
>
> Second, a Test Case says HOW to test: the steps, the test data, and the expected result.
>
> Third, I use scenarios in fast Agile sprints where the team knows the domain well. I write full test cases for regulated fields like automotive or finance, where we need a clear audit trail.
>
> In short: a scenario is one sentence about what to test, and a test case is the step-by-step about how to test it."

* **Ví dụ:** Scenario = 'Kiểm tra đăng nhập'; Test Case = `TC-01` với 5 bước, dữ liệu, kết quả mong đợi.
* **🧠 Nhớ nhanh:** Scenario = *cái gì* (1 câu); Test Case = *làm thế nào* (từng bước).

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-28-testing-a-feature-with-absolute-zero-documentation"></a>CORE 28: Testing a Feature with Absolute Zero Documentation
**[Answer]:**
> "When there is no documentation, I combine four things.
>
> First, exploratory testing, to learn the feature by using it.
>
> Second, competitor analysis, to understand the standard flow in that industry.
>
> Third, short interviews with the developer and the Product Owner, to map the basic flows.
>
> Finally, I write down my assumptions and test criteria, and ask the team to confirm them before I execute.
>
> In short: explore, compare, ask, and confirm my own assumptions."

* **Ví dụ:** chưa có tài liệu → tự khám phá app, so sánh với app cùng loại, hỏi PO, viết giả định gửi team xác nhận.
* **🧠 Nhớ nhanh:** Khám phá → xem sản phẩm tương tự → hỏi Dev/PO → ghi giả định và xác nhận.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-29-performance-load-stress-and-spike-testing-metrics"></a>CORE 29: Performance, Load, Stress, and Spike Testing Metrics
**[Answer]:**
> "These four tests have different goals.
>
> First, Performance testing checks the system under normal conditions.
>
> Second, Load testing checks it at the expected peak user volume.
>
> Third, Stress testing pushes the system past its limit, to find the breaking point. Spike testing checks a sudden, huge traffic increase and then a sharp drop.
>
> For metrics, I look at throughput in requests per second, the error rate, CPU and RAM usage, and the 95th or 99th percentile response time, which is more honest than a simple average.
>
> In short: normal, peak, broken, and shocked — measured by throughput, errors, resources, and P95."

* **Ví dụ:** 1000 người dùng cùng lúc → xem P95 response time và error rate, không chỉ xem trung bình.
* **🧠 Nhớ nhanh:** Bình thường – Cao điểm – Quá tải – Sốc; Metrics: Throughput, Error rate, CPU/RAM, P95/P99.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-30-processing-severe-security-flaws-and-data-exposure"></a>CORE 30: Processing Severe Security Flaws and Data Exposure
**[Answer]:**
> "This is a security issue, so I act quietly and ethically.
>
> First, I never screenshot real customer data, and I never discuss the issue in a public or open channel.
>
> Second, I reproduce the problem using dummy test accounts.
>
> Finally, I log a confidential Jira ticket, and I inform the Security Lead and the PM immediately.
>
> In short: no real data and no public talk — test with dummy accounts and escalate privately."

* **Ví dụ:** API trả về thông tin của người dùng khác → dùng tài khoản test, không chụp dữ liệu thật, báo Security ngay.
* **🧠 Nhớ nhanh:** Không chụp dữ liệu thật → test bằng tài khoản giả → ticket bảo mật → báo Security Lead + PM ngay.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

---

## <a id="part-5-test-levels--test-types"></a>PART 5: TEST LEVELS & TEST TYPES

> **Cách học:** nhớ 4 cấp độ theo thứ tự từ nhỏ → lớn: **Unit → Integration → System → Acceptance (UAT)**.

| # | Test level | Ai test | Test cái gì | Ví dụ |
|---|---|---|---|---|
| 1 | **Unit** | Developer | 1 hàm / 1 class riêng lẻ | hàm `calculate_tax()` trả đúng số |
| 2 | **Integration** | Dev + QA | 2 module ghép lại với nhau | API login gọi Database |
| 3 | **System** | QA | cả hệ thống chạy end-to-end | mua hàng: login → thêm giỏ → thanh toán |
| 4 | **Acceptance (UAT)** | Khách hàng / PO / BA | có đúng nhu cầu nghiệp vụ không | khách test app trước khi go-live |

---

### <a id="level-1-what-are-test-levels"></a>LEVEL 1: What Are Test Levels?
**[Interviewer]:** *"What are test levels? Could you name them?"*

**[Answer]:**
> "A test level is a stage of testing, defined by how big the part under test is. There are four main levels.
>
> First, Unit: one function or one class.
>
> Second, Integration: two or more modules working together.
>
> Third, System: the whole system, end to end.
>
> Finally, Acceptance or UAT: the customer checks the business needs.
>
> Each level has its own goal, its own testers, and its own exit criteria.
>
> In short: unit, integration, system, acceptance — from small to large."

* **Ví dụ:** cùng là chức năng đăng nhập, nhưng Unit test hàm kiểm tra mật khẩu, Integration test API login + Database, System test app thật, còn UAT để khách xác nhận.
* **🧠 Nhớ nhanh:** **Unit → Integration → System → Acceptance**, đi từ nhỏ đến lớn; mỗi cấp có người test và mục tiêu riêng.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="level-2-unit-testing"></a>LEVEL 2: Unit Testing
**[Interviewer]:** *"What is unit testing and who does it?"*

**[Answer]:**
> "Unit testing checks the smallest piece of code — one function, one method, or one class — in isolation.
>
> First, it is usually written by developers, using frameworks like JUnit, pytest, or NUnit.
>
> Second, it is the fastest and cheapest level, so it runs first in the pipeline and gives feedback in seconds.
>
> In short: unit testing checks one small piece of code, and the developer writes it."

* **Ví dụ:** pytest test hàm `calculate_tax(100)` → kỳ vọng trả về 10.
* **🧠 Nhớ nhanh:** Unit = 1 hàm, **dev viết**, chạy nhanh nhất và rẻ nhất; cô lập, không gọi Database hay API thật.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="level-3-integration-testing"></a>LEVEL 3: Integration Testing
**[Interviewer]:** *"What is integration testing and what does it focus on?"*

**[Answer]:**
> "Integration testing is all about connections.
>
> First, the idea: we combine two or more modules or services and check that they talk to each other correctly.
>
> Second, the reason: code can pass unit tests alone, but when module A calls module B, they can fail because of a data mismatch.
>
> Third, the focus: I follow the data flow. For example, if a user buys an item, does the correct price reach the Payment API and get saved in the Database?
>
> In short: unit testing checks the parts, and integration testing checks the connections between those parts."

* **Ví dụ:** API login gọi Database + service gửi email → test xem dữ liệu có được ghi đúng và email có được gửi không.
* **🧠 Nhớ nhanh:** Integration = test **chỗ nối** giữa các module; bug thường nằm ở đây chứ không nằm trong từng module.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="level-4-system-testing"></a>LEVEL 4: System Testing
**[Interviewer]:** *"What is system testing and what does it cover?"*

**[Answer]:**
> "System testing checks the complete system, end to end, against the requirements.
>
> First, it is done by QA, on the real build, usually on a staging environment.
>
> Second, it covers both functional checks and non-functional checks like performance and security.
>
> Third, it is the level where we test complete user journeys: login, choose a product, add it to the cart, pay, and receive the confirmation email.
>
> In short: the whole system, the whole journey, checked by QA."

* **Ví dụ:** luồng mua hàng đầy đủ: login → chọn sản phẩm → thêm vào giỏ → thanh toán → nhận email xác nhận.
* **🧠 Nhớ nhanh:** System = **cả hệ thống, QA test, end-to-end**, gồm cả functional + non-functional.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="level-5-acceptance-testing-uat-vs-sit"></a>LEVEL 5: Acceptance Testing (UAT) vs. SIT
**[Interviewer]:** *"What is acceptance testing, and what is the difference between SIT and UAT?"*

**[Answer]:**
> "Acceptance testing, or UAT, is when the customer, PO, or BA checks that the software meets the business needs and is ready to go live. It is the last level before release.
>
> First, SIT means System Integration Testing. It is done by testers, and we confirm the system is technically correct.
>
> Second, UAT is done by business users. They confirm the product is useful for the business, using real business scenarios.
>
> In short: SIT is the tester checking the technology, and UAT is the customer checking the business."

* **Ví dụ:** SIT = QA test luồng đặt hàng chạy đúng kỹ thuật; UAT = khách hàng tự đặt 1 đơn trên bản staging rồi mới cho go-live.
* **🧠 Nhớ nhanh:** **SIT = tester test kỹ thuật; UAT = khách test nghiệp vụ**; UAT pass xong mới release.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="level-6-test-pyramid-and-shift-left"></a>LEVEL 6: Test Pyramid and Shift-Left
**[Interviewer]:** *"What is the Test Pyramid, and what does shift-left mean?"*

**[Answer]:**
> "The Test Pyramid shows how many tests we should have at each level.
>
> First, many unit tests at the bottom, because they are fast and cheap.
>
> Second, fewer integration tests in the middle.
>
> Third, very few end-to-end or UI tests at the top, because they are slow and expensive to maintain.
>
> Shift-left means moving testing earlier: start testing from the requirements and the unit level, so bugs are found when they are cheap to fix.
>
> In short: many unit tests, some integration tests, few E2E tests — and test early to fix cheap."

* **Ví dụ:** 1000 unit test (chạy vài giây) + 100 integration test + 20 E2E test (chạy 30 phút) — không nên làm ngược lại.
* **🧠 Nhớ nhanh:** **Kim tự tháp: đáy nhiều Unit – giữa Integration – đỉnh ít E2E**; shift-left = test sớm, sửa rẻ.

_**[⬆ Back to Table of Contents](#table-of-contents)**_
