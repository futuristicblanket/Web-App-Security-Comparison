## Web App Security Tools Comparison

This document compares the four major free web app security tools. This document was last updated in June 2017 and was created as a work experience project.

### The Test

Each tool was tested using the [OWASP NodeGoat project](https://github.com/OWASP/NodeGoat).

### Table of comaprison

| Tool | Licence | Platofrms |Pros | Cons | Common Vulnerabilities Detected | 
| ----- | ---- | ------- | ---------- | ---------- | ---------- |
| [Golismero](http://golismero-project.com/) | [GPL v2.0](https://github.com/golismero/golismero/blob/master/LICENSE) | [Linux](https://github.com/golismero/golismero#debianubuntu), [FreeBSD](https://github.com/golismero/golismero#freebsd-10-release), [MacOS](https://github.com/golismero/golismero#mac-os-x), [Windows](https://github.com/golismero/golismero#windows) | Golismero runs from the command line, so it's easy to run from an external server. It's simple and easy to use, and is great for scanning websites not behind a login. It has a strong plugin collection and is easy to build plugins. | Many of Golismero's built in plugins require a connection to the internet to work properly, so it's diificult to test on an isolated network. |
| [OWASP ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project) | [Apache v2.0](https://github.com/zaproxy/zaproxy/blob/develop/LICENSE) | [Linux](https://github.com/zaproxy/zaproxy/releases/download/2.6.0/ZAP_2_6_0_unix.sh), [MacOS](https://github.com/zaproxy/zaproxy/releases/download/2.6.0/ZAP_2_6_0_macos.dmg), [Windows](https://github.com/zaproxy/zaproxy/releases/download/2.6.0/ZAP_2_6_0_windows-x32.exe) |
