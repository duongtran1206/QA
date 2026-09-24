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
"I split the project into layers so test logic stays separate from implementation details:
* **Tests layer:** `.robot` files with high-level test cases written in Gherkin style.
* **Keywords/Resources layer:** `.resource` files with reusable keywords.
* **Libraries layer:** custom Python classes (`.py`) with low-level logic (device control, API calls) that Robot Framework cannot do by itself.
* **Data layer:** environment configs, endpoints, variables, and localization files.

* **Ví dụ:** `tests/login.robot` chỉ gọi keyword; `resources/login.resource` chứa keyword dùng lại; `libraries/adb_lib.py` chứa code ADB; `data/staging.yaml` chứa URL và tài khoản.
* **🧠 Nhớ nhanh:** Tests = *cái gì*; Resources = *dùng lại*; Libraries = *việc nặng*; Data = *dữ liệu*.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m2-exception-handling-inside-custom-python-libraries"></a>M2: Exception Handling Inside Custom Python Libraries
**[Interviewer]:** *"How do you handle exceptions or errors inside your custom Python libraries so that Robot Framework catches them correctly?"*

**[Your Response]:**
"In my Python library I wrap risky code in `try-except` to handle small problems quietly. If the error is serious and must stop the test, I raise an exception — a normal Python `RuntimeError` or my own custom exception. Robot Framework catches it automatically, marks that keyword step as 'FAILED', and keeps the exact error message in the log.

* **Ví dụ:** mất kết nối ADB → `raise RuntimeError('Device offline')` → step hiện FAILED, log ghi rõ 'Device offline'.
* **🧠 Nhớ nhanh:** Lỗi nhỏ → bắt và xử lý; lỗi nghiêm trọng → `raise` để Robot Framework đánh FAILED.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m3-implementing-data-driven-testing-ddt-in-robot-framework"></a>M3: Implementing Data-Driven Testing (DDT) in Robot Framework
**[Interviewer]:** *"How do you implement Data-Driven Testing in Robot Framework? For example, testing the same flow with multiple inputs."*

**[Your Response]:**
"I use the built-in `Test Template` feature. I write one keyword that does the whole flow, for example `Login With Credentials`, and then under the `Test Cases` header I only list data rows (username, password, expected result). The same logic runs again for every row, so there is no copy-paste.

* **Ví dụ:** `valid/valid → Success`; `valid/wrong → 'Invalid password'`; `locked user → 'Account locked'`.
* **🧠 Nhớ nhanh:** 1 keyword + nhiều dòng dữ liệu = `Test Template`.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m4-essential-adb-commands-for-everyday-android-automation"></a>M4: Essential ADB Commands for Everyday Android Automation
**[Interviewer]:** *"Since you work a lot with Android automation, what are the most common ADB commands you use in your automation scripts?"*

**[Your Response]:**
"These are the commands I use most in automation:
* `adb devices` — check the device is connected and ready.
* `adb shell am start` / `am force-stop` — open or reset the app package.
* `adb shell input tap / text / keyevent` — simulate touches and typing when normal element locators fail.
* `adb logcat` — pull logs when a test fails, to attach evidence to the bug ticket.
* `adb push / pull` — copy config files into the phone or download screenshots out of it.

* **Ví dụ:** test treo ở màn hình loading → `adb logcat` để xem app báo lỗi gì trước khi log bug.
* **🧠 Nhớ nhanh:** Xem máy – Mở/tắt app – Chạm/gõ – Xem log – Copy file.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m5-handling-dynamic-ui-elements-without-hardcoded-sleeps"></a>M5: Handling Dynamic UI Elements Without Hardcoded Sleeps
**[Interviewer]:** *"How do you handle dynamic UI elements or elements that take time to load on Android devices?"*

**[Your Response]:**
"My rule is: no hard-coded sleeps like `Sleep 5s`, because they waste time and make tests flaky. I always use explicit waits. In Java/UIAutomator: `device.wait(Until.hasObject(...), timeout)`. In Robot Framework: `Wait Until Element Is Visible` or `Wait Until Page Contains Element` with a timeout. The test moves on the moment the element appears.

