         

    <!--// START: /cog/templates/cog/post/page_template_main.html //-->
<!--// loading page body from page_template_main.html //-->




  	<!-- Data search widget -->
  	

    <div id="cog_post_body">
        <ul>
	<li>
		Correction to sw180, sw17O, prw17O, prw18O and ugrid: <a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/379">#379;</a></li>
	<li>
		Corrected standard names for zmswaero, zmlwaero (<a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/377">#377</a>) and added check;</li>
	<li>
		Correcting time slice specifications for Oclim climatological variables (<a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/376">#376</a>);&nbsp; [IN PROGRESS]</li>
	<li>
		Backward compatible extension to schema: adding new time slice types introduced above (<a href="https://github.com/cmip6dr/schema/issues/2">schema #2</a>);</li>
	<li>
		Amended `starty` for `land-hist` and 13 other experiments to `1700 or 1850` to reflect alternatives specified in experiment protocol (<a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/375">#375</a>);</li>
	<li>
		Removed redundant requestVarGroup records and associated requestLink and objectiveLink records (<a href="https://github.com/cmip6dr/Request/issues/98">#98</a>);</li>
	<li>
		DynVarMIP name corrected (from DynVAR) (<a href="https://github.com/cmip6dr/Request/issues/95">#95</a> and <a href="https://github.com/cmip6dr/Request/issues/94">#94</a>);</li>
	<li>
		Query on <a href="https://github.com/cmip6dr/Request/issues/90">DynVarMIP request (request #90);</a></li>
	<li>
		Metadata omissions in qcranges section corrected (<a href="https://github.com/cmip6dr/Request/issues/99">#99</a>);</li>
	<li>
		Spelling in titles in units section corrected (<a href="https://github.com/cmip6dr/Request/issues/96">#96</a>);</li>
	<li>
		Added missing realm for vegFrac (<a href="https://github.com/cmip6dr/Request/issues/93">#93</a>);</li>
	<li>
		Completed updates of long names to title style specifications: some titles (<a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/380">#380</a>);</li>
	<li>
		vegHeightPasture: cell_methods corrected;</li>
	<li>
		Removed 5 redundant structure records and several redundant units records;</li>
	<li>
		Removed negative values of `ok_min_mean_abs` imported from CMIP5 (<a href="https://github.com/cmip6dr/variableRanges/issues/4">Variable Range #4</a>);</li>
</ul>
<p>
	After beta review:</p>
<ul>
	<li>
		bs550aer corrected to be instantaneous rather than time mean (<a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/386">386</a>);</li>
	<li>
		&quot;bounds&quot; attribute on &quot;olayer100m&quot; dimension corrected to &quot;yes&quot; (<a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/385">385</a>);</li>
	<li>
		Frequency corrected in 6hrLevPt fields mrsos, mrsol, tsl, and soil dimension of mrsol (<a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/384">384</a>);</li>
	<li>
		Deflate, deflate_level and shuffle attributes of CMORvar records set to blank ... these attributes are obsolete (<a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/383">383</a>);</li>
	<li>
		Redundant area type dimension removed for sftof, sftlf (<a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/388">388</a>);</li>
</ul>
<p>
	Review of 01.00.30 beta, listing points of concern to data providers: <a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/387">387</a></p>
<h1>
	Access to the beta version:</h1>
<p>
	<a href="http://proj.badc.rl.ac.uk/svn/exarch/CMIP6dreq/tags/latest">http://proj.badc.rl.ac.uk/svn/exarch/CMIP6dreq/tags/latest (01.00.30beta1) </a></p>
<p>
	Or:</p>
<p>
	<code>pip install -i https://pypi.python.org/pypi [--user]&nbsp; dreqPy==01.00.30beta1</code></p>
<p>
	&nbsp;</p>
    </div> <!--// end div id=cog_post_body //-->

    <!-- include last updated text -->
    <!--// START: /cog/templates/cog/post/_post_last_update.html //-->

    <!--clear:both added to move the last update down if any elements above are floated.-->
    <!--clear:both means no floating elements allowed on either the left or the right side-->
	<div id="last_update_text" style="font-size: 8pt; font-style: italic; text-align:center; clear:both;">
	     Last Update: July 22, 2019, 9:01 a.m. by
         
             <a href="/user/detail/1254/"></a>
         
	</div> <!--// end div id="last_update_text" //-->
