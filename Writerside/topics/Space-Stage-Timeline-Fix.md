# Space Stage Timeline Fix
<link-summary>Fixes a Spore bug that messes up your creatures timeline in adventure mode</link-summary>
<web-summary>Fixes a Spore bug that messes up your creatures timeline in adventure mode</web-summary>
<card-summary>Fixes a Spore bug that messes up your creatures timeline in adventure mode</card-summary>

<include from="Snippets.topic" element-id="requires-mod-api"/>

This mod fixes the bug causing your spore creatures timeline to get obliterated if you befriend a creature while in an adventure.
The key difference, is that because this uses the mod api, while preventing the bug from occurring in space stage, it also prevents it from occurring in creature stage, the only thing this doesn't fix is already affected timelines.

All timelines created after this mod being installed will look correct regardless of which stages timeline you choose to preserve.

<procedure title="Mod Options" type="choices">
    <step>
        <emphasis>Preserve Creature Stage:</emphasis>
        <p>
        If this is chosen, for timelines are already broken, the creature stage timeline will be preserved.
        </p>
        <p>
        Always choose this if your timeline is not broken.
        </p>
    </step>
    <step>
        <emphasis>Preserve Space Stage:</emphasis>
        <p>
        If this is chosen, for timelines are already broken, the space stage timeline will be preserved.
        </p>
    </step>
</procedure>

<include from="Snippets.topic" element-id="mod-download-save-dependency">
    <var name="download" value="https://github.com/Zarklord/SpaceStageTimelineFix/releases/download/v1.0.1/SpaceStageTimelineFixv1.0.1.sporemod"/>
    <var name="issue" value="https://github.com/Zarklord/SpaceStageTimelineFix/issues"/>
</include>

## Version History
<deflist collapsible="true" default-state="collapsed">
    <def title="v1.0.1" default-state="expanded">
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