* **Ví dụ:** nút Login cần 2s để hiện → set timeout 10s → test đi tiếp sau 2s, không chờ đủ 10s.
* **🧠 Nhớ nhanh:** Không `Sleep` cứng — chỉ `Wait` có điều kiện.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m6-troubleshooting-local-pass-vs-jenkins-cicd-failures"></a>M6: Troubleshooting Local Pass vs. Jenkins CI/CD Failures
**[Interviewer]:** *"What is your approach when a test script passes on your local machine but fails randomly when running on the Jenkins node?"*

**[Your Response]:**
"Passing locally but failing on Jenkins usually means the environments are different. I check it in 3 steps:
1.  **Read the evidence:** open the Jenkins log and the failure screenshot to see what actually happened.
2.  **Compare environments:** screen size and rotation, network speed/limits, and ADB version or driver on the node.
3.  **Adjust waits:** if the Jenkins machine is shared and slower, the UI reacts slower, so I increase explicit timeouts for dynamic steps.

* **Ví dụ:** máy local màn hình 1080p, node Jenkins 720p → nút nằm ngoài màn hình → phải cuộn hoặc set cùng độ phân giải.
* **🧠 Nhớ nhanh:** Xem log/screenshot → so sánh môi trường → tăng timeout nếu máy yếu hơn.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m7-handling-authentication-tokens-in-python-api-testing"></a>M7: Handling Authentication Tokens in Python API Testing
**[Interviewer]:** *"When testing REST APIs with Python, how do you handle authentication tokens across multiple test steps?"*

**[Your Response]:**
"I use `requests.Session()`. I log in once with a POST request, take the token from the JSON response, and put it into the session headers: `session.headers.update({'Authorization': f'Bearer {token}'})`. From then on, every request using that session already carries the token, so I never add it manually again.

* **Ví dụ:** login → token `eyJhb...` → gán vào session → các request GET/POST sau không cần nhắc token.
* **🧠 Nhớ nhanh:** Login 1 lần → lấy token → nhét vào `session.headers` → xài lại cho mọi request.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m8-scripted-vs-declarative-jenkins-pipeline-choice"></a>M8: Scripted vs. Declarative Jenkins Pipeline Choice
**[Interviewer]:** *"What is the difference between a Scripted and a Declarative Jenkins Pipeline, and which one do you prefer for automation?"*

**[Your Response]:**
"I prefer Declarative pipelines. They must follow a fixed template inside a `pipeline {}` block, so they are easy to read and they have built-in `post {}` sections for success, failure, and cleanup. Scripted pipelines use free Groovy code: more flexible, but harder to read and maintain. For test automation, Declarative is enough and much clearer: Pull code → Compile → Run tests → Report.

* **Ví dụ:** `post { failure { slackSend ... } }` tự gửi cảnh báo khi test fail, không cần viết `try/catch`.
* **🧠 Nhớ nhanh:** Declarative = có khuôn, dễ đọc, có `post {}`; Scripted = Groovy tự do, khó bảo trì.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m9-regression-testing-under-extreme-timeline-constraints"></a>M9: Regression Testing Under Extreme Timeline Constraints
**[Interviewer]:** *"How do you perform Regression Testing when a minor bug fix is delivered, and the execution time is very limited?"*

**[Your Response]:**
"I do Impact Analysis instead of running everything. I ask the developer which files or modules were changed, then run only the test cases for those features plus the related upstream and downstream systems. I finish with the automated Smoke suite to confirm the system is still healthy.

