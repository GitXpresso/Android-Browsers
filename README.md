# Android browsers list:
Curated list of Android browsers

## To-do:
- [X] add links to the added browsers
- [ ] Add Table of Contents after adding all the browsers
- [ ] add all Android mobile browsers
   * - [ ] add AOSmium browser
   * - [ ] Privacy browser
   * - [ ] DuckDuckDuck Go
   * - [ ] Arc Search
   * - [ ] Ceno browser
   * - [ ] + plus more
- [ ] pretty-ify markdown
    * * [ ] Add browser logos
    * - [ ] Add latest release version
    * - [ ] Add Obtainium, F-Droid, Plus more if available
    * - [ ] Add Markdown Badges
# Android browser list:
## Chromium forks:
**NOTE:** Not all extensions will behave or work as expected from any chromium android forks with extension support.
### Cromite (maintained fork of bromite):
#### Link: https://github.com/uazo/cromite
#### Description: Take back your browser!
#### New Release regularly?: **Yes**
#### Features:
* Extensions support (experimental feature - not all extensions will work as expected) **enable extensions via developer menu**
* Userscript support in settings (Why?: because tampermonkey will be blocked by cromite)
* Hardened browser
* super fast

\+ more

**fun fact:** Uazo worked on bromite, before bromite was archived.
### Helium: 
#### Link: https://github.com/jqssun/android-helium-browser
#### Description: Private, Secure, with webextensions support
#### New Release regularly?: **Yes**
#### Information:
**Warning:** All builds (releases) are experimental.
* Support extensions (already supported when installed)
* based on Vanadium + Helium browser (PC)
* WebRTC IP Policy
### Ultimatum
#### Link: https://github.com/gonzazoid/Ultimatum
#### Description: Chromium fork with webextensions support, ani-detect browser features + more
#### New Release regularly?: **Yes**
#### Information:
* extensions support 
* anti-detect browser features
* support for web3.0
* **Not a Hardened browser**
  - **What makes it not a hardened browser:**
    - Chrome Sync isn't disabled by default like Cromite or Helium.
    - Integrated Google services isn't disabled
    - AI mode isn't disabled 
    - plus other things that come with chromium (android desktop)
## Firefox forks:
### SmartCookieWeb-Preview:
#### Link: https://github.com/CookieJarApps/SmartCookieWeb-Preview/forks
#### Description: Redesign of SmartCookieWeb using GeckoView
#### New Release regularly?: **No**
#### Features:
* Extension support (both mobile and desktop)
* Modern Clean UI
* Fast
* Import/Export settings integration
* Included search engines:
  - Google (default)
  - DuckDuckGo
  - Bing
  - Yandex
  - Naver
  - Qwant
  - Startpage
* Enabled by default:
  - **Security & Privacy:**
    - Tracking Protection
    - Safe browsing
  - **Browser:**  
    - Javascript
    - Search suggestions
    - Swipe to refresh
  - **Webpage:**   
    - Hide URL while scrolling
    - Auto font size
  - **Homepage:**
    - Show shortcuts (homepage)
    - Load website icons into shortcuts  
### Nira browser (alpha):
**Warning:** in Alpha, may still contain bugs and issues.
#### Link: https://github.com/prirai/nira-browser
#### Description: Experience the web with power, privacy, and performance. (SmartCookieWeb-Preview fork)
#### New Release regularly?: **Yes**
#### Features:
**TL;DR (download worthy features):** 
* Built-in adblocking
* Material 3 Design
* Multiple profile system (isolated cookies, sessions and browsing data)
* Private browsing integration
* Uses SmartCookieWeb-Preview Icon

**NOTE: "Complete Features Set" pasted from Github repo (some text altered a little bit)**

**Complete feature set:**
* Tab Groups support (with multiple view modes: list, and bar with groups)
* Bookmark support (import/export + folder navigation)
* Supports Firefox extensions (including desktop extensions)
* Theming options
  - Light
  - Dark
  - Material 3 dynamic color (A12+)
  - Amoled
* Position toolbar on top or bottom
* Contextual Toolbar is a smart toolbar that adapts based on page context
* Homepage shows shortcuts and bookmarks for easy access
* Allow showing/hiding different components of the app for full freedom
* **Multiple Search Engines:**
  - Google 
  - DuckDuckGo 
  - Bing
  - Baidu
  - Brave
  - Naver
  - Qwant
  - Startpage
  - Yandex 
