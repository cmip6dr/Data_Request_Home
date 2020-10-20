<h1 class="title">Data Request Release 01.00.07</h1>

<div id="cog_post_body">
    <div id="cog_post_body">
        <ul>
	<li>
		Corrected dimensions strings for CFMIP joint pdf variables</li>
	<li>
		Corrected &quot;ok_min_mean_abs&quot; value in quality control ranges section: this was being provided with the data value for &quot;ok_max_mean_abs&quot;.</li>
	<li>
		LUMIP fields changed to be &quot;area: mean where land&quot;, for consistency with C4MIP and Lmon.</li>
	<li>
		Area fractions for land: the cell methods string changed to &quot;area: mean where land over all_area_types&quot;, to be consistent with the definition of these variables as representing a proportion of the whole grid cell area (includes changes to CMIP5 Lmon variables, to bring the cell methods string into line with the variable definition);</li>
	<li>
		C4MIP area fractions: complete set of coordinates implemented;</li>
	<li>
		Masked means for C4MIP and LUMIP: cell_methods strings set to appropriate values.</li>
	<li>
		Clean air radiative fluxes: redundancy in requests from AerChemMIP, GeoMIP and RFMIP resolved. rsutna --&gt; rsutaf (TOA Outgoing Aerosol-Free Shortwave Radiation), rsutcc, rsutnacs --&gt; rsutcsaf (TOA Outgoing Clear-Sky, Aerosol-Free Shortwave Radiation);</li>
	<li>
		Fixed javascript bug in http://clipc-services.ceda.ac.uk/dreq/mipVars.html filter .. filter on variable names included matches on uid;</li>
	<li>
		Added a ugrido variable to carry UGRID standard information for models with unstructured grids (expected to occur in one or two CMIP6 models .. can be ignored by the others);</li>
</ul>
</div> <!--// end div id=cog_post_body //-->
