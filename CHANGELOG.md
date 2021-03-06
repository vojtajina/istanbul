Changelog
---------

<table>
<tr><td>v0.1.39</td><td>add <source> tag to cobertura report, pull request by @jhansche</td></tr>
<tr><td>v0.1.38</td><td><ul>
        <li>factor out AST instrumentation into own instrumentASTSync method</li>
        <li>always set function declaration coverage stats to 1 since every such declaration is "executed" exactly one time by the compiler</li>
    </ul></td></tr>
<tr><td>v0.1.37</td><td>--complete-copy flag contrib from @kami, correct strict mode semantics for instrumented functions</td></tr>
<tr><td>v0.1.36</td><td>real quiet when --print=none specified, add repo URL to package.json, add contributors</td></tr>
<tr><td>v0.1.35</td><td>accept cobertura contrib from @nbrownus, fix #52</td></tr>
<tr><td>v0.1.34</td><td>fix async reporting, update dependencies, accept html cleanup contrib from @mathiasbynens</td></tr>
<tr><td>v0.1.33</td><td>initialize global coverage object before running tests to workaround mocha leak detection</td></tr>
<tr><td>v0.1.32</td><td>Fix for null nodes in array expressions, add @unindented as contributor</td></tr>
<tr><td>v0.1.31</td><td>Misc internal fixes and test changes</td></tr>
<tr><td>v0.1.30</td><td>Write standard blurbs ("writing coverage object..." etc.) to stderr rather than stdout</td></tr>
<tr><td>v0.1.29</td><td>Allow --post-require-hook to be a module that can be `require`-d</td></tr>
<tr><td>v0.1.28</td><td>Add --post-require-hook switch to support use-cases similar to the YUI loader</td></tr>
<tr><td>v0.1.27</td><td>Add --hook-run-in-context switch to support RequireJS modules. Thanks to @millermedeiros for the pull request</td></tr>
<tr><td>v0.1.26</td><td>Add support for minimum uncovered unit for check-coverage. Fixes #25</td></tr>
<tr><td>v0.1.25</td><td>Allow for relative paths in the YUI loader hook</td></tr>
<tr><td>v0.1.24</td><td>Add lcov summaries. Fixes issue #20</td></tr>
<tr><td>v0.1.23</td><td>Add ability to save a baseline coverage file for the instrument command. Fixes issue #19</td></tr>
<tr><td>v0.1.22</td><td>Add signature attribute to cobertura method tags to fix NPE by the Hudson publisher</td></tr>
<tr><td>v0.1.21</td><td>Add cobertura XML report format; exprimental for now</td></tr>
<tr><td>v0.1.20</td><td>Fix HTML/ lcov report interface to be more customizable for middleware needs</td></tr>
<tr><td>v0.1.19</td><td>make all hooking non-destructive in that already loaded modules are never reloaded. Add self-test mode so that already loaded istanbul modules can be unloaded prior to hooking.</td></tr>
<tr><td>v0.1.18</td><td>Add option to hook in non-destructive mode; i.e. the require cache is not unloaded when hooking</td></tr>
<tr><td>v0.1.17</td><td>Export some more objects; undocumented for now</td></tr>
<tr><td>v0.1.16</td><td>Fix npm keywords for istanbul which expects an array of strings but was being fed a single string with keywords instead</td></tr>
<tr><td>v0.1.15</td><td>Add the 'check-coverage' command so that Istanbul can be used as a posttest script to enforce minimum coverage</td></tr>
<tr><td>v0.1.14</td><td>Expose the experimental YUI load hook in the interface</td></tr>
<tr><td>v0.1.13</td><td>Internal jshint cleanup, no features or fixes</td></tr>
<tr><td>v0.1.12</td><td>Give npm the README that was getting inadvertently excluded</td></tr>
<tr><td>v0.1.11</td><td>Merge pull request #14 for HTML tweaks. Thanks @davglass. Add @davglass and @nowamasa as contributors in `package.json`</td></tr>
<tr><td>v0.1.10</td><td>Fix to issue #12. Do not install `uncaughtException` handler and pass input error back to CLI using a callback as opposed to throwing.</td></tr>
<tr><td>v0.1.9</td><td>Attempt to create reporting directory again just before writing coverage in addition to initial creation</td></tr>
<tr><td>v0.1.8</td><td>Fix issue #11.</td></tr>
<tr><td>v0.1.7</td><td>Add text summary and detailed reporting available as --print [summary|detail|both|none]. summary is the default if nothing specified.</td></tr>
<tr><td>v0.1.6</td><td>Handle backslashes in the file path correctly in emitted code. Fixes #9. Thanks to @nowamasa for bug report and fix</td></tr>
<tr><td>v0.1.5</td><td>make object-utils.js work on a browser as-is</td></tr>
<tr><td>v0.1.4</td><td>partial fix for issue #4; add titles to missing coverage spans, remove negative margin for missing if/else indicators</td></tr>
<tr><td>v0.1.3</td><td>Set the environment variable running_under_istanbul to 1 when that is the case. This allows test runners that use istanbul as a library to back off on using it when set.</td></tr>
<tr><td>v0.1.2</td><td>HTML reporting cosmetics. Reports now show syntax-colored JS using `prettify`. Summary tables no longer wrap in awkward places.</td></tr>
<tr><td>v0.1.1</td><td>Fixes issue #1. HTML reports use sources embedded inside the file coverage objects if found rather than reading from the filesystem</td></tr>
<tr><td>v0.1.0</td><td>Initial version</td></tr>
</td></tr>
</table>

