# Supported languages, frameworks, and feature availability overview

Get an overview of supported languages and package managers across Snyk environments, including feature availability for open source and licensing (Snyk Open Source) and code analysis (Snyk Code).&#x20;

## Open source and licensing (Snyk Open Source)

The following table lists the programming languages, fully supported package managers, and features for Snyk Open Source.

<table data-full-width="false"><thead><tr><th width="247">Language and package manager</th><th width="146" align="center">Git integration (SCM)</th><th width="106" align="center">Snyk CLI, plugins (IDE), CI/CD</th><th>Features</th></tr></thead><tbody><tr><td><p><a href="../snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-.net.md"><strong>.Net</strong></a> </p><ul><li><a href="broken-reference"><strong>NuGet</strong></a></li><li><strong>Paket</strong></li></ul></td><td align="center">Nuget only </td><td align="center"><strong>✔︎</strong></td><td><ul><li>Fix PRs (Nuget only)</li><li>License scanning</li><li>Reports </li></ul></td></tr><tr><td><a href="../snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-c-c++.md"><strong>C/C++</strong></a></td><td align="center"><span data-gb-custom-inline data-tag="emoji" data-code="2796">➖</span></td><td align="center"><strong>✔︎</strong></td><td><ul><li>License scanning</li></ul><ul><li>Reports </li></ul></td></tr><tr><td><p><a href="../snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-elixir.md"><strong>Elixir</strong></a> </p><ul><li><strong>Hex</strong></li></ul></td><td align="center"><span data-gb-custom-inline data-tag="emoji" data-code="2796">➖</span></td><td align="center"><strong>✔︎</strong></td><td><p></p><ul><li>License scanning</li></ul><ul><li>Reports </li></ul></td></tr><tr><td><p><a href="../snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-go.md"><strong>Go</strong></a> </p><ul><li><strong>Go Modules</strong></li><li><strong>dep</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><p></p><ul><li>License scanning</li></ul><ul><li>Reports </li></ul></td></tr><tr><td><p><a href="../snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-java-and-kotlin.md"><strong>Java and Kotlin</strong></a> </p><ul><li><strong>Maven</strong></li><li><strong>Gradle</strong></li></ul></td><td align="center">Maven and Gradle with lockfile</td><td align="center"><strong>✔︎</strong></td><td><p></p><ul><li>Fix PRs (Maven)</li></ul><ul><li>License scanning</li></ul><ul><li>Reports </li></ul></td></tr><tr><td><p><a href="javascript/"><strong>JavaScript</strong></a> </p><ul><li><strong>npm</strong></li><li><strong>Yarn</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><p></p><ul><li>Fix PRs</li></ul><ul><li>License scanning</li></ul><ul><li>Reports </li></ul></td></tr><tr><td><p><a href="../snyk-code/security-rules-used-by-snyk-code/php-rules.md"><strong>PHP</strong></a> </p><ul><li><strong>Composer</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><ul><li>License scanning</li></ul><ul><li>Reports </li></ul></td></tr><tr><td><p><a href="../snyk-code/security-rules-used-by-snyk-code/python-rules.md"><strong>Python</strong></a> </p><ul><li><strong>Pip</strong></li><li><strong>PyPI</strong></li><li><strong>Poetry</strong></li><li><strong>pipenv</strong></li><li><a href="../snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-python.md#setup.py"><strong>setup.py</strong></a></li></ul></td><td align="center">Pip, PyPI and Poetry only</td><td align="center"><strong>✔︎</strong></td><td><p></p><ul><li>Fix PRs (Pip/PyPi)</li></ul><ul><li>License scanning</li></ul><ul><li>Reports </li></ul></td></tr><tr><td><p><a href="../snyk-code/security-rules-used-by-snyk-code/ruby-rules.md"><strong>Ruby</strong></a> </p><ul><li><strong>RubyGem</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><p></p><ul><li>Fix PRs</li></ul><ul><li>License scanning</li></ul><ul><li>Reports </li></ul></td></tr><tr><td><p><a href="../snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-scala.md"><strong>Scala</strong></a> </p><ul><li><strong>sbt</strong></li></ul></td><td align="center">CLI recommended for stability</td><td align="center"><strong>✔︎</strong></td><td><p></p><ul><li>License scanning</li></ul><ul><li>Reports </li></ul></td></tr><tr><td><p><a href="../snyk-open-source/snyk-open-source-supported-languages-and-package-managers/snyk-for-swift-and-objective-c-cocoapods.md"><strong>Swift and Objective-C</strong></a> </p><ul><li><strong>Cocoapods</strong></li><li><strong>Swift Package Manager</strong></li></ul></td><td align="center"><span data-gb-custom-inline data-tag="emoji" data-code="26aa">⚪</span>Cocoapods only</td><td align="center"><strong>✔︎</strong></td><td><p></p><ul><li>License scanning</li></ul><ul><li>Reports </li></ul></td></tr></tbody></table>