* **Ví dụ:** fix nút 'Forgot Password' → test lại flow quên mật khẩu + gửi email + đăng nhập, rồi chạy smoke.
* **🧠 Nhớ nhanh:** Hỏi dev sửa gì → test đúng vùng đó + vùng liên quan → chạy smoke.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="m10-reopening-existing-bugs-vs-creating-new-defect-spinoffs"></a>M10: Reopening Existing Bugs vs. Creating New Defect Spinoffs
**[Interviewer]:** *"What do you do if a developer marks your bug as 'Fixed', but during retesting, you find the bug is still there, or it caused a new bug?"*

**[Your Response]:**
"There are two different cases:
1.  **The old bug is still there** → I do not create a new ticket. I Reopen the original Jira ticket with new logs and screenshots, and comment that the fix failed on this build.
2.  **The old bug is fixed but the change broke another feature** → I Close the original ticket to confirm that fix, and open a new bug ticket for the new regression. I link the two tickets for traceability.

* **Ví dụ:** bug login còn lỗi → Reopen; login hết lỗi nhưng nút Logout mới bị vỡ → ticket mới cho Logout + link với ticket cũ.
* **🧠 Nhớ nhanh:** Lỗi cũ còn → Reopen; lỗi mới do sửa → ticket mới + link.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

---

## PART 4: 30 CORE QUALITY ASSURANCE QUESTIONS & SMART ANSWERS

> **Cách học:** mỗi câu chỉ cần nhớ 2 phần — câu trả lời tiếng Anh (nói khi phỏng vấn) và dòng **🧠 Nhớ nhanh** (từ khóa tiếng Việt để nhắc lại).

### <a id="core-1-difference-between-sdlc-and-stlc"></a>CORE 1: Difference Between SDLC and STLC
**[Answer]:** "SDLC is the whole life of the software: plan, design, code, test, release, and maintain. STLC is only the testing part inside SDLC: read requirements, plan tests, write tests, run tests, then close testing. Simply put, SDLC is the whole journey and STLC is one stop in that journey."

* **Ví dụ:** SDLC giống xây cả căn nhà (từ bản vẽ đến bàn giao); STLC là bước kiểm tra chất lượng của căn nhà đó.
* **🧠 Nhớ nhanh:** SDLC = cả vòng đời; STLC = vòng đời của testing, chạy song song bên trong SDLC.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-2-verification-vs-validation"></a>CORE 2: Verification vs. Validation
**[Answer]:** "Verification asks: 'Are we building it right?' We check documents, requirements, and code without running the app — that is static testing. Validation asks: 'Are we building the right product?' We run the real software and use it like a user — that is dynamic testing."

* **Ví dụ:** Verification = đọc bản thiết kế xem đúng chuẩn chưa (chưa chạy gì). Validation = lắp xong cho người dùng chạy thử.
* **🧠 Nhớ nhanh:** Verification = *không chạy app*, chỉ đọc tài liệu; Validation = *phải chạy app* như người dùng thật.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-3-standard-fields-in-a-high-quality-test-case"></a>CORE 3: Standard Fields in a High-Quality Test Case
**[Answer]:** "A good test case has these fields: Test Case ID, Title, Pre-condition, Test Steps, Test Data, Expected Result, Actual Result, and Status (Pass / Fail / Blocked). For full traceability we add Priority, Severity, Module, Author, and Post-condition."

* **Ví dụ:** ID `TC-01` | Title `Login with valid account` | Pre-condition `user đã đăng ký` | Data `user1 / 123456` | Expected `vào trang Home` | Actual `vào trang Home` | Status `Pass`.
* **🧠 Nhớ nhanh:** nhớ theo dòng chảy: **Chuẩn bị → Làm → Dữ liệu → Mong đợi → Thực tế → Kết luận** (Pass/Fail/Blocked).

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-4-smoke-sanity-and-regression-testing-distinctions"></a>CORE 4: Smoke, Sanity, and Regression Testing Distinctions
**[Answer]:** "Smoke test runs on a new build to check the main features still work — it is broad but shallow. Sanity test runs after one small fix to check that area carefully — narrow but deep. Regression test runs after any code change to make sure the change did not break features that already worked."

