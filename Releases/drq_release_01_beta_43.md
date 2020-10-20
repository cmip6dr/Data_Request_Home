<h1 class="title">Release 01.beta.43</h1>

<div id="cog_post_body">
    <div id="cog_post_body">
        <p>
	Added in the &quot;CMIP Request&quot;: this is a core set of variables, requested from the DECK and CMIP6 historical simulations. The &quot;CMIP&quot; requested variables should be provided for all models. This does not include any new variables (except for thos being introduced into the Omon and Oyr tables by OMIP);</p>
<p>
	Corrected clisccp assigment to cfDay_3d (was getting assigned to cfDay_2d, inflating request volume). (editted in util_anal.py, util_gen.py);</p>
<p>
	Adjusted LS3MIP requirements for 3-hourly data from the historical simulation: reduced to 35 years;</p>
<p>
	Updates ISMIP6, DAMIP, OMIP (physical oceanography) requests. Further updates from the OMIP bio-geochemistry and chemistry variables will be implemented soon;</p>
<p>
	Fixed a number of bugs raised on https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions;</p>
<p>
	Added time period of requested data to spreadsheets of variables requested for individual experiments (3 additional columns to the right);</p>
<p>
	Added a feature to the python API to provide variable sheets sorted by frequency and realm, rather than by table:</p>
<p>
	drq -m &lt;mip1&gt;[,&lt;mip2]&nbsp; --sf --xfr</p>
</div> <!--// end div id=cog_post_body //-->
