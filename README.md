# Project 7 - WordPress Pentesting

Time spent: 10 hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. (Required) CVE-2015-5623
  - [&#10003;] Summary: 
    - Vulnerability types: stored XSS
    - Tested in version: 4.1
    - Fixed in version: 4.1.6
  - [&#10003;] GIF Walkthrough: http://i.imgur.com/aPulzqj.gif
  - [&#10003;] Steps to recreate: Login as an admin, publish a post with XSS. Then go to posts and it'll be there.
  - [&#10003;] Affected source code:
    - [Link 1](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2015-5622)
1. (Required) Username enumeration
  - [&#10003;] Summary: Username enumeration
    - Vulnerability types: Username enumeration
    - Tested in version: 4.1
    - Fixed in version: ???
  - [&#10003;] GIF Walkthrough: http://i.imgur.com/UTyBSOC.gif
  - [&#10003;] Steps to recreate: Enter a unexistent username and it'll prompt a different error than when you enter an exist username
  - [&#10003;] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Required) Authenticated Shortcode Tags Cross-Site Scripting CVE-2015-5714
  - [&#10003;] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.1
    - Fixed in version: 4.1.8
  - [&#10003;] GIF Walkthrough: http://i.imgur.com/LFAKjW3.gif
  - [&#10003;] Steps to recreate: Triple nested tags are not sanitized.
  - [&#10003;] Affected source code:
    - [Link 1](http://blog.checkpoint.com/2015/09/15/finding-vulnerabilities-in-core-wordpress-a-bug-hunters-trilogy-part-iii-ultimatum/)
1. (Optional) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Optional) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php) 

## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while doing the work

## License

    Copyright [2017] [Stephen Yang]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.