* **Ví dụ:** Smoke = mở app, thử đăng nhập / thanh toán / tìm kiếm xem còn chạy. Sanity = chỉ test lại nút 'Forgot Password' vừa sửa. Regression = chạy lại bộ test cũ sau khi sửa.
* **🧠 Nhớ nhanh:** Smoke = build mới (rộng, nông); Sanity = sửa 1 chỗ (hẹp, sâu); Regression = sợ vỡ chỗ khác.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-5-severity-vs-priority-with-extreme-examples"></a>CORE 5: Severity vs. Priority with Extreme Examples
**[Answer]:** "Severity is how badly the bug breaks the system (technical impact). Priority is how soon the business needs it fixed (urgency). High Severity + Low Priority: the app crashes only when you type 10,000 characters into an optional field — very bad but very rare. Low Severity + High Priority: a typo in the company logo on the homepage — nothing breaks, but the brand looks bad, so it must be fixed now."

* **Ví dụ:** App crash khi nhập 10.000 ký tự = nặng nhưng hiếm → Severity cao, Priority thấp. Sai chính tả logo trang chủ = nhẹ nhưng ảnh hưởng thương hiệu → Severity thấp, Priority cao.
* **🧠 Nhớ nhanh:** Severity = *hỏng nặng đến đâu*; Priority = *phải sửa gấp đến đâu*. Nặng chưa chắc gấp, gấp chưa chắc nặng.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-6-core-states-in-a-standard-bug-life-cycle"></a>CORE 6: Core States in a Standard Bug Life Cycle
**[Answer]:** "A bug moves through these states: New (QA found it) → Assigned (given to a developer) → Open (the developer is working on it) → Fixed (developer says done) → Retest (QA checks again) → Verified (the fix works) → Closed (finished). If the fix fails, it goes back to Reopened. Other states are Deferred (fix later), Rejected (not accepted), and Cannot Reproduce."

* **Ví dụ:** giống xử lý khiếu nại: tiếp nhận → chuyển bộ phận → xử lý → trả lời → khách kiểm tra lại → đóng.
* **🧠 Nhớ nhanh:** **Mới → Giao → Mở → Sửa → Test lại → Xác nhận → Đóng**; fail thì Reopen.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-7-black-box-white-box-and-gray-box-testing"></a>CORE 7: Black-box, White-box, and Gray-box Testing
**[Answer]:** "Black-box: I only compare inputs and outputs with the requirements, and I know nothing about the code inside. White-box: I look inside the code — branches, loops, statements — usually developers do this with unit tests. Gray-box: in between — I know some internals such as the database or the architecture, but I still test from the outside."

* **Ví dụ:** Black-box = thử đồ hộp mà không biết công thức; White-box = biết rõ công thức từng bước; Gray-box = biết vài nguyên liệu chính nhưng không biết hết.
* **🧠 Nhớ nhanh:** Đen = không thấy code; Trắng = thấy hết code; Xám = thấy một phần.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-8-functional-vs-non-functional-testing-with-examples"></a>CORE 8: Functional vs. Non-functional Testing with Examples
**[Answer]:** "Functional testing checks WHAT the system does: does login work, does the payment go through, does search return results? Non-functional testing checks HOW WELL it does it: how fast (performance), how safe (security), and how easy to use (usability)."

* **Ví dụ:** Functional = đăng nhập đúng tài khoản có vào được không? Non-functional = đăng nhập mất bao lâu, có chặn brute force không?
* **🧠 Nhớ nhanh:** Functional = *LÀM ĐƯỢC GÌ*; Non-functional = *LÀM TỐT ĐẾN ĐÂU*.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-9-essential-components-of-a-great-bug-report"></a>CORE 9: Essential Components of a Great Bug Report
**[Answer]:** "A good bug report must be clear and actionable. It needs: a short clear Title; Steps to Reproduce; Expected result vs Actual result; Environment (OS, browser version, device); Severity and Priority; and Evidence such as screenshots, screen recording, or logs."

