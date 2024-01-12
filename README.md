# 漏洞报告

## 漏洞描述
漏洞概述：（简要描述漏洞的性质和影响）

## 影响版本
受影响的软件版本：DIR-825ACG1、DIR-841、DIR-1260、DIR-822、DIR-X1530、DIR-825、DIR-615、DIR-842、DIR-853、DIR-1210、DIR-806A、DIR-815、DSL-245GR、DSL-G2452GR、DIR-878、DIR-825ACF、DIR-615T、DIR-300、DIR-842S、DIR-815S、DSL-2640U、DIR-2150、DWR-921、DIR-615S、DIR-620、DVG-5402G、DIR-882、DWM-312W、DIR-815/AC、DSL-224、DWM-321、DIR-X1860、DAP-1360、DIR-820、DIR-843、DVG-5402G/GFRU、DWR-953、DVG-N5402G/IL、DIR-825AC、DIR-620S、DVG-N5402G、Good Line Router v2、DSL-2750U、DIR-615GF、DIR-816

## 漏洞详情
漏洞详细信息：The "area" parameter of the "devinfo" interface is controllable, allowing for the retrieval of device information. The specific path for the GET request is http://127.0.0.1/devinfo?area=notice|net|version.

## 复现步骤
漏洞复现步骤：（提供漏洞复现的步骤，以便验证漏洞）

## 预期结果
预期的结果：（描述您期望看到的结果）

## 实际结果
实际的结果：（描述您实际观察到的结果）

## 修复建议
修复建议：（提供修复漏洞的建议或解决方案）

## 其他信息
其他信息：（提供任何其他有关漏洞的信息，例如漏洞披露策略等）

---

# Vulnerability Report

## Vulnerability Description
Summary: D-Link is vulnerable to an unauthorized access exploit, allowing attackers to retrieve sensitive information such as device MAC address, IP address, routing details, device region, version number, etc., by specifying a command.

## Affected Versions
Affected software versions: DIR-825ACG1、DIR-841、DIR-1260、DIR-822、DIR-X1530、DIR-825、DIR-615、DIR-842、DIR-853、DIR-1210、DIR-806A、DIR-815、DSL-245GR、DSL-G2452GR、DIR-878、DIR-825ACF、DIR-615T、DIR-300、DIR-842S、DIR-815S、DSL-2640U、DIR-2150、DWR-921、DIR-615S、DIR-620、DVG-5402G、DIR-882、DWM-312W、DIR-815/AC、DSL-224、DWM-321、DIR-X1860、DAP-1360、DIR-820、DIR-843、DVG-5402G/GFRU、DWR-953、DVG-N5402G/IL、DIR-825AC、DIR-620S、DVG-N5402G、Good Line Router v2、DSL-2750U、DIR-615GF、DIR-816

## Vulnerability Details
Detailed information: The "area" parameter of the "devinfo" interface is controllable, allowing for the retrieval of device information. The specific path for the GET request is http://127.0.0.1/devinfo?area=notice|net|version

## Reproduction Steps
Reproduction steps: (Provide steps to reproduce the vulnerability for validation)

## Expected Result
Expected result: (Describe what you expected to see)

## Actual Result
Actual result: (Describe what you actually observed)

## Fix Recommendation
Fix recommendation: (Provide recommendations or solutions to fix the vulnerability)

## Additional Information
Additional information: (Provide any other information about the vulnerability, such as disclosure policy, etc.)
