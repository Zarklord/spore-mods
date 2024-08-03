# Space Stage Timeline Fix
<link-summary>Fixes a Spore bug that messes up your creatures timeline in adventure mode</link-summary>
<web-summary>Fixes a Spore bug that messes up your creatures timeline in adventure mode</web-summary>
<card-summary>Fixes a Spore bug that messes up your creatures timeline in adventure mode</card-summary>

<include from="Snippets.topic" element-id="requires-mod-api"/>

This mod fixes the bug causing your spore creatures timeline to get obliterated if you befriend a creature while in an adventure.
The key difference, is that because this uses the mod api, while preventing the bug from occurring in space stage, it also prevents it from occurring in creature stage.

<include from="Snippets.topic" element-id="mod-download">
    <var name="download" value="https://github.com/Zarklord/SpaceStageTimelineFix/releases/download/v2.0.0/SpaceStageTimelineFixv2.0.0.sporemod"/>
    <var name="issue" value="https://github.com/Zarklord/SpaceStageTimelineFix/issues"/>
</include>

## Version History
<deflist collapsible="true" default-state="collapsed">
    <def title="v2.0.0" default-state="expanded">
        <list>
            <li>This now always fixes the timeline, regardless of when you install the mod.</li>
            <li>No longer introduces a save data dependency.</li>
        </list>
    </def>
    <def title="v1.0.1">
        <list>
            <li>Fixed a bug causing the mod to not work when visual studio was not installed</li>
        </list>
    </def>
    <def title="v1.0.0">
        <list>
            <li>Initial Release</li>
        </list>
    </def>
</deflist>

<seealso style="cards">
    <category ref="external">
        <a href="https://github.com/Zarklord/SpaceStageTimelineFix" summary="Source Code and Package Sources">Github</a>
    </category>
</seealso>