* **Ví dụ:** Title 'Login fails with valid account on Android 12' + 5 bước + 2 ảnh chụp + file `logcat`.
* **🧠 Nhớ nhanh:** **Tiêu đề – Bước – Mong đợi/Thực tế – Môi trường – Mức độ – Bằng chứng**.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-10-test-plan-vs-test-strategy-documents"></a>CORE 10: Test Plan vs. Test Strategy Documents
**[Answer]:** "A Test Strategy is a high-level document at company or program level. It is stable and says how we test in general: approach, tools, and standards. A Test Plan is a project-level document created from that strategy. For one release it describes the scope, schedule, people, risks, and deliverables."

* **Ví dụ:** Strategy = 'luật chơi chung của công ty'; Plan = 'kế hoạch cho đợt release này'.
* **🧠 Nhớ nhanh:** Strategy = cấp công ty, ít đổi; Plan = cấp dự án, đổi theo từng release.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-11-applying-bva-and-ep-on-age-field-18-60"></a>CORE 11: Applying BVA and EP on Age Field (18-60)
**[Answer]:** "With Boundary Value Analysis I test the edges: 17 (invalid low), 18 (valid minimum), 19 (valid), 59 (valid), 60 (valid maximum), 61 (invalid high). With Equivalence Partitioning I split inputs into groups and test one value from each group: valid 18–60, too low (<18), too high (>60), and wrong format (letters, symbols, negative number, empty)."

* **Ví dụ:** nhập 18 → OK; nhập 17 → báo lỗi; nhập 61 → báo lỗi; nhập 'abc' → báo lỗi.
* **🧠 Nhớ nhanh:** BVA = test đúng mép và sát mép; EP = test 1 giá trị đại diện cho cả nhóm.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-12-essential-test-cases-for-a-user-login-feature"></a>CORE 12: Essential Test Cases for a User Login Feature
**[Answer]:** "Login needs more than correct and wrong passwords. I also test: SQL Injection and XSS; brute force protection (account locks after N failed attempts); password is case-sensitive; Remember Me; session timeout; login from many devices at the same time; social login (Google/Facebook); Forgot Password flow; and the layout on small screens."

* **Ví dụ:** nhập sai mật khẩu 5 lần → tài khoản bị khóa 15 phút.
* **🧠 Nhớ nhanh:** 5 nhóm — **Chức năng – Bảo mật – Phiên đăng nhập – Nhiều thiết bị – Giao diện**.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-13-handling-cannot-reproduce-feedback-professionally"></a>CORE 13: Handling 'Cannot Reproduce' Feedback Professionally
**[Answer]:** "I stay friendly, never defensive. First, I re-read my bug report to check the steps, test data, and environment are clear. Then I share a recording or the logs. If it still cannot be reproduced, I debug together with the developer on their machine. Finally, if it only happens in a special environment, I write those exact conditions into the ticket."

* **Ví dụ:** bug chỉ xảy ra trên Android 11 → ghi rõ model, phiên bản OS, phiên bản app vào ticket.
* **🧠 Nhớ nhanh:** Kiểm tra lại report → gửi bằng chứng → debug cùng nhau → ghi lại điều kiện đặc biệt.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-14-determining-when-to-stop-testing-exit-criteria"></a>CORE 14: Determining When to Stop Testing (Exit Criteria)
**[Answer]:** "Testing is endless, so we agree Exit Criteria in advance and stop when they are met: all high-priority test cases executed, coverage target reached, open defects below the allowed limit, the deadline reached, and stakeholders accepting the remaining risk."

* **Ví dụ:** '0 bug Critical, còn ≤ 5 bug Minor, chạy 100% test P1 → được dừng'.
* **🧠 Nhớ nhanh:** Đủ test → đủ coverage → ít bug → hết thời gian → có người ký nhận rủi ro.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-15-standard-bug-tracking-workflow-inside-jira"></a>CORE 15: Standard Bug Tracking Workflow Inside Jira
**[Answer]:** "I log the defect in Jira with clear steps, evidence, and environment. I set the Epic, Component, Severity, and Priority, then assign it to the dev team. When it is marked Fixed, I pull the latest build, retest it, attach the new evidence, and close the ticket."

