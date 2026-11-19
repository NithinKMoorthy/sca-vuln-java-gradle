# sca-vuln-java-gradle

> **WARNING: Intentionally vulnerable.** Test fixture for Software Composition Analysis (SCA) tools.
> Do not deploy. Dependencies are pinned to versions with known CVEs.

**Ecosystem:** Gradle (Java)

## Expected findings (non-exhaustive)
- struts2-core 2.3.30: CVE-2017-5638 (Equifax RCE)
- guava 20.0: CVE-2018-10237, CVE-2020-8908
- bcprov 1.60: CVE-2020-28052
- netty-codec-http 4.1.42: CVE-2019-20444, CVE-2021-21290
- xstream 1.4.10: CVE-2021-39144 and many more
- tomcat-embed-core 9.0.30: CVE-2020-1938 (Ghostcat)
- gson 2.8.5: CVE-2022-25647
