+++
date = '2026-04-10T23:54:00+02:00'
draft = false
title = 'Test'
+++
## Executive Summary
* **Sample:** Lab01-01.exe
* **Type:** PE32 Executable
* **Verdict:** Malicious (Downloader/Backdoor)
* **Description:** العينة دي بتعمل كذا وكذا وبتحاول تفتح بورت في الجهاز.

---

## Static Analysis
### Hashes
* **MD5:** `[حط الـ Hash هنا]`
* **SHA256:** `[حط الـ Hash هنا]`

### Strings & Imports
* لقيت الـ APIs دي: `CreateProcessA`, `Sleep`, `WS2_32.dll`.
* فيه IP مريب لقيته: `127.0.0.1` (مثلاً).

---

## Dynamic Analysis
### Host-based Indicators
* المالوير عمل فايل في المسار ده: `C:\Windows\System32\kerne132.dll`.

### Network Indicators
* حاول يكلم الدومين ده: `www.malwareanalysisbook.com`.

---

## Technical Deep Dive
![صورة من IDA](path-to-your-image.png)
> **Note:** هنا بتشرح بقى إنت فهمت إيه من الـ Assembly وليه الـ Jump دي كانت صايعة.