* **Ví dụ:** ticket đang ở trạng thái Fixed → QA retest → Pass → chuyển sang Closed kèm ảnh chụp mới.
* **🧠 Nhớ nhanh:** **Log → Gán → Fix → Retest → Đóng**.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-16-verifying-get-post-put-delete-and-http-status-codes"></a>CORE 16: Verifying GET, POST, PUT, DELETE and HTTP Status Codes
**[Answer]:** "For GET I check the data comes back correctly, with filters and pagination working. For POST I check required fields, wrong data types, and duplicate prevention. For PUT I check the update really changes the data. For DELETE I check the item is gone and that deleting a non-existent item gives a clear error. Common status codes: 200 OK, 201 Created, 204 No Content, 400 Bad Request, 401 Unauthorized, 403 Forbidden, 404 Not Found, 409 Conflict, and 500 Internal Server Error."

* **Ví dụ:** POST thiếu email → 400 Bad Request; POST trùng email → 409 Conflict; DELETE id không tồn tại → 404.
* **🧠 Nhớ nhanh:** **GET = đọc, POST = tạo, PUT = sửa, DELETE = xóa**; mã: 2xx thành công, 4xx lỗi phía client, 5xx lỗi server.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-17-focus-areas-and-tools in-responsive-web-testing"></a>CORE 17: Focus Areas and Tools in Responsive Web Testing
**[Answer]:** "I check the layout at each breakpoint (mobile, tablet, desktop), touch events, screen rotation, font scaling, image rendering, and the menu changing into a hamburger icon. For tools I use Chrome DevTools for quick checks, BrowserStack for many real devices, and a real phone for final confirmation."

* **Ví dụ:** màn 375px thì menu phải thành hamburger; màn 1440px thì menu nằm ngang.
* **🧠 Nhớ nhanh:** Bố cục – Cảm ứng – Xoay màn hình – Chữ/hình – Menu. Tools: DevTools + BrowserStack + máy thật.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-18-cross-browser-testing-and-browser-selection-criteria"></a>CORE 18: Cross-Browser Testing and Browser Selection Criteria
**[Answer]:** "It is necessary because browsers use different rendering engines, so the same CSS, HTML, and JS can behave differently. I do not guess: I pick browsers using real data about our users from Google Analytics or StatCounter. Usually we support the latest 2 versions of Chrome, Safari, Edge, and Firefox."

* **Ví dụ:** nút Submit bị lệch 2px trên Safari — chỉ phát hiện khi test trên Safari.
* **🧠 Nhớ nhanh:** Khác engine → khác kết quả; chọn browser theo dữ liệu người dùng thật, không đoán.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-19-handling-200-unexecuted-test-cases-with-a-1-day-deadline"></a>CORE 19: Handling 200 Unexecuted Test Cases with a 1-Day Deadline
**[Answer]:** "I switch to Risk-Based Testing. I run only the critical smoke tests, the main end-to-end user flows, and regression tests for the modules changed recently. Then I report clearly to the PM: what was tested, what was not, and what risks are left, so the business can decide."

* **Ví dụ:** 200 case còn lại → chọn 30 case quan trọng nhất (đăng nhập, thanh toán, đặt hàng) để chạy trước.
* **🧠 Nhớ nhanh:** Smoke → luồng chính → module vừa thay đổi → báo cáo minh bạch.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-20-test-cases-for-an-e-commerce-add-to-cart-feature"></a>CORE 20: Test Cases for an E-commerce 'Add to Cart' Feature
**[Answer]:** "I test: adding quantity 1, many, 0, negative, and more than stock; adding an out-of-stock item; guest checkout; the cart still there after logout and login; price updates when a promo code is applied; cart syncing between 2 browser tabs; and response time with a very large cart."

