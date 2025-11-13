# Jenkins Execution Log

## Build Information
- **Job Name:** `MBP_Github_Polaris_Simplified_Workflow/main`
- **Build Number:** #2
- **Build Status:** 🟢 **SUCCESS**
- **Duration:** 6 min 59 sec and counting
- **Timestamp:** 2025-11-13 13:34:35 UTC

---

## Console Output

```
Branch indexing
Connecting to https://api.github.com using madhusud@blackduck.com/****** (Github_Username_PAT)
Obtained nodejs-npm/Jenkinsfile from 577f3e6faf9c704aaca9552e7b995767f2e6195d
Loading library blackduck-logs-publisher@main
Attempting to resolve main from remote references...
 > git --version # timeout=10
 > git --version # 'git version 2.39.5 (Apple Git-154)'
using GIT_ASKPASS to set credentials Github_Username_PAT
 > git ls-remote -h -- https://github.com/integrations-garage/blackduck-logs-publisher # timeout=10
Found match: refs/heads/main revision e969196a63b1be83b84541b022f7aa52928bd5e5
The recommended git tool is: NONE
using credential Github_Username_PAT
 > git rev-parse --resolve-git-dir /Users/madhusud/.jenkins/workspace/Polaris_Simplified_Workflow_main@libs/a0dda568bac7bbb4a171f59ba3f2660c21c69edc6356524e9ae8bb4500c12bbb/.git # timeout=10
Fetching changes from the remote Git repository
 > git config remote.origin.url https://github.com/integrations-garage/blackduck-logs-publisher # timeout=10
Fetching without tags
Fetching upstream changes from https://github.com/integrations-garage/blackduck-logs-publisher
 > git --version # timeout=10
 > git --version # 'git version 2.39.5 (Apple Git-154)'
using GIT_ASKPASS to set credentials Github_Username_PAT
 > git fetch --no-tags --force --progress -- https://github.com/integrations-garage/blackduck-logs-publisher +refs/heads/*:refs/remotes/origin/* # timeout=10
Checking out Revision e969196a63b1be83b84541b022f7aa52928bd5e5 (main)
 > git config core.sparsecheckout # timeout=10
 > git checkout -f e969196a63b1be83b84541b022f7aa52928bd5e5 # timeout=10
Commit message: "Phase 3 - 2"
 > git rev-list --no-walk e969196a63b1be83b84541b022f7aa52928bd5e5 # timeout=10
[Pipeline] Start of Pipeline
[Pipeline] node
Running on mac-sh in /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2
[Pipeline] {
[Pipeline] stage
[Pipeline] { (Declarative: Checkout SCM)
[Pipeline] checkout
The recommended git tool is: NONE
using credential Github_Username_PAT
Cloning the remote Git repository
Cloning with configured refspecs honoured and without tags
Cloning repository https://github.com/polaris-jenkins-samples/simplified-example.git
 > git init /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2 # timeout=10
Fetching upstream changes from https://github.com/polaris-jenkins-samples/simplified-example.git
 > git --version # timeout=10
 > git --version # 'git version 2.39.5 (Apple Git-154)'
using GIT_ASKPASS to set credentials Github_Username_PAT
 > git fetch --no-tags --force --progress -- https://github.com/polaris-jenkins-samples/simplified-example.git +refs/heads/main:refs/remotes/origin/main # timeout=10
Avoid second fetch
Checking out Revision 577f3e6faf9c704aaca9552e7b995767f2e6195d (main)
Commit message: "Polaris Simplified Workflow"
First time build. Skipping changelog.
 > git config remote.origin.url https://github.com/polaris-jenkins-samples/simplified-example.git # timeout=10
 > git config --add remote.origin.fetch +refs/heads/main:refs/remotes/origin/main # timeout=10
 > git config core.sparsecheckout # timeout=10
 > git checkout -f 577f3e6faf9c704aaca9552e7b995767f2e6195d # timeout=10
[Pipeline] }
[Pipeline] // stage
[Pipeline] withEnv
[Pipeline] {
[Pipeline] stage
[Pipeline] { (Build)
[Pipeline] script
[Pipeline] {
[Pipeline] echo
JOB_NAME: MBP_Github_Polaris_Simplified_Workflow/main
[Pipeline] dir
Running in /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm
[Pipeline] {
[Pipeline] sh
+ node --version
v22.16.0
[Pipeline] sh
+ npm --version
10.9.2
[Pipeline] sh
+ npm install
npm warn deprecated fsevents@1.2.9: fsevents 1 will break on node v14+ and could be using insecure binaries. Upgrade to fsevents 2.
npm warn deprecated set-value@2.0.0: Critical bug fixed in v3.0.1, please upgrade to the latest version.
npm warn deprecated mixin-deep@1.3.1: Critical bug fixed in v2.0.1, please upgrade to the latest version.
npm warn deprecated ini@1.3.5: Please update to ini >=1.3.6 to avoid a prototype pollution issue
npm warn deprecated set-value@0.4.3: Critical bug fixed in v3.0.1, please upgrade to the latest version.
npm warn deprecated path-is-absolute@2.0.0: This package is no longer relevant as Node.js 0.12 is unmaintained.
npm warn deprecated urix@0.1.0: Please see https://github.com/lydell/urix#deprecated
npm warn deprecated har-validator@5.1.3: this library is no longer supported
npm warn deprecated to-iso-string@0.0.2: to-iso-string has been deprecated, use @segment/to-iso-string instead.
npm warn deprecated cryptiles@2.0.5: This version has been deprecated in accordance with the hapi support policy (hapi.im/support). Please upgrade to the latest version to get the best features, bug fixes, and security patches. If you are unable to upgrade at this time, paid support is available for older versions (hapi.im/commercial).
npm warn deprecated resolve-url@0.2.1: https://github.com/lydell/resolve-url#deprecated
npm warn deprecated bcrypt-nodejs@0.0.3: bcrypt-nodejs is no longer actively maintained. Please use bcrypt or bcryptjs. See https://github.com/kelektiv/node.bcrypt.js/wiki/bcrypt-vs-brypt.js to learn more about these two options
npm warn deprecated cryptiles@0.2.2: This version has been deprecated in accordance with the hapi support policy (hapi.im/support). Please upgrade to the latest version to get the best features, bug fixes, and security patches. If you are unable to upgrade at this time, paid support is available for older versions (hapi.im/commercial).
npm warn deprecated source-map-url@0.4.0: See https://github.com/lydell/source-map-url#deprecated
npm warn deprecated boom@0.4.2: This version has been deprecated in accordance with the hapi support policy (hapi.im/support). Please upgrade to the latest version to get the best features, bug fixes, and security patches. If you are unable to upgrade at this time, paid support is available for older versions (hapi.im/commercial).
npm warn deprecated debug@3.2.6: Debug versions >=3.2.0 <3.2.7 || >=4 <4.3.1 have a low-severity ReDos regression when used in a Node.js environment. It is recommended you upgrade to 3.2.7 or 4.3.1. (https://github.com/visionmedia/debug/issues/797)
npm warn deprecated debug@3.2.6: Debug versions >=3.2.0 <3.2.7 || >=4 <4.3.1 have a low-severity ReDos regression when used in a Node.js environment. It is recommended you upgrade to 3.2.7 or 4.3.1. (https://github.com/visionmedia/debug/issues/797)
npm warn deprecated debug@3.2.6: Debug versions >=3.2.0 <3.2.7 || >=4 <4.3.1 have a low-severity ReDos regression when used in a Node.js environment. It is recommended you upgrade to 3.2.7 or 4.3.1. (https://github.com/visionmedia/debug/issues/797)
npm warn deprecated debug@3.2.6: Debug versions >=3.2.0 <3.2.7 || >=4 <4.3.1 have a low-severity ReDos regression when used in a Node.js environment. It is recommended you upgrade to 3.2.7 or 4.3.1. (https://github.com/visionmedia/debug/issues/797)
npm warn deprecated chokidar@2.1.6: Chokidar 2 does not receive security updates since 2019. Upgrade to chokidar 3 with 15x fewer dependencies
npm warn deprecated boom@2.10.1: This version has been deprecated in accordance with the hapi support policy (hapi.im/support). Please upgrade to the latest version to get the best features, bug fixes, and security patches. If you are unable to upgrade at this time, paid support is available for older versions (hapi.im/commercial).
npm warn deprecated sntp@0.2.4: This module moved to @hapi/sntp. Please make sure to switch over as this distribution is no longer supported and may contain bugs and critical security issues.
npm warn deprecated minimatch@0.3.0: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm warn deprecated chokidar@2.1.8: Chokidar 2 does not receive security updates since 2019. Upgrade to chokidar 3 with 15x fewer dependencies
npm warn deprecated sntp@1.0.9: This module moved to @hapi/sntp. Please make sure to switch over as this distribution is no longer supported and may contain bugs and critical security issues.
npm warn deprecated querystring@0.2.0: The querystring API is considered Legacy. new code should use the URLSearchParams API instead.
npm warn deprecated request@2.36.0: request has been deprecated, see https://github.com/request/request/issues/3142
npm warn deprecated mkdirp@0.3.0: Legacy versions of mkdirp are no longer supported. Please update to mkdirp 1.x. (Note that the API surface has changed to use Promises in 1.x.)
npm warn deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm warn deprecated hoek@0.9.1: This version has been deprecated in accordance with the hapi support policy (hapi.im/support). Please upgrade to the latest version to get the best features, bug fixes, and security patches. If you are unable to upgrade at this time, paid support is available for older versions (hapi.im/commercial).
npm warn deprecated node-uuid@1.4.8: Use uuid module instead
npm warn deprecated node-uuid@1.4.8: Use uuid module instead
npm warn deprecated uuid@3.3.2: Please upgrade  to version 7 or higher.  Older versions may use Math.random() in certain circumstances, which is known to be problematic.  See https://v8.dev/blog/math-random for details.
npm warn deprecated source-map-resolve@0.5.2: See https://github.com/lydell/source-map-resolve#deprecated
npm warn deprecated har-validator@2.0.6: this library is no longer supported
npm warn deprecated mkdirp@0.5.1: Legacy versions of mkdirp are no longer supported. Please update to mkdirp 1.x. (Note that the API surface has changed to use Promises in 1.x.)
npm warn deprecated hoek@2.16.3: This version has been deprecated in accordance with the hapi support policy (hapi.im/support). Please upgrade to the latest version to get the best features, bug fixes, and security patches. If you are unable to upgrade at this time, paid support is available for older versions (hapi.im/commercial).
npm warn deprecated request@2.79.0: request has been deprecated, see https://github.com/request/request/issues/3142
npm warn deprecated request@2.88.0: request has been deprecated, see https://github.com/request/request/issues/3142
npm warn deprecated request@2.67.0: request has been deprecated, see https://github.com/request/request/issues/3142
npm warn deprecated readdir-scoped-modules@1.0.2: This functionality has been moved to @npmcli/fs
npm warn deprecated hawk@1.0.0: This module moved to @hapi/hawk. Please make sure to switch over as this distribution is no longer supported and may contain bugs and critical security issues.
npm warn deprecated hawk@3.1.3: This module moved to @hapi/hawk. Please make sure to switch over as this distribution is no longer supported and may contain bugs and critical security issues.
npm warn deprecated jade@0.26.3: Jade has been renamed to pug, please install the latest version of pug instead of jade
npm warn deprecated swig@1.4.2: This package is no longer maintained
npm warn deprecated bson@1.0.9: Fixed a critical issue with BSON serialization documented in CVE-2019-2391, see https://bit.ly/2KcpXdo for more details
npm warn deprecated nodeunit@0.9.5: you are strongly encouraged to use other testing options

added 962 packages, and audited 1412 packages in 11s

32 packages are looking for funding
  run `npm fund` for details

137 vulnerabilities (9 low, 35 moderate, 57 high, 36 critical)

To address issues that do not require attention, run:
  npm audit fix

To address all issues possible (including breaking changes), run:
  npm audit fix --force

Some issues need review, and may require choosing
a different dependency.

Run `npm audit` for details.
[Pipeline] }
[Pipeline] // dir
[Pipeline] }
[Pipeline] // script
[Pipeline] }
[Pipeline] // stage
[Pipeline] stage
[Pipeline] { (polaris-simplified-workflow)
[Pipeline] script
[Pipeline] {
[Pipeline] dir
Running in /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm
[Pipeline] {
[Pipeline] security_scan
**************************** START EXECUTION OF BLACK DUCK SECURITY SCAN ****************************
[Security Scan] INFO: Jenkins Job name: MBP_Github_Polaris_Simplified_Workflow
-------------------------------- Connection to node --------------------------------
[Security Scan] INFO: Jenkins job is running on agent node remotely
-------------------------- Parameter Validation Initiated --------------------------
[Security Scan] INFO:  --- product = [POLARIS]
[Security Scan] INFO: Parameters for polaris:
[Security Scan] INFO:  --- polaris_waitForScan = true
[Security Scan] INFO:  --- polaris_server_url = https://poc.polaris.blackduck.com
[Security Scan] INFO:  --- polaris_assessment_types = SAST,SCA
[Security Scan] INFO:  --- polaris_access_token = ******************************************************************************
[Security Scan] INFO:  --- polaris_prComment_enabled = true
[Security Scan] INFO:  --- polaris_reports_sarif_groupSCAIssues = true
[Security Scan] INFO:  --- polaris_reports_sarif_create = true
[Security Scan] INFO:  --- polaris_test_sca_location = hybrid
[Security Scan] INFO:  --- polaris_test_sast_location = hybrid
------------------------------------------------------------------------------------
[Security Scan] INFO: Parameters for additional configuration:
[Security Scan] INFO:  --- network_airgap = false
[Security Scan] INFO: Polaris parameters are validated successfully
[Security Scan] INFO: Bridge download parameters are validated successfully
[Security Scan] INFO: Bridge download is not required. Found installed in: /Users/madhusud/bridge-cli-bundle/bridge-cli-bundle-macos_arm
------------------------------------------------------------------------------------
[Security Scan] INFO: Bridge CLI version is - 3.9.2
[Security Scan] INFO: Jenkins Job name: MBP_Github_Polaris_Simplified_Workflow
[Security Scan] INFO: Polaris Application Name: simplified-example
[Security Scan] INFO: Polaris Project Name: simplified-example
[Security Scan] INFO: Polaris Branch Name: main
[Security Scan] INFO: Polaris PR Comment is ignored for non pull request scan
[Security Scan] INFO: Jenkins Job name: MBP_Github_Polaris_Simplified_Workflow
[Security Scan] INFO: Executable command line arguments: /Users/madhusud/bridge-cli-bundle/bridge-cli-bundle-macos_arm/bridge-cli --stage polaris --input /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/polaris_input11344531798183720230.json --out .bridge/output/scan_info_out.json

******************************* START EXECUTION OF BRIDGE CLI *******************************
2025-11-13 13:28:01.1476 IST [Bridge CLI] INFO: Using cache directory: /Users/madhusud/bridge-cli-bundle/bridge-cli-bundle-macos_arm
2025-11-13 13:28:01.1528 IST [Bridge CLI] INFO: Found version "3.0.371" in registry for workflow "polaris", trying to load it from local cache
2025-11-13 13:28:02.4447 IST [Bridge CLI] INFO: Input Resources:
2025-11-13 13:28:02.4448 IST [Bridge CLI] INFO: resource = value [source]
2025-11-13 13:28:02.4448 IST [Bridge CLI] INFO: ------------------------------------------------------------
2025-11-13 13:28:02.4448 IST [Bridge CLI] INFO: network.airgap = false [polaris_input11344531798183720230.json]
2025-11-13 13:28:02.4448 IST [Bridge CLI] INFO: polaris.accesstoken = ***************************************** [polaris_input11344531798183720230.json]
2025-11-13 13:28:02.4448 IST [Bridge CLI] INFO: polaris.application.name = simplified-example [polaris_input11344531798183720230.json]
2025-11-13 13:28:02.4448 IST [Bridge CLI] INFO: polaris.assessment.types = [SAST SCA] [polaris_input11344531798183720230.json]
2025-11-13 13:28:02.4448 IST [Bridge CLI] INFO: polaris.branch.name = main [polaris_input11344531798183720230.json]
2025-11-13 13:28:02.4448 IST [Bridge CLI] INFO: polaris.project.name = simplified-example [polaris_input11344531798183720230.json]
2025-11-13 13:28:02.4448 IST [Bridge CLI] INFO: polaris.reports.sarif.create = true [polaris_input11344531798183720230.json]
2025-11-13 13:28:02.4449 IST [Bridge CLI] INFO: polaris.reports.sarif.file.path = .blackduck/integrations/polaris/sarif/report.sarif.json [polaris_input11344531798183720230.json]
2025-11-13 13:28:02.4449 IST [Bridge CLI] INFO: polaris.reports.sarif.groupSCAIssues = true [polaris_input11344531798183720230.json]
2025-11-13 13:28:02.4449 IST [Bridge CLI] INFO: polaris.serverUrl = https://poc.polaris.blackduck.com [polaris_input11344531798183720230.json]
2025-11-13 13:28:02.4449 IST [Bridge CLI] INFO: polaris.test.sast.location = hybrid [polaris_input11344531798183720230.json]
2025-11-13 13:28:02.4449 IST [Bridge CLI] INFO: polaris.test.sca.location = hybrid [polaris_input11344531798183720230.json]
2025-11-13 13:28:02.4449 IST [Bridge CLI] INFO: polaris.waitForScan = true [polaris_input11344531798183720230.json]
2025-11-13 13:28:02.4449 IST [Bridge CLI] INFO: ------------------------------------------------------------
2025-11-13 13:28:02.4449 IST [Bridge CLI] INFO: Starting adapters for stage polaris
2025-11-13 13:28:02.4466 IST [Bridge CLI] INFO: Starting Adapter: Polaris Status Provider
2025-11-13 13:28:02.4466 IST [Bridge CLI] INFO: Starting Adapter: Polaris Initializer
2025-11-13 13:28:02.4466 IST [Bridge CLI] INFO: Starting Adapter: Polaris SCM Discovery
2025-11-13 13:28:02.4466 IST [Bridge CLI] INFO: Starting Adapter: Polaris Controller
2025-11-13 13:28:02.5053 IST [Polaris SCM Discovery] INFO: Adapter finished
2025-11-13 13:28:02.5092 IST [Bridge CLI] INFO: Starting Adapter: Set Polaris Assessment Mode to CI
2025-11-13 13:28:02.5093 IST [Set Polaris Assessment Mode to CI] INFO: Provided value for resource 'polaris.assessment.mode'
2025-11-13 13:28:02.5093 IST [Set Polaris Assessment Mode to CI] INFO: Adapter finished
2025-11-13 13:28:02.5129 IST [Bridge CLI] INFO: Starting Adapter: Create Polaris Project & Branch By Default
2025-11-13 13:28:02.5130 IST [Create Polaris Project & Branch By Default] INFO: Provided value for resource 'polaris.onboarding'
2025-11-13 13:28:02.5131 IST [Create Polaris Project & Branch By Default] INFO: Adapter finished
2025-11-13 13:28:04.9015 IST [Polaris Initializer] INFO: Successfully created test for "SCA(scaPackage)" assessment. The short test ID is "7A42PMH"
2025-11-13 13:28:04.9219 IST [Polaris Initializer] INFO: Successfully created test for "SAST(sastFull)" assessment. The short test ID is "Y1QIJ3U"
2025-11-13 13:28:04.9289 IST [Polaris Initializer] INFO: Provided value for resource 'polaris.test.SAST.tests.sastFull.id'
2025-11-13 13:28:04.9295 IST [Polaris Initializer] INFO: Provided value for resource 'polaris.test.SCA.tests.scaPackage.id'
2025-11-13 13:28:04.9297 IST [Polaris Initializer] INFO: Provided value for resource 'polaris.test.SAST.tests.sastFull.shortId'
2025-11-13 13:28:04.9298 IST [Polaris Initializer] INFO: Provided value for resource 'polaris.test.SCA.tests.scaPackage.shortId'
2025-11-13 13:28:04.9300 IST [Polaris Initializer] INFO: Provided value for resource 'polaris.test.SAST.tests.sastFull.streamId'
2025-11-13 13:28:04.9301 IST [Polaris Initializer] INFO: Provided value for resource 'polaris.project.id'
2025-11-13 13:28:04.9302 IST [Polaris Initializer] INFO: Provided value for resource 'polaris.branch.id'
2025-11-13 13:28:04.9303 IST [Polaris Initializer] INFO: Provided value for resource 'polaris.portfolioid'
2025-11-13 13:28:04.9304 IST [Polaris Initializer] INFO: Provided value for resource 'polaris.tenant.id'
2025-11-13 13:28:04.9305 IST [Polaris Initializer] INFO: Provided value for resource 'polaris.application.id'
2025-11-13 13:28:04.9308 IST [Polaris Initializer] INFO: Adapter finished
2025-11-13 13:28:04.9425 IST [Bridge CLI] INFO: Starting Adapter: Check pull request
2025-11-13 13:28:04.9661 IST [Check pull request] INFO: Provided value for resource 'environment.scan.pull'
2025-11-13 13:28:04.9663 IST [Check pull request] INFO: Adapter finished
2025-11-13 13:28:04.9917 IST [Polaris Controller] INFO: Running for "sca" assessment with scan type "scaPackage"
2025-11-13 13:28:04.9919 IST [Polaris Controller] INFO: fetching recommended "detect" tool info...
2025-11-13 13:28:05.8001 IST [Polaris Controller] INFO: checking "detect" tool installation inside bridge home directory: /Users/madhusud/.blackduck/bridge/tools/blackduck-detect/10.4.0
2025-11-13 13:28:05.8001 IST [Polaris Controller] INFO: Running command:/Library/Java/JavaVirtualMachines/jdk-21.jdk/Contents/Home/bin/java -version
2025-11-13 13:28:05.8454 IST [Polaris Controller] INFO: Checking tool version for "detect" in "/Users/madhusud/.blackduck/bridge/tools/blackduck-detect/10.4.0"
2025-11-13 13:28:05.8478 IST [Polaris Controller] INFO: Got tool version for "detect": 10.4.0
2025-11-13 13:28:06.1368 IST [Polaris Controller] INFO: "detect" tool is already installed...
2025-11-13 13:28:06.1369 IST [Polaris Controller] INFO: Running for "sast" assessment with scan type "sastFull"
2025-11-13 13:28:06.1369 IST [Polaris Controller] INFO: fetching recommended "coverity" tool info...
2025-11-13 13:28:06.4189 IST [Polaris Controller] INFO: checking "coverity" tool installation inside bridge home directory: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0
2025-11-13 13:28:06.4189 IST [Polaris Controller] INFO: Checking tool version for "cov_thin_client" in "/Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0"
2025-11-13 13:28:06.4189 IST [Polaris Controller] INFO: Running command:/Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/coverity --version
2025-11-13 13:28:06.4423 IST [Polaris Controller] INFO: Got tool version for "cov_thin_client": 2025.9.0
2025-11-13 13:28:06.7234 IST [Polaris Controller] INFO: "coverity" tool is already installed...
2025-11-13 13:28:06.7234 IST [Polaris Controller] INFO: fetching recommended "Sigma" tool info...
2025-11-13 13:28:07.0058 IST [Polaris Controller] INFO: checking "Sigma" tool installation inside bridge home directory: /Users/madhusud/.blackduck/bridge/tools/sigma/2025.10.0
2025-11-13 13:28:07.0058 IST [Polaris Controller] INFO: Checking tool version for "sigma" in "/Users/madhusud/.blackduck/bridge/tools/sigma/2025.10.0"
2025-11-13 13:28:07.0059 IST [Polaris Controller] INFO: Running command:/Users/madhusud/.blackduck/bridge/tools/sigma/2025.10.0/sigma --version
2025-11-13 13:28:07.0370 IST [Polaris Controller] INFO: Got tool version for "sigma": 2025.10.0
2025-11-13 13:28:07.3198 IST [Polaris Controller] INFO: "Sigma" tool is already installed...
2025-11-13 13:28:07.3456 IST [Polaris Controller] INFO: Provided value for resource 'coverity.id'
2025-11-13 13:28:07.3460 IST [Polaris Controller] INFO: Provided value for resource 'sigma.id'
2025-11-13 13:28:07.3462 IST [Polaris Controller] INFO: Provided value for resource 'detect.id'
2025-11-13 13:28:07.3462 IST [Bridge CLI] INFO: Starting adapters for stage polaris-sca-package
2025-11-13 13:28:07.3463 IST [Bridge CLI] INFO: Starting adapters for stage polaris-sast
2025-11-13 13:28:07.3463 IST [Bridge CLI] INFO: Starting adapters for stage polaris-artifacts-uploader
2025-11-13 13:28:07.3463 IST [Bridge CLI] INFO: Starting adapters for stage polaris-post-processing
2025-11-13 13:28:07.3463 IST [Bridge CLI] INFO: Starting adapters for stage polaris-reports-sarif
2025-11-13 13:28:07.3472 IST [Bridge CLI] INFO: Starting Adapter: Polaris SCA Package Manager Scan
2025-11-13 13:28:07.3473 IST [Bridge CLI] INFO: Starting Adapter: Polaris Coverity Capture
2025-11-13 13:28:07.3473 IST [Bridge CLI] INFO: Starting Adapter: Polaris Artifacts Uploader
2025-11-13 13:28:07.3475 IST [Polaris Controller] INFO: Adapter finished
2025-11-13 13:28:07.3473 IST [Bridge CLI] INFO: Starting Adapter: Polaris Waiter
2025-11-13 13:28:07.3473 IST [Bridge CLI] INFO: Starting Adapter: Polaris Policy Checker
2025-11-13 13:28:07.3473 IST [Bridge CLI] INFO: Starting Adapter: Polaris Issues Fetcher
2025-11-13 13:28:07.3473 IST [Bridge CLI] INFO: Starting Adapter: Polaris SARIF Issues Fetcher
2025-11-13 13:28:07.3854 IST [Bridge CLI] INFO: Starting Adapter: Default Adapter for execution path
2025-11-13 13:28:07.3866 IST [Default Adapter for execution path] INFO: Provided value for resource 'coverity.execution.path'
2025-11-13 13:28:07.3867 IST [Default Adapter for execution path] INFO: Adapter finished
2025-11-13 13:28:07.4000 IST [Bridge CLI] INFO: Starting Adapter: Default Adapter for execution path
2025-11-13 13:28:07.4005 IST [Default Adapter for execution path] INFO: Provided value for resource 'sigma.execution.path'
2025-11-13 13:28:07.4006 IST [Default Adapter for execution path] INFO: Adapter finished
2025-11-13 13:28:07.4378 IST [Polaris Coverity Capture] INFO: Identified workflow: Polaris
2025-11-13 13:28:07.4385 IST [Polaris Coverity Capture] INFO: command: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/coverity capture --dir /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir -o analyze.location=connect
2025-11-13 13:28:07.4854 IST [Polaris Coverity Capture] INFO: coverity 2025.9.0 covcli-2025.9-push-12
2025-11-13 13:28:07.4855 IST [Polaris Coverity Capture] INFO: envvar: COVERITY_CACHE_API_TOKEN_FILE=/var/folders/wm/gkd75sk54h57yqd0_j95gp2r0000gn/T/polaris_coverity_cache4207949062/.authKey
2025-11-13 13:28:07.4855 IST [Polaris Coverity Capture] INFO: envvar: COVERITY_CACHE_KEY=e88298dc-1601-489c-80ac-dac8a0a179f3
2025-11-13 13:28:07.4856 IST [Polaris Coverity Capture] INFO: envvar: COVERITY_CACHE_URL=https://poc.polaris.blackduck.com/api/cache
2025-11-13 13:28:07.4856 IST [Polaris Coverity Capture] INFO: envvar: COVERITY_CLI_CAPTURE_ZIP_ARCHIVE=/Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/idir.zip
2025-11-13 13:28:07.4856 IST [Polaris Coverity Capture] INFO: envvar: COVERITY_CLI_POLARIS_CLIENT=true
2025-11-13 13:28:07.4858 IST [Polaris Coverity Capture] INFO: Detected that stdout is not connected to a terminal.  Defaulting ticker mode to 'none'.
2025-11-13 13:28:07.4858 IST [Polaris Coverity Capture] INFO: If this is not correct, explicitly set the ticker mode to the desired value using the '--ticker-mode' option.
2025-11-13 13:28:07.4868 IST [Polaris Coverity Capture] INFO: Executing command: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-manage-emit --dir /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir create
2025-11-13 13:28:07.5052 IST [Polaris Coverity Capture] INFO: Using lightweight capture with thin client.
2025-11-13 13:28:07.5054 IST [Polaris Coverity Capture] INFO: Executing command: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-internal-manage-cache check
2025-11-13 13:28:08.2563 IST [Polaris Coverity Capture] INFO: Caching is enabled.
2025-11-13 13:28:08.2570 IST [Polaris Coverity Capture] INFO: Telemetry is enabled
2025-11-13 13:28:08.7454 IST [Polaris Coverity Capture] INFO: Executing command: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-manage-emit --dir /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir list-capture-diagnostics
2025-11-13 13:28:08.7611 IST [Polaris Coverity Capture] INFO: Executing action no-op: nothing to do for initialization
2025-11-13 13:28:09.2367 IST [Polaris Coverity Capture] INFO: Executing action Delete compiler configurations for intermediate directory '/Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir'
2025-11-13 13:28:09.2369 IST [Polaris Coverity Capture] INFO: Executing action Configure build compiler: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-configure -c /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir/coverity-cli/build-compiler-configs/coverity_config.xml --compiler gcc --comptype clangcc --template
2025-11-13 13:28:09.4654 IST [Polaris Coverity Capture] INFO: Executing action Configure build compiler: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-configure -c /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir/coverity-cli/build-compiler-configs/coverity_config.xml --compiler cc --comptype gcc --template
2025-11-13 13:28:09.6974 IST [Polaris Coverity Capture] INFO: Executing action Configure build compiler: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-configure -c /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir/coverity-cli/build-compiler-configs/coverity_config.xml --compiler c++ --comptype g++ --template
2025-11-13 13:28:09.9334 IST [Polaris Coverity Capture] INFO: Executing action Configure build compiler: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-configure -c /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir/coverity-cli/build-compiler-configs/coverity_config.xml --compiler clang --comptype clangcc --template
2025-11-13 13:28:10.1823 IST [Polaris Coverity Capture] INFO: Executing action Configure build compiler: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-configure -c /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir/coverity-cli/build-compiler-configs/coverity_config.xml --compiler java --comptype java --template
2025-11-13 13:28:10.4434 IST [Polaris Coverity Capture] INFO: Executing action Configure build compiler: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-configure -c /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir/coverity-cli/build-compiler-configs/coverity_config.xml --compiler go --comptype go --template
2025-11-13 13:28:10.7095 IST [Polaris Coverity Capture] INFO: Executing action Configure build compiler: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-configure -c /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir/coverity-cli/build-compiler-configs/coverity_config.xml --compiler ccache --comptype prefix --template
2025-11-13 13:28:10.9470 IST [Polaris Coverity Capture] INFO: Executing action Configure build compiler: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-configure -c /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir/coverity-cli/build-compiler-configs/coverity_config.xml --compiler kotlinc --comptype kotlinc --template
2025-11-13 13:28:11.1854 IST [Polaris Coverity Capture] WARNING: Template config template-java-config-0 already exists for java and will be reused. 
2025-11-13 13:28:11.1855 IST [Polaris Coverity Capture] WARNING: Template config template-apt-config-0 already exists for apt and will be reused. 
2025-11-13 13:28:11.1855 IST [Polaris Coverity Capture] WARNING: Template config template-javaw-config-0 already exists for javaw and will be reused. 
2025-11-13 13:28:11.1899 IST [Polaris Coverity Capture] INFO: Executing action Configure build compiler: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-configure -c /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir/coverity-cli/buildless-compiler-configs/coverity_config.xml --dart
2025-11-13 13:28:11.4186 IST [Polaris Coverity Capture] INFO: Executing action Configure build compiler: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-configure -c /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir/coverity-cli/buildless-compiler-configs/coverity_config.xml --javascript
2025-11-13 13:28:11.6510 IST [Polaris Coverity Capture] INFO: Executing action Configure build compiler: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-configure -c /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir/coverity-cli/buildless-compiler-configs/coverity_config.xml --php
2025-11-13 13:28:11.8749 IST [Polaris Coverity Capture] INFO: Executing action Configure build compiler: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-configure -c /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir/coverity-cli/buildless-compiler-configs/coverity_config.xml --python
2025-11-13 13:28:12.1006 IST [Polaris Coverity Capture] INFO: Executing action Configure build compiler: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-configure -c /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir/coverity-cli/buildless-compiler-configs/coverity_config.xml --ruby
2025-11-13 13:28:12.3316 IST [Polaris Coverity Capture] INFO: Executing action Configure build compiler: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-configure -c /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir/coverity-cli/buildless-compiler-configs/coverity_config.xml --comptype capture-config-files --file-regex $capture-config-files$ --template
2025-11-13 13:28:12.3462 IST [Polaris Coverity Capture] WARNING: Configuration already exists for file regex $capture-config-files$
2025-11-13 13:28:12.3462 IST [Polaris Coverity Capture] INFO:           and it will not be updated.
2025-11-13 13:28:12.8206 IST [Polaris Coverity Capture] INFO: Executing action no-op: no compilers need to be unconfigured
2025-11-13 13:28:13.2339 IST [Polaris Coverity Capture] INFO: Executing action no-op: compiler configurations loaded
2025-11-13 13:28:13.8209 IST [Polaris Coverity Capture] INFO: Executing action Emit files using buildless capture: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-internal-capture-files --dir /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir -c /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir/coverity-cli/buildless-compiler-configs/coverity_config.xml --ticker-mode none --append-log --capture-list-file /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir/coverity-cli/capture-file-list-1300384891 --record-with-source
2025-11-13 13:28:13.8308 IST [Polaris Coverity Capture] INFO: Buildless capture started.
2025-11-13 13:28:13.8398 IST [Polaris Coverity Capture] INFO: Emitting 84 Files.
2025-11-13 13:28:14.2987 IST [Polaris Coverity Capture] INFO: Buildless capture completed.
2025-11-13 13:28:14.3005 IST [Polaris Coverity Capture] INFO: Executing action No unwanted TUs to delete
2025-11-13 13:28:14.3005 IST [Polaris Coverity Capture] INFO: Executing action Action cleanup: Unwanted TUs action cleanup
2025-11-13 13:28:14.3005 IST [Polaris Coverity Capture] INFO: Executing action deleteResidualTUs /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir
2025-11-13 13:28:14.3008 IST [Polaris Coverity Capture] INFO: Executing command: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-manage-emit --dir /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir list-capture-diagnostics
2025-11-13 13:28:14.3183 IST [Polaris Coverity Capture] INFO: Executing action Invalidate capture results
2025-11-13 13:28:14.3184 IST [Polaris Coverity Capture] INFO: Executing action Invoke cov-run-sigma: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-run-sigma --project-dir /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm --dir /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir --coverity-config /var/folders/wm/gkd75sk54h57yqd0_j95gp2r0000gn/T/cov-run-sigma-config-2977860132/coverity.yaml --sigma-binary-path /Users/madhusud/.blackduck/bridge/tools/sigma/2025.10.0/sigma --enable-telemetry
2025-11-13 13:28:14.3318 IST [Polaris Coverity Capture] INFO: cov-run-sigma version 2025.9.0 on Darwin 24.6.0 arm64
2025-11-13 13:28:14.3318 IST [Polaris Coverity Capture] INFO: Internal version numbers: 477d3c5ddd p-2025.9-push-57
2025-11-13 13:28:14.3318 IST [Polaris Coverity Capture] INFO: 
2025-11-13 13:28:15.8165 IST [Polaris Coverity Capture] INFO: Executing action Action cleanup: Coverity configuration for Sigma
2025-11-13 13:28:16.3109 IST [Polaris Coverity Capture] INFO: Executing command: /Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/cov-manage-emit --dir /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir list-capture-diagnostics
2025-11-13 13:28:16.3664 IST [Polaris Coverity Capture] INFO: Capture summary:
2025-11-13 13:28:16.3664 IST [Polaris Coverity Capture] INFO:     SUCCEEDED: 87
2025-11-13 13:28:16.3664 IST [Polaris Coverity Capture] INFO:     INCOMPLETE: 0
2025-11-13 13:28:16.3664 IST [Polaris Coverity Capture] INFO:     FAILED: 0
2025-11-13 13:28:16.3664 IST [Polaris Coverity Capture] INFO:     IGNORED: 3
2025-11-13 13:28:16.3664 IST [Polaris Coverity Capture] INFO:     FILES CAPTURED: 87
2025-11-13 13:28:16.3665 IST [Polaris Coverity Capture] INFO:     LINES OF CODE: 32921
2025-11-13 13:28:16.3682 IST [Polaris Coverity Capture] INFO: Capture phase took 8.112s.
2025-11-13 13:28:16.3682 IST [Polaris Coverity Capture] WARNING: !! SOURCES FOR UNSUPPORTED LANGUAGES WERE DETECTED !!
2025-11-13 13:28:16.3682 IST [Polaris Coverity Capture] WARNING: 
2025-11-13 13:28:16.3682 IST [Polaris Coverity Capture] WARNING: Source files for the following languages were detected, but these languages are not supported on Mac OS ARM:
2025-11-13 13:28:16.3683 IST [Polaris Coverity Capture] WARNING:   * C#
2025-11-13 13:28:16.3684 IST [Polaris Coverity Capture] WARNING: In order to analyze these files, please analyze the project on an operating system and architecture where they are supported.
2025-11-13 13:28:16.3911 IST [Polaris Coverity Capture] INFO: To analyze your project, type '/Users/madhusud/.blackduck/bridge/tools/cov-thin-client/2025.9.0/bin/coverity analyze --dir /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/2025.9.0/idir -o analyze.location=connect'.
2025-11-13 13:28:16.3931 IST [Polaris Coverity Capture] INFO: Coverity Capture completed successfully
2025-11-13 13:28:16.4000 IST [Polaris Coverity Capture] INFO: Provided value for resource 'coverity.completed'
2025-11-13 13:28:16.4003 IST [Polaris Coverity Capture] INFO: Provided value for resource 'coverity.idir.output'
2025-11-13 13:28:16.4004 IST [Polaris Coverity Capture] INFO: Provided value for resource 'polaris.test.sast.tests.sastFull.artifacts.path'
2025-11-13 13:28:16.4006 IST [Polaris Coverity Capture] INFO: Adapter finished
2025-11-13 13:28:16.4025 IST [Bridge CLI] INFO: Starting Adapter: Default Adapter for execution path
2025-11-13 13:28:16.4026 IST [Default Adapter for execution path] INFO: Provided value for resource 'detect.execution.path'
2025-11-13 13:28:16.4027 IST [Default Adapter for execution path] INFO: Adapter finished
2025-11-13 13:28:16.4273 IST [Polaris SCA Package Manager Scan] INFO: Running command /Library/Java/JavaVirtualMachines/jdk-21.jdk/Contents/Home/bin/java -jar /Users/madhusud/.blackduck/bridge/tools/blackduck-detect/10.4.0/detect-10.4.0.jar --detect.cleanup=false --detect.bdio.file.name=scan --detect.bdio.output.path=/Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_sca_package_manager_scan/detect/bdio/blackduck_artifact --detect.output.path=/Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_sca_package_manager_scan/detect --detect.tools=DETECTOR --detect.component.location.analysis.enabled=true --blackduck.offline.mode=true --blackduck.offline.mode.force.bdio=true
2025-11-13 13:28:16.0000 IST [Polaris SCA Package Manager Scan][main] WARNING: --- Detect-Self-Updater:  Self-Update feature is disabled because of the following reasons:
2025-11-13 13:28:16.0000 IST [Polaris SCA Package Manager Scan][main] WARNING: --- Detect-Self-Updater:  Detect in offline mode is incompatible with the Self-Update feature.
2025-11-13 13:28:16.0000 IST [Polaris SCA Package Manager Scan][main] WARNING: --- Detect-Self-Updater:  Black Duck URL is required for the Self-Update feature.
2025-11-13 13:28:17.1946 IST [Polaris SCA Package Manager Scan] INFO: ______     _            _
2025-11-13 13:28:17.1948 IST [Polaris SCA Package Manager Scan] INFO: |  _  \   | |          | |
2025-11-13 13:28:17.1948 IST [Polaris SCA Package Manager Scan] INFO: | | | |___| |_ ___  ___| |_
2025-11-13 13:28:17.1949 IST [Polaris SCA Package Manager Scan] INFO: | | | / _ \ __/ _ \/ __| __|
2025-11-13 13:28:17.1949 IST [Polaris SCA Package Manager Scan] INFO: | |/ /  __/ ||  __/ (__| |_
2025-11-13 13:28:17.1949 IST [Polaris SCA Package Manager Scan] INFO: |___/ \___|\__\___|\___|\__|
2025-11-13 13:28:17.1949 IST [Polaris SCA Package Manager Scan] INFO: 
2025-11-13 13:28:17.3189 IST [Polaris SCA Package Manager Scan] INFO: 
2025-11-13 13:28:17.3189 IST [Polaris SCA Package Manager Scan] INFO: Detect Version: 10.4.0
2025-11-13 13:28:17.3189 IST [Polaris SCA Package Manager Scan] INFO: 
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- 
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Current property values:
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- --property = value [notes]
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- ------------------------------------------------------------
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- blackduck.offline.mode = true [cmd] 
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- blackduck.offline.mode.force.bdio = true [cmd] 
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- detect.bdio.file.name = scan [cmd] 
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- detect.bdio.output.path = /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_sca_package_manager_scan/detect/bdio/blackduck_artifact [cmd] 
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- detect.cleanup = false [cmd] 
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- detect.component.location.analysis.enabled = true [cmd] 
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- detect.excluded.directories = /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge [env] 
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- detect.output.path = /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_sca_package_manager_scan/detect [cmd] 
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- detect.tools = DETECTOR [cmd] 
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- ------------------------------------------------------------
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- 
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Detect build date: 2025-04-24
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Source directory: /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Output directory: /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_sca_package_manager_scan/detect
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Run directory: /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_sca_package_manager_scan/detect/runs/2025-11-13-07-58-17-280
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- 
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] WARNING: --- Correlated Scanning is not available for Rapid/Stateless scan mode or offline scanning. A correlation ID will not be set.
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- ----------------------------------
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Docker tool will not be run.
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- ----------------------------------
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Bazel tool will not be run.
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- ----------------------------------
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Will include the Detectors tool.
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Searching for detectors.
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Evaluating detectors. This may take a while.
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- ======================================================================================================
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Detector Report
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- ======================================================================================================
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- 	/Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm (depth 0)
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- 		NPM Package Lock: SUCCESS
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- 			Found file: /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/package-lock.json
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- 			Found file: /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/package.json
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- ----------------------------------
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Detectors actions finished.
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- ----------------------------------
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Project name: owasp-nodejs-goat
2025-11-13 13:28:17.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Project version: 1.3.0
2025-11-13 13:28:19.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- ----------------------------------
2025-11-13 13:28:19.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Signature Scanner tool will not be run.
2025-11-13 13:28:19.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- ----------------------------------
2025-11-13 13:28:19.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Vulnerability Impact Analysis tool will not be run.
2025-11-13 13:28:19.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- ----------------------------------
2025-11-13 13:28:19.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- IaC Scanner tool will not be run.
2025-11-13 13:28:19.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- ----------------------------------
2025-11-13 13:28:19.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- ##################################################################################################
2025-11-13 13:28:19.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- #                                                                                                #
2025-11-13 13:28:19.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- #  Product Notice                                                                                #
2025-11-13 13:28:19.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- #  © 2024 Black Duck Software, Inc.                                                              #
2025-11-13 13:28:19.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- #  This Black Duck Component Locator and all associated documentation are proprietary            #
2025-11-13 13:28:19.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- #  to Black Duck Software, Inc. and may only be used pursuant to the terms and conditions of a   #
2025-11-13 13:28:19.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- #  written license agreement with Black Duck Software, Inc. All other use, reproduction,         #
2025-11-13 13:28:19.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- #  modification, or distribution of the Black Duck Component Locator or the associated           #
2025-11-13 13:28:19.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- #  documentation is strictly prohibited.                                                         #
2025-11-13 13:28:19.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- #                                                                                                #
2025-11-13 13:28:19.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- ##################################################################################################
2025-11-13 13:28:19.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Running Component Locator v1.1.12 on /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Component Location Analysis file saved at: /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_sca_package_manager_scan/detect/runs/2025-11-13-07-58-17-280/scan/components-with-locations.json
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- ----------------------------------
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- 
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- 
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Creating status file: /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_sca_package_manager_scan/detect/runs/2025-11-13-07-58-17-280/status/status.json
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- 
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Skipping cleanup, it is disabled.
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- 
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- 
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- ======== Detect Result ========
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- 
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Component Location Analysis File: /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_sca_package_manager_scan/detect/runs/2025-11-13-07-58-17-280/scan/components-with-locations.json
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- 
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- ======== Detect Status ========
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- 
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- NPM: SUCCESS
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Overall Status: SUCCESS - Detect exited successfully.
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- 
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- ===============================
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- 
2025-11-13 13:29:02.0000 IST [Polaris SCA Package Manager Scan][main] INFO: --- Detect duration: 00h 00m 45s 399ms
2025-11-13 13:29:02.1678 IST [Polaris SCA Package Manager Scan] INFO: Provided value for resource 'detect.completed'
2025-11-13 13:29:02.1680 IST [Polaris SCA Package Manager Scan] INFO: Provided value for resource 'polaris.test.sca.tests.scaPackage.artifacts.path'
2025-11-13 13:29:02.1724 IST [Polaris SCA Package Manager Scan] INFO: Adapter finished
2025-11-13 13:29:02.2143 IST [Polaris Artifacts Uploader] INFO: uploading artifact for "SAST(sastFull)" assessment with id "91846c26-3bdd-4da9-8aa5-d49c445ff2c9"
2025-11-13 13:29:02.2148 IST [Polaris Artifacts Uploader] INFO: uploading artifact for "SCA(scaPackage)" assessment with id "0dbcf5bd-181e-4f60-96eb-72394a3b3e7b"
2025-11-13 13:29:03.4760 IST [Polaris Artifacts Uploader] INFO: Uploading artifact /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/idir.zip for "SAST(sastFull)" assessment
2025-11-13 13:29:03.6236 IST [Polaris Artifacts Uploader] INFO: Uploading artifact /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_sca_package_manager_scan/blackduck-sca-artifacts.zip for "SCA(scaPackage)" assessment
2025-11-13 13:29:03.9120 IST [Polaris Artifacts Uploader] INFO: Uploading Progress of "SAST(sastFull)" artifact:   4%  16384/386516
2025-11-13 13:29:04.0575 IST [Polaris Artifacts Uploader] INFO: Uploading Progress of "SCA(scaPackage)" artifact:   7%  16384/208043
2025-11-13 13:29:04.1202 IST [Polaris Artifacts Uploader] INFO: Uploading Progress of "SAST(sastFull)" artifact:  29%  114688/386516
2025-11-13 13:29:04.2680 IST [Polaris Artifacts Uploader] INFO: Uploading Progress of "SCA(scaPackage)" artifact:  39%  81920/208043
2025-11-13 13:29:04.2712 IST [Polaris Artifacts Uploader] INFO: Uploading Progress of "SCA(scaPackage)" artifact:  70%  147456/208043
2025-11-13 13:29:04.5603 IST [Polaris Artifacts Uploader] INFO: Uploading Progress of "SAST(sastFull)" artifact:  55%  212992/386516
2025-11-13 13:29:04.5606 IST [Polaris Artifacts Uploader] INFO: Uploading Progress of "SAST(sastFull)" artifact:  80%  311296/386516
2025-11-13 13:29:04.7116 IST [Polaris Artifacts Uploader] INFO: Uploading Progress of "SCA(scaPackage)" artifact: 100%  208043/208043
2025-11-13 13:29:04.7717 IST [Polaris Artifacts Uploader] INFO: Uploading Progress of "SAST(sastFull)" artifact: 100%  386516/386516
2025-11-13 13:29:05.2032 IST [Polaris Artifacts Uploader] INFO: successfully uploaded artifact "/Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_sca_package_manager_scan/blackduck-sca-artifacts.zip"
2025-11-13 13:29:05.2450 IST [Polaris Artifacts Uploader] INFO: successfully uploaded artifact "/Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.bridge/polaris_coverity_capture/idir.zip"
2025-11-13 13:29:05.6584 IST [Polaris Artifacts Uploader] INFO: successfully resumed "SCA(scaPackage)" assessment with id "0dbcf5bd-181e-4f60-96eb-72394a3b3e7b"
2025-11-13 13:29:05.7151 IST [Polaris Artifacts Uploader] INFO: successfully resumed "SAST(sastFull)" assessment with id "91846c26-3bdd-4da9-8aa5-d49c445ff2c9"
2025-11-13 13:29:05.7437 IST [Polaris Artifacts Uploader] INFO: Provided value for resource 'polaris.test.sca.tests.scaPackage.artifacts.uploadSuccessful'
2025-11-13 13:29:05.7439 IST [Polaris Artifacts Uploader] INFO: Provided value for resource 'polaris.test.sast.tests.sastFull.artifacts.uploadSuccessful'
2025-11-13 13:29:05.7442 IST [Polaris Artifacts Uploader] INFO: Adapter finished
2025-11-13 13:29:05.7728 IST [Polaris Waiter] INFO: Waiting for test with assessment type "SCA(scaPackage)" and id "0dbcf5bd-181e-4f60-96eb-72394a3b3e7b"
2025-11-13 13:29:05.7730 IST [Polaris Waiter] INFO: Waiting for test with assessment type "SAST(sastFull)" and id "91846c26-3bdd-4da9-8aa5-d49c445ff2c9"
2025-11-13 13:29:06.5067 IST [Polaris Waiter] INFO: Polling Test Manager: state of test with assessment type "SAST(sastFull)" and id "91846c26-3bdd-4da9-8aa5-d49c445ff2c9" is "Queuing"
2025-11-13 13:29:06.5316 IST [Polaris Waiter] INFO: Polling Test Manager: state of test with assessment type "SCA(scaPackage)" and id "0dbcf5bd-181e-4f60-96eb-72394a3b3e7b" is "Queuing"
2025-11-13 13:29:58.0346 IST [Polaris Waiter] INFO: Polling Test Manager: state of test with assessment type "SCA(scaPackage)" and id "0dbcf5bd-181e-4f60-96eb-72394a3b3e7b" is "Scanning & Publishing"
2025-11-13 13:29:58.0375 IST [Polaris Waiter] INFO: Polling Test Manager: state of test with assessment type "SAST(sastFull)" and id "91846c26-3bdd-4da9-8aa5-d49c445ff2c9" is "Scanning"
2025-11-13 13:30:28.9337 IST [Polaris Waiter] INFO: test with assessment type "SCA(scaPackage)" and id "0dbcf5bd-181e-4f60-96eb-72394a3b3e7b" completed successfully
2025-11-13 13:32:12.0637 IST [Polaris Waiter] INFO: test with assessment type "SAST(sastFull)" and id "91846c26-3bdd-4da9-8aa5-d49c445ff2c9" completed successfully
2025-11-13 13:32:12.0923 IST [Polaris Waiter] INFO: Provided value for resource 'polaris.test.sast.tests.sastFull.completed'
2025-11-13 13:32:12.0928 IST [Polaris Waiter] INFO: Provided value for resource 'polaris.test.sca.tests.scaPackage.completed'
2025-11-13 13:32:12.0942 IST [Polaris Waiter] INFO: Adapter finished
2025-11-13 13:32:12.1783 IST [Polaris Policy Checker] INFO: Checking for policy violations for "SAST(sastFull)" assessment...
2025-11-13 13:32:12.1789 IST [Polaris Policy Checker] INFO: Checking for policy violations for "SCA(scaPackage)" assessment...
2025-11-13 13:32:13.0481 IST [Polaris Policy Checker] INFO: no policies were violated to break the build
2025-11-13 13:32:13.0782 IST [Polaris Policy Checker] INFO: Adapter finished
2025-11-13 13:32:13.1289 IST [Polaris Issues Fetcher] INFO: Fetching issues for "SCA(scaPackage)" assessment
2025-11-13 13:32:13.1298 IST [Polaris Issues Fetcher] INFO: Fetching issues for "SAST(sastFull)" assessment
2025-11-13 13:32:13.8870 IST [Polaris Issues Fetcher] INFO: Successfully fetched issues for assessment type "SAST(sastFull)" with id "91846c26-3bdd-4da9-8aa5-d49c445ff2c9"
 {
 "critical": 0,
 "high": 2,
 "informational": 0,
 "low": 25,
 "medium": 13
}
2025-11-13 13:32:13.9768 IST [Polaris Issues Fetcher] INFO: Successfully fetched issues for assessment type "SCA(scaPackage)" with id "0dbcf5bd-181e-4f60-96eb-72394a3b3e7b"
 {
 "critical": 6,
 "high": 109,
 "informational": 0,
 "low": 15,
 "medium": 133
}
2025-11-13 13:32:14.0028 IST [Polaris Issues Fetcher] INFO: Provided value for resource 'polaris.test.sca.tests.scaPackage.issues.critical'
2025-11-13 13:32:14.0031 IST [Polaris Issues Fetcher] INFO: Provided value for resource 'polaris.test.sca.tests.scaPackage.issues.low'
2025-11-13 13:32:14.0033 IST [Polaris Issues Fetcher] INFO: Provided value for resource 'polaris.test.sca.tests.scaPackage.issues.high'
2025-11-13 13:32:14.0035 IST [Polaris Issues Fetcher] INFO: Provided value for resource 'polaris.test.sca.tests.scaPackage.issues.informational'
2025-11-13 13:32:14.0038 IST [Polaris Issues Fetcher] INFO: Provided value for resource 'polaris.test.sca.tests.scaPackage.issues.medium'
2025-11-13 13:32:14.0040 IST [Polaris Issues Fetcher] INFO: Provided value for resource 'polaris.test.sast.tests.sastFull.issues.informational'
2025-11-13 13:32:14.0043 IST [Polaris Issues Fetcher] INFO: Provided value for resource 'polaris.test.sast.tests.sastFull.issues.critical'
2025-11-13 13:32:14.0045 IST [Polaris Issues Fetcher] INFO: Provided value for resource 'polaris.test.sast.tests.sastFull.issues.high'
2025-11-13 13:32:14.0048 IST [Polaris Issues Fetcher] INFO: Provided value for resource 'polaris.test.sast.tests.sastFull.issues.low'
2025-11-13 13:32:14.0050 IST [Polaris Issues Fetcher] INFO: Provided value for resource 'polaris.test.sast.tests.sastFull.issues.medium'
2025-11-13 13:32:14.0059 IST [Polaris Issues Fetcher] INFO: Adapter finished
2025-11-13 13:32:14.0510 IST [Polaris SARIF Issues Fetcher] INFO: Fetching issues from Polaris Server...
2025-11-13 13:34:34.7157 IST [Polaris SARIF Issues Fetcher] INFO: Added entry to resource 'polaris.reports.sarif.issues'
2025-11-13 13:34:34.7296 IST [Bridge CLI] INFO: Starting adapters for stage polaris-sarif-generator
2025-11-13 13:34:34.7298 IST [Bridge CLI] INFO: Starting Adapter: Polaris SARIF Generator
2025-11-13 13:34:34.7301 IST [Polaris SARIF Issues Fetcher] INFO: Adapter finished
2025-11-13 13:34:34.7729 IST [Polaris Status Provider] INFO: Results for test "SAST(sastFull)" with ID "91846c26-3bdd-4da9-8aa5-d49c445ff2c9" are available at https://poc.polaris.blackduck.com/portfolio/portfolios/edf596d3-b54f-4a6b-9e5c-209f2e526c67/portfolio-items/dd84e8a7-7370-4c30-9322-e898a16caaa5/projects/19ad2fe3-655d-42b6-9bf4-24808ebf7c69/tests/91846c26-3bdd-4da9-8aa5-d49c445ff2c9/detected-issues
2025-11-13 13:34:34.7732 IST [Polaris Status Provider] INFO: Results for test "SCA(scaPackage)" with ID "0dbcf5bd-181e-4f60-96eb-72394a3b3e7b" are available at https://poc.polaris.blackduck.com/portfolio/portfolios/edf596d3-b54f-4a6b-9e5c-209f2e526c67/portfolio-items/dd84e8a7-7370-4c30-9322-e898a16caaa5/projects/19ad2fe3-655d-42b6-9bf4-24808ebf7c69/tests/0dbcf5bd-181e-4f60-96eb-72394a3b3e7b/detected-issues
2025-11-13 13:34:34.7732 IST [Polaris Status Provider] INFO: Polaris issues view for project "simplified-example", branch "main" is available at https://poc.polaris.blackduck.com/portfolio/portfolios/edf596d3-b54f-4a6b-9e5c-209f2e526c67/portfolio-items/dd84e8a7-7370-4c30-9322-e898a16caaa5/projects/19ad2fe3-655d-42b6-9bf4-24808ebf7c69/issues?branchId=4a5812b7-ac2c-4312-b424-a525ca8777f7
2025-11-13 13:34:34.7798 IST [Polaris Status Provider] INFO: Provided value for resource 'polaris.test.SAST.tests.sastFull.summary.url'
2025-11-13 13:34:34.7800 IST [Polaris Status Provider] INFO: Provided value for resource 'polaris.test.SCA.tests.scaPackage.summary.url'
2025-11-13 13:34:34.7801 IST [Polaris Status Provider] INFO: Provided value for resource 'polaris.project.issues.url'
2025-11-13 13:34:34.7803 IST [Polaris Status Provider] INFO: Adapter finished
2025-11-13 13:34:34.8403 IST [Polaris SARIF Generator] INFO: Will create rules with SCA component-version pairs grouped by their related vulnerabilities in the SARIF report. Since "polaris.reports.sarif.groupSCAIssues" is configured to "true"
2025-11-13 13:34:34.8493 IST [Polaris SARIF Generator] INFO: SARIF report created successfully at .blackduck/integrations/polaris/sarif/report.sarif.json
2025-11-13 13:34:34.8805 IST [Polaris SARIF Generator] INFO: Provided value for resource 'polaris.reports.sarif.file.output'
2025-11-13 13:34:34.8808 IST [Polaris SARIF Generator] INFO: Adapter finished
******************************* END EXECUTION OF BRIDGE CLI *******************************
[Security Scan] INFO: This is not a (PR/MR) event
[Security Scan] INFO: Archiving SARIF jenkins artifact from: /Users/madhusud/Jenkins_Testing/Nodes/workspace/Polaris_Simplified_Workflow_main@2/nodejs-npm/.blackduck/integrations/polaris/sarif/report.sarif.json
Archiving artifacts
[Security Scan] INFO: SARIF archived successfully in jenkins artifact
[Security Scan] INFO: Retrieving the issue count from the scan results
[Security Scan] INFO: Total issues found: 303
[Security Scan] INFO: Security Scan execution is successful
**************************** END EXECUTION OF BLACK DUCK SECURITY SCAN ****************************
[Pipeline] }
[Pipeline] // dir
[Pipeline] }
[Pipeline] // script
[Pipeline] }
[Pipeline] // stage
[Pipeline] stage
[Pipeline] { (Declarative: Post Actions)
[Pipeline] echo
Black Duck Logs Publisher - Starting log upload process
[Pipeline] echo
Configuration: [githubOrg:polaris-jenkins-samples, repoName:simplified-example, credentialsId:github-pat-logs-publisher, maxRetries:3, retentionCount:5, jobNamePrefixes:[MBP_Github_, MBP_, Github_, Pipeline_, Job_, Build_]]
[Pipeline] echo
Job Name: MBP_Github_Polaris_Simplified_Workflow/main
[Pipeline] echo
Build Number: 2
[Pipeline] echo
GitHub Organization: polaris-jenkins-samples
[Pipeline] withCredentials
Masking supported pattern matches of $GITHUB_TOKEN
[Pipeline] {
[Pipeline] echo
Using configured repository name: simplified-example
[Pipeline] echo
Target repository: polaris-jenkins-samples/simplified-example
[Pipeline] echo
LogProcessor: captureJenkinsLogs called
```

---

*Log generated by Black Duck Logs Publisher*