## Code analysis (Snyk Code)

The following table lists the programming languages and fully supported frameworks and features for Snyk Code.

<table data-full-width="false"><thead><tr><th width="232">Language and framework</th><th width="131" align="center">Git integration (SCM)</th><th width="207" align="center">Snyk CLI, plugins (IDE), CI/CD</th><th>Features</th></tr></thead><tbody><tr><td><strong>Apex</strong></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><ul><li>Reports</li><li>Custom rules</li></ul></td></tr><tr><td><p><strong>C#</strong> </p><ul><li><strong>.NET</strong></li><li><strong>ASP.NET</strong></li><li><strong>.NET Core</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><p></p><ul><li>Reports</li></ul><ul><li>Custom rules</li></ul></td></tr><tr><td><p><strong>C/C++ (beta)</strong></p><ul><li><strong>C++ Standard Library</strong></li><li><strong>POSIX</strong></li><li><strong>Win32</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><p></p><p>Reports</p></td></tr><tr><td><strong>Go</strong></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><p></p><ul><li>Reports</li></ul><ul><li>Custom rules</li></ul></td></tr><tr><td><p><strong>Java</strong> </p><ul><li><strong>Apache Camel</strong> </li><li><strong>Apache Struts</strong></li><li><strong>Spring MVC</strong></li><li><strong>Spring JDBC</strong></li><li><strong>Jakarta XML Services</strong></li><li><strong>Dropwizard</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><p></p><ul><li>Reports</li></ul><ul><li>Custom rules</li></ul></td></tr><tr><td><p><strong>JavaScript</strong></p><ul><li><strong>React</strong></li><li><strong>Vue.js</strong></li><li><strong>Express</strong></li><li><strong>JQuery</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><p></p><ul><li>Reports</li></ul><ul><li>Custom rules</li></ul></td></tr><tr><td><strong>Kotlin</strong> <strong>(beta)</strong></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td>Reports</td></tr><tr><td><p><strong>PHP</strong></p><ul><li><strong>Symfony</strong></li><li><strong>Laravel</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><p></p><ul><li>Reports</li></ul><ul><li>Custom rules</li></ul></td></tr><tr><td><p><strong>Python</strong></p><ul><li><strong>Django</strong></li><li><strong>Flask</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><p></p><ul><li>Reports</li></ul><ul><li>Custom rules</li></ul></td></tr><tr><td><p><strong>Ruby</strong> </p><ul><li><strong>Ruby On Rails</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><p></p><ul><li>Reports</li></ul><ul><li>Custom rules</li></ul></td></tr><tr><td><p><strong>Scala (beta)</strong></p><ul><li><strong>Play</strong> </li><li><strong>Akka</strong></li><li><strong>HTTP4S</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td>Reports</td></tr><tr><td><p><strong>Swift (beta)</strong> </p><ul><li><strong>AlamoFire</strong></li><li><strong>Pathos</strong></li><li><strong>SQLite</strong></li><li><strong>CryptoKit</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td>Reports</td></tr><tr><td><strong>TypeScript</strong></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><p></p><ul><li>Reports</li></ul><ul><li>Custom rules</li></ul></td></tr><tr><td><strong>VB.NET (beta)</strong></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td>Reports</td></tr></tbody></table>