# dxtoolkit

## What is it

Dxtoolkit is a set of scripts, which are delivered by Delphix professional services team. 
Dxtoolkit scripts look and feel like UNIX executables, following the typical conventions of using flags for arguments.  Dxtoolkit is written in Perl, but no knowledge of Perl is required unless you want to extend it.  In fact, no programming experience whatsoever is required to use the dxtoolkit.

## What's new

Please check a [change log](https://github.com/delphix/dxtoolkit/blob/master/CHANGELOG.md) for list of changes.

## How to get started
### Compiled version

**Prerequisites**
* OpenSSL 1.0 library is required for Solaris Sparc, Solaris x64, Red Hat 6 and Red Hat 7 
* OpenSSL 0.98 library is required for Red Hat 5

If you don't have required version of OpenSSL library download a version with -openssl- in name, where
those libraries are embbeded.

Download a compiled version of DxToolkit for required platform from a [releases  page](https://github.com/delphix/dxtoolkit/releases). 
Create a configuration file *dxtools.conf* based on dxtools.conf.example or a Wiki page.

Check a [documentation](https://github.com/delphix/dxtoolkit/wiki) for more details

### Known issues

There is no script dx_syslog on Windows and AIX due to lack of support of Log::Syslog::Fast Perl module

### Source version

Perl version 5.16 or higher

**Required packages**
- JSON
- Date::Manip
- DateTime::Event::Cron::Quartz
- DateTime::Format::DateParse
- Crypt::CBC
- Crypt::Blowfish
- Text::CSV
- Try::Tiny
- LWP::UserAgent
- Net::SSLeay
- IO::Socket::SSL
- LWP::Protocol::https
- Term::ReadKey
- Log::Syslog::Fast

## Legalness
```
 Licensed under the Apache License, Version 2.0 (the "License");
 you may not use this file except in compliance with the License.
 You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.
```
Copyright (c) 2014, 2016 by Delphix. All rights reserved.
