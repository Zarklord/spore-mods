# Cell Stage+
<link-summary>Enables all 40 cell parts to be usable in Cell Stage</link-summary>
<web-summary>Enables all 40 cell parts to be usable in Cell Stage</web-summary>
<card-summary>Enables all 40 cell parts to be usable in Cell Stage</card-summary>

<include from="Snippets.topic" element-id="requires-mod-api"/>
<include from="Snippets.topic" element-id="requires-upe"/>

Enables all 40 cell parts to be usable during cell stage.

<deflist collapsible="true" default-state="collapsed">
    <def title="Early Cell Stage Editor">
        <tabs>
            <tab title="Mouths">
                <img src="CELLMOUTHSTART.png" alt="CELLMOUTHSTART.png" thumbnail="true"/>
            </tab>
            <tab title="Eyes">
                <img src="CELLEYESTART.png" alt="CELLEYESTART.png" thumbnail="true"/>
            </tab>
            <tab title="Movement">
                <img src="CELLMOVEMENTSTART.png" alt="CELLMOVEMENTSTART.png" thumbnail="true"/>
            </tab>
            <tab title="Weapons">
                <img src="CELLATTACKSTART.png" alt="CELLATTACKSTART.png" thumbnail="true"/>
            </tab>
        </tabs>
    </def>
    <def title="Fully Unlocked Cell Stage Editor">
        <tabs>
            <tab title="Mouths">
                <img src="CELLMOUTHEND.png" alt="CELLMOUTHEND.png" thumbnail="true"/>
            </tab>
            <tab title="Eyes">
                <img src="CELLEYEEND.png" alt="CELLEYEEND.png" thumbnail="true"/>
            </tab>
            <tab title="Movement">
                <img src="CELLMOVEMENTEND.png" alt="CELLMOVEMENTEND.png" thumbnail="true"/>
            </tab>
            <tab title="Weapons">
                <img src="CELLATTACKEND.png" alt="CELLATTACKEND.png" thumbnail="true"/>
            </tab>
        </tabs>
    </def>
    <def title="Cell to Creature Stage Editor">
        <tabs>
            <tab title="Mouths">
                <img src="CELL2CREATUREMOUTH.png" alt="CELL2CREATUREMOUTH.png" thumbnail="true"/>
            </tab>
            <tab title="Eyes">
                <img src="CELL2CREATUREEYE.png" alt="CELL2CREATUREEYE.png" thumbnail="true"/>
            </tab>
            <tab title="Legs">
                <img src="CELL2CREATURELEGS.png" alt="CELL2CREATURELEGS.png" thumbnail="true"/>
            </tab>
            <tab title="Weapons">
                <img src="CELL2CREATUREATTACK.png" alt="CELL2CREATUREATTACK.png" thumbnail="true"/>
            </tab>
            <tab title="Detail">
                <img src="CELL2CREATUREMOVEMENT.png" alt="CELL2CREATUREMOVEMENT.png" thumbnail="true"/>
            </tab>
        </tabs>
    </def>
</deflist>

<procedure title="Mod Options" type="choices">
    <step>
        <emphasis>API Only:</emphasis>
        <p>Installs the API for making more parts available.</p>
        <p>Only choose this when instructed by another mod.</p>
    </step>
    <step>
        <emphasis>Part Unlocks:</emphasis>
        <p>Installs the API, and the config files to make the other 28 cell parts unlock-able.</p>
        <p>Only choose this when instructed by another mod.</p>
    </step>
    <step>
        <emphasis>Part Improvements:</emphasis>
        <p>Installs the API, Part Unlocks, and the improvements to make those 28 parts look and act like the normal parts.</p>
        <p>Only choose this when instructed by another mod.</p>
    </step>
    <step>
        <emphasis>Editor Improvements:</emphasis>
        <p>Installs the API, Part Unlocks, Part Improvements, and changes to the Cell and Cell to Creature Editors, to allow you to use the cell parts in game.</p>
        <p>Choose this option unless instructed by another mod.</p>
    </step>
</procedure>

<include from="Snippets.topic" element-id="mod-download">
    <var name="download" value="https://github.com/Zarklord/CellStagePartsAPI/releases/download/1.0.0/CellStagePlus.sporemod"/>
    <var name="issue" value="https://github.com/Zarklord/CellStagePartsAPI/issues"/>
</include>

## Version History
<deflist collapsible="true" default-state="collapsed">
    <def title="v1.0.0" default-state="expanded">
        <list>
            <li>Initial Release</li>
        </list>
    </def>
</deflist>

<seealso style="cards">
    <category ref="external">
        <a href="https://github.com/Zarklord/CellStagePartsAPI/" summary="Source Code">Github</a>
    </category>
</seealso>