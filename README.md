# W-7
# Project 7 - WordPress Pentesting

Time spent: 7 hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. (Required) DOS attack
  - [ ] Summary: 
    - Vulnerability types: Denial of service
    - Tested in version: 4.2
    - Fixed in version: ?
  - [ ] GIF Walkthrough: <img src='week7.1.gif' />
  - [ ] Steps to recreate: login as Admin and from website download a script and use that to attack the WP website 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)

1. (Required) Cross Site Scripting Attack
  - [ ] Summary: 
    - Vulnerability types: xss
    - Tested in version:4.2
    - Fixed in version:4.7.3 
  - [ ] GIF Walkthrough: <img src='week7.2.gif' />
  - [ ] Steps to recreate: Login as Admin and uploaded a 3 MB image with error XSS
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)

1. (Required) Cross Site Scripting Attack
  - [ ] Summary: 
    - Vulnerability types:xss
    - Tested in version:4.2
    - Fixed in version: 4.7.5
  - [ ] GIF Walkthrough: <img src='week7.3.gif' />
  - [ ] Steps to recreate: login as admin and add a comment body onload=alert(document.cookie)
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

    Copyright [2018] [Mir Sahraye]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
