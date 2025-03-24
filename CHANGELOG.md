<div align="center">
  <a href="#">
    <img src="https://raw.githubusercontent.com/community-scripts/ProxmoxVED/main/misc/images/logo.png" height="100px" />
 </a>
</div>
<h1 align="center">Changelog - Develop</h1>

<h3 align="center">All notable changes to this project will be documented in this file.</h3>


## 2025-03-24

### 🆕 New Scripts

  - wazuh [@omiinaya](https://github.com/omiinaya) ([#3381](https://github.com/community-scripts/ProxmoxVE/pull/3381))
- yt-dlp-webui [@CrazyWolf13](https://github.com/CrazyWolf13) ([#3364](https://github.com/community-scripts/ProxmoxVE/pull/3364))
- Extension/New Script: Redis Alpine Installation [@MickLesk](https://github.com/MickLesk) ([#3367](https://github.com/community-scripts/ProxmoxVE/pull/3367))
- Fluid Calendar [@vhsdream](https://github.com/vhsdream) ([#2869](https://github.com/community-scripts/ProxmoxVE/pull/2869))
- CryptPad [@MickLesk](https://github.com/MickLesk) ([#3205](https://github.com/community-scripts/ProxmoxVE/pull/3205))

### 🚀 Updated Scripts

  - License url VED to VE [@bvdberg01](https://github.com/bvdberg01) ([#3258](https://github.com/community-scripts/ProxmoxVE/pull/3258))
- Omada jdk to jre [@bvdberg01](https://github.com/bvdberg01) ([#3319](https://github.com/community-scripts/ProxmoxVE/pull/3319))

  - #### 🐞 Bug Fixes

    - GoMFT: Check if build-essential is present before updating, if not then install it [@tremor021](https://github.com/tremor021) ([#3358](https://github.com/community-scripts/ProxmoxVE/pull/3358))
    - revealjs: Fix update process [@tremor021](https://github.com/tremor021) ([#3341](https://github.com/community-scripts/ProxmoxVE/pull/3341))
    - MySQL: Correctly add repo to mysql.list [@tremor021](https://github.com/tremor021) ([#3315](https://github.com/community-scripts/ProxmoxVE/pull/3315))
    - Cronicle: add missing gnupg package [@MickLesk](https://github.com/MickLesk) ([#3323](https://github.com/community-scripts/ProxmoxVE/pull/3323))
    - Omada zulu 8 to 21 [@bvdberg01](https://github.com/bvdberg01) ([#3318](https://github.com/community-scripts/ProxmoxVE/pull/3318))
    - GoMFT: Fix build dependencies [@tremor021](https://github.com/tremor021) ([#3313](https://github.com/community-scripts/ProxmoxVE/pull/3313))
    - GoMFT: Don't rely on binaries from github [@tremor021](https://github.com/tremor021) ([#3303](https://github.com/community-scripts/ProxmoxVE/pull/3303))
    - Wikijs: Remove Dev Message & Performance-Boost [@bvdberg01](https://github.com/bvdberg01) ([#3232](https://github.com/community-scripts/ProxmoxVE/pull/3232))
    - Snipe-IT: Remove composer update & add no interaction for install [@MickLesk](https://github.com/MickLesk) ([#3256](https://github.com/community-scripts/ProxmoxVE/pull/3256))
    - Fluid-Calendar: Remove unneeded $STD in update [@MickLesk](https://github.com/MickLesk) ([#3250](https://github.com/community-scripts/ProxmoxVE/pull/3250))
    - Update omada download url [@bvdberg01](https://github.com/bvdberg01) ([#3245](https://github.com/community-scripts/ProxmoxVE/pull/3245))
    - TriliumNotes: Fix release handling [@tremor021](https://github.com/tremor021) ([#3160](https://github.com/community-scripts/ProxmoxVE/pull/3160))

  - #### ✨ New Features

    - [core] Rebase Scripts (formatting, highlighting & remove old deps) [@MickLesk](https://github.com/MickLesk) ([#3378](https://github.com/community-scripts/ProxmoxVE/pull/3378))
    - Update nextcloud-vm.sh to 18.1 ISO [@0xN0BADC0FF33](https://github.com/0xN0BADC0FF33) ([#3333](https://github.com/community-scripts/ProxmoxVE/pull/3333))
    - Netdata: Update to newer deb File [@MickLesk](https://github.com/MickLesk) ([#3276](https://github.com/community-scripts/ProxmoxVE/pull/3276))

  - #### 💥 Breaking Changes

    - FluidCalendar: Switch to safer DB operations [@vhsdream](https://github.com/vhsdream) ([#3270](https://github.com/community-scripts/ProxmoxVE/pull/3270))
    - Tandoor: Extend needed dependencies (Read for Update-Functionality)  [@MickLesk](https://github.com/MickLesk) ([#3207](https://github.com/community-scripts/ProxmoxVE/pull/3207))

  - #### 🔧 Refactor

    - Refactor: ErsatzTV Script [@MickLesk](https://github.com/MickLesk) ([#3365](https://github.com/community-scripts/ProxmoxVE/pull/3365))

### 🧰 Maintenance

  - #### ✨ New Features

    - [core] install core deps (debian / ubuntu) [@MickLesk](https://github.com/MickLesk) ([#3366](https://github.com/community-scripts/ProxmoxVE/pull/3366))
    - [core] add gitignore to prevent big pulls [@MickLesk](https://github.com/MickLesk) ([#3278](https://github.com/community-scripts/ProxmoxVE/pull/3278))

  - #### 💾 Core

    - Clarify MTU in advanced Settings. [@michelroegl-brunner](https://github.com/michelroegl-brunner) ([#3296](https://github.com/community-scripts/ProxmoxVE/pull/3296))

  - #### 📂 Github

    - Refactor Changelog Workflow [@michelroegl-brunner](https://github.com/michelroegl-brunner) ([#3371](https://github.com/community-scripts/ProxmoxVE/pull/3371))
    - [core] cleanup - remove old backups of workflow files [@MickLesk](https://github.com/MickLesk) ([#3247](https://github.com/community-scripts/ProxmoxVE/pull/3247))

### 🌐 Website

  - Bump next from 15.1.3 to 15.2.3 in /frontend [@dependabot[bot]](https://github.com/dependabot[bot]) ([#3316](https://github.com/community-scripts/ProxmoxVE/pull/3316))

  - #### 🐞 Bug Fixes

    - JSON editor note fix [@bvdberg01](https://github.com/bvdberg01) ([#3260](https://github.com/community-scripts/ProxmoxVE/pull/3260))
    - Move cryptpad files to right folders [@bvdberg01](https://github.com/bvdberg01) ([#3242](https://github.com/community-scripts/ProxmoxVE/pull/3242))
    - Update Frontend Version Logic [@michelroegl-brunner](https://github.com/michelroegl-brunner) ([#3223](https://github.com/community-scripts/ProxmoxVE/pull/3223))

  - #### ✨ New Features

    - Add Latest Change Date to Frontend [@michelroegl-brunner](https://github.com/michelroegl-brunner) ([#3231](https://github.com/community-scripts/ProxmoxVE/pull/3231))

  - #### 📝 Script Information

    - Proxmox, rather than Promox [@gringocl](https://github.com/gringocl) ([#3293](https://github.com/community-scripts/ProxmoxVE/pull/3293))
    - Audiobookshelf: Fix category on website [@jaykup26](https://github.com/jaykup26) ([#3304](https://github.com/community-scripts/ProxmoxVE/pull/3304))
    - Threadfin: add port for website [@MickLesk](https://github.com/MickLesk) ([#3295](https://github.com/community-scripts/ProxmoxVE/pull/3295))
    - Debian VM: Update webpage with login info [@tremor021](https://github.com/tremor021) ([#3215](https://github.com/community-scripts/ProxmoxVE/pull/3215))
    - CrowdSec: Add debian only warning to website [@tremor021](https://github.com/tremor021) ([#3210](https://github.com/community-scripts/ProxmoxVE/pull/3210))
    - Heimdall Dashboard: Fix missing logo on website [@tremor021](https://github.com/tremor021) ([#3227](https://github.com/community-scripts/ProxmoxVE/pull/3227))
    - Seafile: lowercase slug for Install/Update-Source [@MickLesk](https://github.com/MickLesk) ([#3209](https://github.com/community-scripts/ProxmoxVE/pull/3209))
    - VictoriaMetrics: Fix Wrong Slug [@MickLesk](https://github.com/MickLesk) ([#3225](https://github.com/community-scripts/ProxmoxVE/pull/3225))
    - Website: Lowercase Zitadel-Slug [@MickLesk](https://github.com/MickLesk) ([#3222](https://github.com/community-scripts/ProxmoxVE/pull/3222))

## 2025-03-03

### 🚀 Initial Release