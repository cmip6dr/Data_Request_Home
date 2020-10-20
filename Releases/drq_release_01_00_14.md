         

    <!--// START: /cog/templates/cog/post/page_template_main.html //-->
<!--// loading page body from page_template_main.html //-->




  	<!-- Data search widget -->
  	

    <div id="cog_post_body">
        <ul>
	<li>
		Requested grid in DAMIP: changed &quot;100km&quot; to &quot;1deg&quot;, for consistency.</li>
	<li>
		Spelling correction in standard name of prcsh;</li>
	<li>
		Quality ranges added for slainity variables: so, sos, sossq, soga, sosga: with lower limit of mean absolute value (ok_min_mean_abs) set to 28 to catch two errors which occurred in CMIP5 (1) reporting in units of &quot;1&quot; instead of &quot;0.001&quot; and (2) values to 0 over land;</li>
	<li>
		6 hourly surface albedo removed from HighResMIP request: some ambiguities in definition and not really needed;</li>
	<li>
		Standard names adjusted to approved in OMIP.</li>
	<li>
		Corrected standard name for sistryubot to sea_ice_base_upward_y_stress (to be consistent with&nbsp; sistrxubot);</li>
	<li>
		Added &quot;positive&quot; flags for upwelling/downwelling/upward/downward fluxes (the flag causes CMOR to require information on the sign convention if the input data and apply a sign correction if needed);</li>
	<li>
		Corrected specification for RFMIP selected days, to 1st Jan, April, July, October;</li>
	<li>
		Updated HighResMIP site url to <a href="http://collab.knmi.nl/project/highresmip/">collab.knmi.nl/project/highresmip/</a></li>
</ul>
    </div> <!--// end div id=cog_post_body //-->

    <!-- include last updated text -->
    <!--// START: /cog/templates/cog/post/_post_last_update.html //-->

    <!--clear:both added to move the last update down if any elements above are floated.-->
    <!--clear:both means no floating elements allowed on either the left or the right side-->
	<div id="last_update_text" style="font-size: 8pt; font-style: italic; text-align:center; clear:both;">
	     Last Update: Aug. 3, 2017, 10 a.m. by
         
             <a href="/user/detail/1254/"></a>
         
	</div> <!--// end div id="last_update_text" //-->
