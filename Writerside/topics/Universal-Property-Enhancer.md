# Universal Property Enhancer
<web-summary>A Spore ModAPI mod that allows extending and modifying any property file</web-summary>
<link-summary>Universally extend and edit property files</link-summary>
<card-summary>Universally extend and edit property files</card-summary>

<include from="Snippets.topic" element-id="requires-mod-api"/>
<include from="Snippets.topic" element-id="api-only-mod"/>

This Mod Uses the Mod API to allow for making changes to prop files without editing them such as:
- Changing a property universally across all files.
- Adding/Remove properties to any file.
- Duplicate a property file to multiple locations

Additionally, you can add custom palette icons to categories with this mod.

This allows you to do things like [Infinite Part Scaling](Infinite-Part-Scaling.md), without having to edit the prop file for every part.

<include from="Snippets.topic" element-id="mod-download"/>
<var name="download" value="https://github.com/Zarklord/UniversalPropertyEnhancer/releases/download/v1.2.0/UPEv1.2.0.sporemod"/>
<var name="issue" value="https://github.com/Zarklord/UniversalPropertyEnhancer/issues"/>

## Version History
<deflist collapsible="true" default-state="collapsed">
    <def title="v1.2.0" default-state="expanded">
    <list>
        <li>Fixed the game crashing when closing</li>
        <li>Fixed a memory leak</li>
        <li>VerifyUPE no longer requires a package to be installed, instead the data is generated, tested and then removed dynamically</li>
        <li>UPE Tests run automatically, and print to the log file when launching the game (VerifyUPE can still be run to view the results in the cheat console)</li>
        <li>Added proper support for mods packed with older versions of SMFX
            <list>
                <li>Proper support for prop mods packed with pre Feb 2020 SMFX (strings didn't get the last character serialized into the prop file)</li>
                <li>Proper support for prop mods packed with pre June 2023 SMFX (array strings had the wrong data size)</li>
            </list>
        </li>
        <li>Added proper support for prop mods packed in the future with the increased knowledge of prop flags</li>
    </list>
    </def>
    <def title="v1.1.3">
        <list>
            <li>Added better detection for legacy string8s arrays, fixing some crashes</li>
        </list>
    </def>
    <def title="v1.1.2">
        <list>
            <li>Fixed a crash when using postinits packages on SporeModder FX v2.1.34 or later</li>
        </list>
    </def>
    <def title="v1.1.1">
        <list>
            <li>Fixed a bug causing the mod to not work when visual studio was not installed</li>
        </list>
    </def>
    <def title="v1.1.0">
        <list>
            <li>Added support for custom palette icons</li>
        </list>
    </def>
    <def title="v1.0.0">
        <list>
            <li>Renamed from Universal Property Replacer to Universal Property Enhancer</li>
            <li>Improved the method for replacing properties, along with adding support for all types (including arrays) that can be used in prop files.</li>
            <li>Added a prop file postinit system, allowing you to add and remove properties specific prop files</li>
            <li>A bunch of bug fixes and updated to the newest mod API</li>
        </list>
    </def>
    <def title="v0.2.1">
        <list>
            <li>Fixed a silly bug breaking the mod</li>
        </list>
    </def>
    <def title="v0.2.0">
        <list>
            <li>Fixed a major logic error which prevented the mod from working as intended</li>
        </list>
    </def>
    <def title="v0.1.1">
        <list>
            <li>Fixed a cheatlog printing bug</li>
        </list>
    </def>
    <def title="v0.1.0">
        <list>
            <li>Initial Release</li>
        </list>
    </def>
</deflist>

<seealso style="cards">
    <category ref="external">
        <a href="https://github.com/Zarklord/UniversalPropertyEnhancer/" summary="Source Code">Github</a>
    </category>
    <category ref="docs">
        <a href="https://zarklord.github.io/UniversalPropertyEnhancer/documentation.html" summary="Universal Property Enhancer Docs">Modding Documentation</a>
    </category>
</seealso>