* Distraction-free reading with customizable fonts and colors
* Convert PDF to webpage
* Custom Tab integration when opening links from other apps
* Built-in download manager with external downloader support
* LRU tab navigation by swiping left or right to backward to navigation tabs by their order of recency
* Background audio/video with media session controls
**Multiple Language support:**
  - Arabic
  - French
  - Italian
  - Japanese
  - Polish
  - Portuguese (BR & PT)
  - Russian
  - Turkish
  - Vietnamese
  - Chinese (CN)
* Create separate profiles for work, personal, shopping, or any use case with full cookie and data isolation and a unique color and emoji to easily identify profiles
* Switch between profiles seamlessly without losing your tabs
* Install web apps as standalone applications with one tap with smart suggestions including binding pwa storage with a specific profile
* Enable/disable, update, or uninstall PWAs from settings
### Iceraven:
#### link: https://github.com/fork-maintainers/iceraven-browser
#### Description: Definitely not brought to you by Mozilla!
#### New Release regularly?: **Yes**
#### Features:
* Customizable (but not that customizable)
* Desktop and Android firefox extensions support
* feature: hide Firefox sync
* supports about:config
### Fennec browser:
#### Link: https://f-droid.org/en/packages/org.mozilla.fennec_fdroid/
#### Description:  It has proprietary bits and telemetry removed, but still connects to various Mozilla Services.
#### New Release regularly?: **Yes**
#### Features
* Supports about:config
* Has a wide variety search engines already added
* Disables Mozilla telemetry by default
* Improved tracking protection
### Ironfox (maintained fork of Mull):
#### Link: https://github.com/ironfox-oss/IronFox
#### Description: continue the legacy of Mull by providing a free and open source, privacy and security-oriented web browser for daily use.
#### New Release regularly?: **Yes**
#### Features:
* hardened browser
* supports about:config
* supports Unified Push
* has its own "librewolf privacy settings" equivalent
* duckduckgo default search engine
* Cookie Banner Blocker in Private browsing
* **search engines:**
  - DuckDuckGo (default search engine)
  - DuckDuckGo (No AI)
  - DuckDuckGo (HTML)
  - DuckDuckGo (Lite)
  - Marginalia
  - Mojeek
  - Startpage
  - Startpage (EU)
  - Wikipedia
  - No Search
* **setup screen:**
  - spoof langauge to en-US (make browser less unique)
  - choose DOH protection strength + pick DOH Provider
  - Install Ublock origin (earlier versions)
  - enable Javascript Just-in-Time (improves performance for complex webpages)
  - Safe browsing (uses Google Safe Browsing service)
* **Ironfox settings:**
  - **Media autoplay:**
    - Sticky [off by default]
    - Transcient [on by default]
    - Click-to-Play [off by default]
  - **Preferred website appearance:**
    - Light [on by default]
    - Dark [off by default]
    - follow browser theme [off by default]
  - **Privacy And Security:**
    - Disable WebGL [on by default]
    - Enable accessibility features [off by default]
    - Enable javascript [on by default]
    - Enable WebGL overrides from IronFox [on by default]
  - **Privacy:**
    - **Cross-origin referer policy:**
      - Always send cross-origin referers [on by default]
      - Send cross-origin referers when based domains match
      - Disable Cross-origin referers
      
    - Always use private browsing mode [off by default] 
    - Enable disk cache [off by default]
    - Enable fingerprinting overrides from IronFox [on by default]
    - Enable fingerprinting overrides from Mozilla [on by default]
    - Enable timezone spoofing overrides from IronFox [on by default & grayed out]
    - Request English versions of webpages [on by default]
    - Spoof timezone to UTC-0 (ungrays "Enable timezone spoofing overrides from IronFox")[off by default]
  - **Security:**
    - Allow Installation of add-ons (enable extensions)[off by default]
    - Enable Safe-browsing [on/off based on decision in setup menu]
    - Enable print capabilities (allows the use of a printer)[on by default]
    - Enable Scalable Vector Graphics (SVG)[on by default]
    - Enable WebAssembly (WASM)[on by default]
    - Enable WebRTC [on by default]
    - Enable Javascript Just-in-Time Compilation for extensions [off by default]
    - Enable Javascript Just-in-Time Compilation [on/off based on decision in setup menu]
  - **Miscellaneous:**
    - Enable collections [on by default]
    - Enable Firefox Translations (able to translate webpages to your desired language)[on by default]
    - Enable IPv6 network connectivity [on by default]
    - Open PDFS externally (open PDFS in your preferred PDF Viewer app/or default PDF viewer app)[off by default]
    - use Unified Push (allow notifications to pop-up on screen)[off by default]
- **IronFox Labs:**
    - Homepage as a New Tab
    
**_Finished Markdown?:_** No    
