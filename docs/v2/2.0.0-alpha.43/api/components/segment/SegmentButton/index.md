---
layout: "v2_fluid/docs_base"
version: "2.0.0-alpha.43"
versionHref: "/docs/v2/2.0.0-alpha.43"
path: ""
category: api
id: "segmentbutton"
title: "SegmentButton"
header_sub_title: "Class in module "
doc: "SegmentButton"
docType: "class"
show_preview_device: true
preview_device_url: "/docs/v2/demos/segment/"
angular_controller: APIDemoCtrl 
---




<div class="improve-docs">
<a href='http://github.com/driftyco/ionic2/tree/master/ionic/components/segment/segment.ts#L131'>
View Source
</a>
&nbsp;
<a href='http://github.com/driftyco/ionic2/edit/master/ionic/components/segment/segment.ts#L131'>
Improve this doc
</a>
</div>





<h1 class="api-title">


SegmentButton






</h1>






<p>The child buttons of the <code>ion-segment</code> component. Each <code>ion-segment-button</code> must have a value.</p>


<h2>Directive</h2>
<h3>selector: <code>ion-segment-button</code></h3>
<!-- @usage tag -->

<h2>Usage</h2>

<pre><code class="lang-html">&lt;ion-segment [(ngModel)]=&quot;relationship&quot; primary&gt;
  &lt;ion-segment-button value=&quot;friends&quot; (click)=&quot;clickedFriends()&quot;&gt;
    Friends
  &lt;/ion-segment-button&gt;
  &lt;ion-segment-button value=&quot;enemies&quot; (click)=&quot;clickedEnemies()&quot;&gt;
    Enemies
  &lt;/ion-segment-button&gt;
&lt;/ion-segment&gt;
</code></pre>
<p>Or with <code>FormBuilder</code></p>
<pre><code class="lang-html">&lt;form [ngFormModel]=&quot;myForm&quot;&gt;
  &lt;ion-segment ngControl=&quot;mapStyle&quot; danger&gt;
    &lt;ion-segment-button value=&quot;standard&quot;&gt;
      Standard
    &lt;/ion-segment-button&gt;
    &lt;ion-segment-button value=&quot;hybrid&quot;&gt;
      Hybrid
    &lt;/ion-segment-button&gt;
    &lt;ion-segment-button value=&quot;sat&quot;&gt;
      Satellite
    &lt;/ion-segment-button&gt;
  &lt;/ion-segment&gt;
&lt;/form&gt;
</code></pre>




<!-- @property tags -->

<h2>Attributes:</h2>
<table class="table" style="margin:0;">
<thead>
<tr>
<th>Attribute</th>












<th>Type</th>


<th>Description</th>
</tr>
</thead>
<tbody>

<tr>
<td>
value
</td>


<td>
string
</td>


<td>
the value of the segment-button.
</td>
</tr>

<tr>
<td>
click
</td>


<td>
Any
</td>


<td>
expression to evaluate when a segment button has been clicked
</td>
</tr>

</tbody>
</table>


<!-- methods on the class --><!-- related link -->

<h2>Related</h2>

<a href='/docs/v2/components#segment'>Segment Component Docs</a>
<a href='/docs/v2/api/components/segment/Segment/'>Segment API Docs</a><!-- end content block -->


<!-- end body block -->