* **Ví dụ:** thêm 5 sản phẩm khi kho chỉ còn 3 → hệ thống phải báo 'chỉ còn 3'.
* **🧠 Nhớ nhanh:** Số lượng – Tồn kho – Khách/Guest – Đăng nhập lại – Khuyến mãi – Đồng bộ tab – Hiệu năng.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-21-allocating-testing-scope-for-5-pm-build-releasing-at-9-am"></a>CORE 21: Allocating Testing Scope for 5 PM Build Releasing at 9 AM
**[Answer]:** "First I run a quick Smoke Test to confirm the app is not broken. Then I use Impact Analysis: I find the modules changed by the latest commits and run regression tests only on those modules and their related features. I do not rush through everything. Before I leave, I send a short status report: what was tested, what was skipped, and what risks remain."

* **Ví dụ:** build chỉ sửa phần thanh toán → test thanh toán + đơn hàng liên quan, bỏ qua module chat không đổi.
* **🧠 Nhớ nhanh:** Smoke nhanh → Impact Analysis → báo cáo trước khi về.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-22-retesting-vs-regression-suite-scope-optimization"></a>CORE 22: Retesting vs. Regression Suite Scope Optimization
**[Answer]:** "Retesting means checking the exact bug I reported, to confirm it is really fixed. Regression means checking that this fix did not break other features. When the regression suite gets too big, I prioritize with Impact Analysis and Risk-Based selection, and I automate the stable, repetitive cases so they run in the pipeline."

* **Ví dụ:** Retest = login đã OK chưa; Regression = sau khi sửa login, nút Logout có còn chạy?
* **🧠 Nhớ nhanh:** Retest = *'bug của tôi đã hết chưa?'*; Regression = *'sửa nó có làm vỡ chỗ khác không?'*.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-23-handling-critical-defects-releasing-with-pm-approval"></a>CORE 23: Handling Critical Defects Releasing with PM Approval
**[Answer]:** "My job is to show the risk, not to block the release. I document the bug clearly in Jira — impact, how to reproduce, effect on users — and email the stakeholders so there is an audit trail. When the PM officially accepts the risk and signs off, I help prepare a hotfix for after the release."

* **Ví dụ:** bug chỉ ảnh hưởng 1% người dùng iOS cũ → PM ký chấp nhận → release, kèm kế hoạch hotfix.
* **🧠 Nhớ nhanh:** Ghi rõ rủi ro → để PM ký nhận → chuẩn bị hotfix.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-24-comprehensive-test-scenarios-for-a-file-upload-component"></a>CORE 24: Comprehensive Test Scenarios for a File Upload Component
**[Answer]:** "I test: valid and invalid extensions; size cases (0 KB, exact maximum, over maximum); file names with special characters or very long names; corrupted files; malware scanning with an Eicar test file; fake MIME type (rename .exe to .png); network lost in the middle of an upload; many files at once; and cancelling an upload."

* **Ví dụ:** upload file 0 KB → hệ thống phải báo lỗi rõ ràng, không được treo.
* **🧠 Nhớ nhanh:** Loại file – Kích thước – Tên file – File lỗi/virus – Giả MIME – Mạng – Nhiều file – Hủy.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-25-comprehensive-test-cases-for-a-website-search-box"></a>CORE 25: Comprehensive Test Cases for a Website Search Box
**[Answer]:** "I test empty search, one character, the maximum length, spaces before and after the keyword, SQLi and XSS strings, special characters, Vietnamese with accents, copy-paste, autocomplete timing, recent search history, and speed under heavy load."

