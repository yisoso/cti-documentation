---
layout: page
title: Visualized SDO Relationships
categories: examples
---

<script src="{{ site.baseurl }}/js/visualized_sdo_relationships.js"></script>

This example iterates over all SDOs and visually represents possible relationships of each SDO to another. Visual representations can simplify understanding and are often easier to interpret than text alone. All graphs were created with [Graphviz](http://graphviz.org/){: target="_blank"}. To download the Graphviz files [go here](#graphviz-dot-files------graphviz-png-files).

**Overview of All Relationships**
------------

The graphic below shows how each SDO fits in the overall SDO ecosystem with regard to its possible relationships.

**Note:** Report and Observed Data do not have any relationships.

<a href="{{site.baseurl}}/img/relationships/SDO_Relationships_Graphviz.svg"><img alt="nope" src="{{site.baseurl}}/img/relationships/SDO_Relationships_Graphviz.png"></a>

**SDO Relationships**
--------------

Click the SDO in the table you wish to view.
<div class="row">
    <div class="col-md-4" markdown="1">

{: .table }
| ![Attack Pattern]({{ site.baseurl }}/img/icons/attack_pattern.png){: .relationshipIcon data-tag="Attack_Pattern"} | ![Campaign]({{ site.baseurl }}/img/icons/campaign.png){: .relationshipIcon data-tag="Campaign"} | ![Course of Action]({{ site.baseurl }}/img/icons/course_of_action.png){: .relationshipIcon data-tag="Course_of_Action"} |
| ![Identity]({{ site.baseurl }}/img/icons/identity.png){: .relationshipIcon data-tag="Identify"} | ![Indicator]({{ site.baseurl }}/img/icons/indicator.png){: .relationshipIcon data-tag="Indicator"} | ![Intrusion Set]({{ site.baseurl }}/img/icons/intrusion_set.png){: .relationshipIcon data-tag="Intrusion_Set"} |
| ![Malware]({{ site.baseurl }}/img/icons/malware.png){: .relationshipIcon data-tag="Malware"} | ![Observed Data]({{ site.baseurl }}/img/icons/observed_data.png){: .relationshipIcon data-tag="Observed_Data"} | ![Report]({{ site.baseurl }}/img/icons/report.png){: .relationshipIcon data-tag="Report"} |
| ![Threat Actor]({{ site.baseurl }}/img/icons/threat_actor.png){: .relationshipIcon data-tag="Threat_Actor"} | ![Tool]({{ site.baseurl }}/img/icons/tool.png){: .relationshipIcon data-tag="Tool"} | ![Vulnerability]({{ site.baseurl }}/img/icons/vulnerability.png){: .relationshipIcon data-tag="Vulnerability"} |

</div>

<div class="col-md-8 text-center">
    <object class="relationshipGraph" id="Attack_Pattern" data="{{ site.baseurl }}/img/relationships/Attack Pattern.svg" type="image/svg+xml">Attack Pattern</object>
    <object class="relationshipGraph" id="Campaign" data="{{ site.baseurl }}/img/relationships/Campaign.svg" type="image/svg+xml">Campaign</object>
    <object class="relationshipGraph" id="Course_of_Action" data="{{ site.baseurl }}/img/relationships/Course of Action.svg" type="image/svg+xml">Course of Action</object>
    <object class="relationshipGraph" id="Identify" data="{{ site.baseurl }}/img/relationships/Identify.svg" type="image/svg+xml">Identify</object>
    <object class="relationshipGraph" id="Indicator" data="{{ site.baseurl }}/img/relationships/Indicator.svg" type="image/svg+xml">Indicator</object>
    <object class="relationshipGraph" id="Intrusion_Set" data="{{ site.baseurl }}/img/relationships/Intrusion Set.svg" type="image/svg+xml">Intrusion Set</object>
    <object class="relationshipGraph" id="Malware" data="{{ site.baseurl }}/img/relationships/Malware.svg" type="image/svg+xml">Malware</object>
    <object class="relationshipGraph" id="Observed_Data" data="{{ site.baseurl }}/img/relationships/Observed Data.svg" type="image/svg+xml">Observed Data</object>
    <object class="relationshipGraph" id="Report" data="{{ site.baseurl }}/img/relationships/Report.svg" type="image/svg+xml">Report</object>
    <object class="relationshipGraph" id="Threat_Actor" data="{{ site.baseurl }}/img/relationships/Threat Actor.svg" type="image/svg+xml">Threat Actor</object>
    <object class="relationshipGraph" id="Tool" data="{{ site.baseurl }}/img/relationships/Tool.svg" type="image/svg+xml">Tool</object>
    <object class="relationshipGraph" id="Vulnerability" data="{{ site.baseurl }}/img/relationships/Vulnerability.svg" type="image/svg+xml">Vulnerability</object>
</div>
</div>

## [Graphviz DOT Files]({{ site.baseurl }}/img/relationships/SDO_Relationships_Dot_Files.zip)   ---   [Graphviz PNG Files]({{ site.baseurl }}/img/relationships/SDO_Relationships_PNGs.zip)
