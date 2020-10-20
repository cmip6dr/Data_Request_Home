<h1 class="title">Release 01.00.27</h1>

<div id="cog_post_body">
    <div id="cog_post_body">
        <p>
	Changes introduced in 01.00.27beta01:</p>
<ul>
	<li>
		Split land-future experiment into land-ssp434 and land-ssp585 (3 ensemble members each);</li>
	<li>
		Adding a core request of variables for general intercomparison to all experiments, with a slightly extended set for ScenarioMIP experiments. This is a minor addition designed to ensure that there are no unintended gaps in the variables requested (as part of the CMIP request);</li>
	<li>
		Corrections to ocean biogeochemical tracers which are requested as monthly surface fields with a lower priority option of providing them on all model levels. Requests from VIACSAB, the DCPP-mon group, and the CMIP general intercomparison set are restricted to surface variables; request from C4MIP and DAMIP are specifically for the model level versions. Otherwise, requests follow OMIP in specifying both.</li>
	<li>
		ScenarioMIP3 experiment group record removed; request items linking to it either removed or redirected to ScenarioMIP2;</li>
	<li>
		GeoMIP request for data from ssp460 added;</li>
	<li>
		dmlt: added soil_temperature dimension stempzero and cell methods string, as required by new standard name (depth_at_shallowest_isotherm_defined_by_soil_temperature).</li>
	<li>
		reference to &quot;grid_latitude&quot; in spatial shape records &quot;GYB-R&quot; and &quot;GYB-O&quot;&nbsp; corrected to &quot;gridlatitude&quot;;</li>
</ul>
<p>
	Additional changes in full release:</p>
<ul>
	<li>
		Title of structure records for MODIS size distributions corrected;</li>
	<li>
		Removed Odec request items for all experiments except piControl-spinup and esm-piControl-spinup;</li>
	<li>
		corrections to implementation of addition of core request;</li>
	<li>
		ppos added, and Omon.pp changed to 3d variable;</li>
	<li>
		corrections to the extensions/collect module: removed a bug affecting the _get__expt() method of requestLink items;</li>
	<li>
		added a extensions/versions module to improve support for handling multiple document versions -- see dreqPy.pdf for more information;</li>
	<li>
		improved spreadsheets provided on web site: the &quot;cmvme_&lt;mip&gt;_&lt;expt&gt;_&lt;tier&gt;_&lt;priority&gt;&quot; tables have a priority in column one: previously this was the CMOR variable default priority, which caused some confusion. Now changed to be the priority set by the requesting MIP for that experiment.</li>
	<li>
		Additional standard name corrections. Only two variables now lack valid standard names: sw2H and sndmasssubl.</li>
	<li>
		simpmass: following long discussion, this&nbsp; variable has been assigned a standard name sea_ice_melt_pond_thickness, with units of &quot;m&quot;, a change from the previous units of &quot;kg m-2&quot; -- the long name has been changed to &quot;Meltpond Mass per Unit Area (as Depth)&quot;;</li>
</ul>
<p>
	The beta release prior to this full release is available from:</p>
<ul>
	<li>
		SVN: svn co <a href="http://proj.badc.rl.ac.uk/svn/exarch/CMIP6dreq/tags/01.00.27b1">http://proj.badc.rl.ac.uk/svn/exarch/CMIP6dreq/tags/01.00.27b1</a></li>
	<li>
		Python repository: <code>pip install -i https://pypi.python.org/pypi [--user]&nbsp; dreqPy==01.00.27b1</code></li>
	<li>
		<code>Web site: <a href="http://clipc-services.ceda.ac.uk/dreq/beta/">http://clipc-services.ceda.ac.uk/dreq/beta/</a></code></li>
</ul>
<p>
	&nbsp;</p>
</div> <!--// end div id=cog_post_body //-->
