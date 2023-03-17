# Change Log for Amazon Corretto 19

The following sections describe the changes for each release of Amazon Corretto 19.

## Corretto version: 19.0.2.7.1
Release Date: January 17, 2023

**Target Platforms <sup>1</sup>**

+ RPM-based Linux using glibc 2.12 or later, x86_64
+ Debian-based Linux using glibc 2.12 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64
+ Alpine-based Linux, x86_64
+ Windows 10 or later, x86_64
+ macos 10.15 and later, x86_64
+ macos 11.0 and later, aarch64

**1.** This is the platform targeted by the build. See [Using Amazon Corretto](https://aws.amazon.com/corretto/faqs/#Using_Amazon_Corretto)
in the Amazon Corretto FAQ for supported platforms

The following issues are addressed in 19.0.2.7.1:

| Issue Name                                                    | Platform | Description                                                                                        | Link                                                                      |
|---------------------------------------------------------------|----------|----------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| Import jdk-19.0.2+7                                           | All      | Updates Corretto baseline to OpenJDK 19.0.2+7                                                      | [jdk-19.0.2+7](https://github.com/openjdk/jdk19u/releases/tag/19.0.2+7)   |
| Include commitId.txt in archives                              | All      | Include commitId.txt in archives                                                                   | [#7](https://github.com/corretto/corretto-19/pull/7)                      |
| Update amazon cacerts                                         | All      | Update amazon cacerts file from amazonlinux                                                        |                                                                           |
| Backport 8295447: NPE with invalid pattern matching construct | All      | Backport 8295447: NullPointerException with invalid pattern matching construct in constructor call | [c9d485792b9](https://github.com/corretto/corretto-19/commit/c9d485792b9) |                                                             |
| Backport 8296904: Improve handling of macos xcode toolchain   | macOS    | Backport 8296904: Improve handling of macos xcode toolchain                                        | [7275da49c0e](https://github.com/corretto/corretto-19/commit/7275da49c0e) |                                                            |

The following CVEs are addressed in 19.0.2.7.1:

| CVE            | CVSS | Component                   |
|----------------|------|-----------------------------|
| CVE-2023-21835 | 5.3  | security-libs/javax.net.ssl |
| CVE-2023-21843 | 3.7  | client-libs/javax.sound     |


## Corretto version: 19.0.1.10.1
Release Date: October 18, 2022

**Target Platforms <sup>1</sup>**

+ RPM-based Linux using glibc 2.12 or later, x86_64
+ Debian-based Linux using glibc 2.12 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64
+ Alpine-based Linux, x86_64
+ Windows 7 or later, x86_64
+ macos 10.15 and later, x86_64
+ macos 11.0 and later, aarch64

**1.** This is the platform targeted by the build. See [Using Amazon Corretto](https://aws.amazon.com/corretto/faqs/#Using_Amazon_Corretto)
in the Amazon Corretto FAQ for supported platforms

The following issues are addressed in 19.0.1.10.1:

| Issue Name                                 | Platform | Description                                                                          | Link                                                                            |
|--------------------------------------------|----------|--------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| Import jdk-19.0.1+10                       | All      | Updates Corretto baseline to OpenJDK 19.0.1+10                                       | [jdk-19.0.1+10](https://github.com/openjdk/jdk19u/releases/tag/jdk-19.0.1%2B10) |
| Update Timezone Data to 2022e              | All      | All tzdata updates up to 2022e                                                       | [#5](https://github.com/corretto/corretto-19/pull/5) [#6](https://github.com/corretto/corretto-19/pull/6) |
| Update amazon cacerts                      | All      | Update amazon cacerts file from amazonlinux                                          | |

The following CVEs are addressed in 19.0.1.10.1:

| CVE            | CVSS | Component                   |
|----------------|------|-----------------------------|
| CVE-2022-21618 | 5.3  | security-libs/org.ietf.jgss |
| CVE-2022-21628 | 5.3  | core-libs/java.net          |
| CVE-2022-39399 | 3.7  | core-libs/java.net          |
| CVE-2022-21619 | 3.7  | security-libs/java.security |
| CVE-2022-21624 | 3.7  | core-libs/javax.naming      |


## Corretto version: 19.0.0.36.1
Release Date: August 17, 2022

**Target Platforms**

+ RPM-based Linux using glibc 2.12 or later, x86_64
+ Debian-based Linux using glibc 2.12 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64
+ Alpine-based Linux, x86_64
+ Windows 7 or later, x86_64
+ macos 10.15 and later, x86_64
+ macos 11.0 and later, aarch64


The following issues are addressed in 19.0.0.36.1

| Issue Name                                 | Platform | Description                                                                          | Link                                                                            |
|--------------------------------------------|----------|--------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| Import jdk-19+36                           | All      | Updates Corretto baseline to OpenJDK 19+36                                           | [jdk-19+36](https://github.com/openjdk/jdk19/releases/tag/jdk-19%2B36)          |

