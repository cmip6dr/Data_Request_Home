         

    <!--// START: /cog/templates/cog/post/page_template_main.html //-->
<!--// loading page body from page_template_main.html //-->




  	<!-- Data search widget -->
  	

    <div id="cog_post_body">
        <h2>
	Content</h2>
<h3>
	By MIP</h3>
<ul>
	<li>
		ISMIP6: Variables renamed, clarified requests for ice-sheet data on polar stereographic grids. Intial specifications of polar stereographic grids added.</li>
	<li>
		DynVar: Daily zonal mean variables corrected to be on 39 pressure levels (same as monthly zonal mean variables)</li>
	<li>
		VolMIP: experiment information updated</li>
</ul>
<h3>
	Variables</h3>
<ul>
	<li>
		sftgif: In CMIP5 this variable had a long name &quot;Fraction of grid cell occupied by glaciers.&quot; and a standard name land_ice_area_fraction. The long name has been changed to be consistent with the standard name, replacing &quot;glaciers&quot; with &quot;land ice (ice sheet, ice shelf, ice cap, glacier)&quot;. [&quot;Fraction&quot; has also been replaced with &quot;Percentage&quot; for consistency with units]</li>
</ul>
<h3>
	Dimensions</h3>
<ul>
	<li>
		coordinates added for polar stereographic grids. ISMIP6 is requesting data on polar stereographic grids.</li>
</ul>
<h3>
	Technical</h3>
<ul>
	<li>
		adjusted workflow to keep UIDs of CMORvar records fixed between updates.</li>
	<li>
		cell_methods: updated specification for weighted time means to match http://cf-trac.llnl.gov/trac/ticket/152 (weghted time mean example).</li>
</ul>
    </div> <!--// end div id=cog_post_body //-->

    <!-- include last updated text -->
    <!--// START: /cog/templates/cog/post/_post_last_update.html //-->

    <!--clear:both added to move the last update down if any elements above are floated.-->
    <!--clear:both means no floating elements allowed on either the left or the right side-->
	<div id="last_update_text" style="font-size: 8pt; font-style: italic; text-align:center; clear:both;">
	     Last Update: Aug. 1, 2016, 10:16 a.m. by
         
             <a href="/user/detail/1254/"></a>
         
	</div> <!--// end div id="last_update_text" //-->