* **Ví dụ:** gõ `  tai nghe  ` (có khoảng trắng 2 đầu) → kết quả phải giống `tai nghe`.
* **🧠 Nhớ nhanh:** Rỗng – 1 ký tự – Dài nhất – Khoảng trắng – Bảo mật – Ký tự đặc biệt – Gợi ý – Hiệu năng.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-26-handling-defect-rejections-marked-as-not-a-bug"></a>CORE 26: Handling Defect Rejections Marked as 'Not a Bug'
**[Answer]:** "I check the requirement or user story first. If the specification is on my side, I reopen the ticket and attach the document, or ask the BA to confirm. If the specification is unclear, I book a quick call with the developer and the BA to agree on the correct behaviour, then we update the documentation."

* **Ví dụ:** spec ghi 'mật khẩu tối thiểu 8 ký tự' nhưng app cho nhập 6 → reopen ticket + link spec.
* **🧠 Nhớ nhanh:** Xem yêu cầu → có bằng chứng thì reopen + gắn link → chưa rõ thì họp 3 bên (Dev–BA–QA) → cập nhật tài liệu.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-27-test-scenario-vs-test-case-allocation-strategies"></a>CORE 27: Test Scenario vs. Test Case Allocation Strategies
**[Answer]:** "A Test Scenario says WHAT to test, in one line: 'Validate user checkout'. A Test Case says HOW to test: steps, test data, and expected result. I use scenarios in fast Agile sprints where the team knows the domain well. I write full test cases for regulated fields like automotive or finance, where we need a clear audit trail."

* **Ví dụ:** Scenario = 'Kiểm tra đăng nhập'; Test Case = `TC-01` với 5 bước, dữ liệu, kết quả mong đợi.
* **🧠 Nhớ nhanh:** Scenario = *cái gì* (1 câu); Test Case = *làm thế nào* (từng bước).

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-28-testing-a-feature-with-absolute-zero-documentation"></a>CORE 28: Testing a Feature with Absolute Zero Documentation
**[Answer]:** "I combine 4 things: exploratory testing to learn the feature by using it; product and competitor analysis to see the standard flow; short interviews with the developer and the Product Owner; then I write down my assumptions and test criteria and ask the team to confirm them before I execute."

* **Ví dụ:** chưa có tài liệu → tự khám phá app, so sánh với app cùng loại, hỏi PO, viết giả định gửi team xác nhận.
* **🧠 Nhớ nhanh:** Khám phá → xem sản phẩm tương tự → hỏi Dev/PO → ghi giả định và xác nhận.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-29-performance-load-stress-and-spike-testing-metrics"></a>CORE 29: Performance, Load, Stress, and Spike Testing Metrics
**[Answer]:** "Performance testing checks the system under normal conditions. Load testing checks it at the expected peak user volume. Stress testing pushes it past the limit to find the breaking point. Spike testing checks what happens with a sudden huge traffic increase and then a sharp drop. Key metrics: throughput (requests per second), error rate, CPU and RAM usage, and the 95th/99th percentile response time, which is more honest than an average."

* **Ví dụ:** 1000 người dùng cùng lúc → xem P95 response time và error rate, không chỉ xem trung bình.
* **🧠 Nhớ nhanh:** Bình thường – Cao điểm – Quá tải – Sốc; Metrics: Throughput, Error rate, CPU/RAM, P95/P99.

_**[⬆ Back to Table of Contents](#table-of-contents)**_

### <a id="core-30-processing-severe-security-flaws-and-data-exposure"></a>CORE 30: Processing Severe Security Flaws and Data Exposure
**[Answer]:** "This is a serious security issue, so I act quietly and ethically. I never screenshot real customer data (PII), and I never discuss the issue on public or open channels. I reproduce it with dummy accounts, log a confidential Jira ticket, and tell the Security Lead and the PM immediately."

* **Ví dụ:** API trả về thông tin của người dùng khác → dùng tài khoản test, không chụp dữ liệu thật, báo Security ngay.
* **🧠 Nhớ nhanh:** Không chụp dữ liệu thật → test bằng tài khoản giả → ticket bảo mật → báo Security Lead + PM ngay.

_**[⬆ Back to Table of Contents](#table-of-contents)**_
