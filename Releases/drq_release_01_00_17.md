         

    <!--// START: /cog/templates/cog/post/page_template_main.html //-->
<!--// loading page body from page_template_main.html //-->




  	<!-- Data search widget -->
  	

    <div id="cog_post_body">
        <ul>
	<li>
		co2totalmass removed: duplicated co2mass;</li>
	<li>
		lwtoacs name changed to lwtoacsdust and long name changed to &quot;Clear Sky Longwave radiative Forcing due to Dust at TOA&quot; for consistency with other TOA longwave variables;</li>
	<li>
		ua200, ua850, va200, va850 (requested by PMIP) removed;</li>
	<li>
		New search page for experiments added:<a href="http://clipc-services.ceda.ac.uk/dreq/experiments.html"> Experiment Search</a></li>
	<li>
		Cell areas: &quot;areacelli&quot; name changes to &quot;modelCellAreai&quot;, to emphasise that this variable is defined to capture the areas of the model ice sheet grid, not the grid used to report the data. The long names and decriptions of areacella, areacello, areacellr, areacellg have been modified to make it clear that, for interpolated data these refer to the properties of the grid they are reported on, not the model grid. The cell methods attributes have been changed from &quot;area: mean&quot; to &quot;area: sum&quot;.&nbsp;</li>
	<li>
		siconc, siconco -&gt; siconca, siconc: there has been some confusion around the Sea Ice Concentration variables since the introduction of siconco in version 01.00.10. In the release notes &quot;siconco&quot; is defined clearly as being on the ocean grid, but the metadata in the request itself implied that it should be on the atmospheric grid. To resolve this with minimal disruption we now have siconca for the atrmospheric grid, and siconc for the ocean grid;</li>
	<li>
		sidivvel, sihevel, sistremax, sistresave, simpmass, simprefrozen: changed from cell measures areacella to areacello;</li>
	<li>
		ice variable cell measures in the request for most sea ice variables changed to &quot;areacello OR areacella&quot;, and the comment in the cell methods string to &quot;siconc or siconca&quot;.</li>
	<li>
		Updated documentation (<a href="http://proj.badc.rl.ac.uk/svn/exarch/CMIP6dreq/tags/01.00.18/dreqPy/docs/dreqPy.pdf">dreqPy.pdf</a> and <a href="http://proj.badc.rl.ac.uk/svn/exarch/CMIP6dreq/tags/01.00.18/dreqPy/docs/dreqML.pdf">dreqML.pdf</a>)</li>
</ul>
    </div> <!--// end div id=cog_post_body //-->

    <!-- include last updated text -->
    <!--// START: /cog/templates/cog/post/_post_last_update.html //-->

    <!--clear:both added to move the last update down if any elements above are floated.-->
    <!--clear:both means no floating elements allowed on either the left or the right side-->
	<div id="last_update_text" style="font-size: 8pt; font-style: italic; text-align:center; clear:both;">
	     Last Update: Dec. 23, 2017, 7:26 a.m. by
         
             <a href="/user/detail/1254/"></a>
         
	</div> <!--// end div id="last_update_text" //-->
