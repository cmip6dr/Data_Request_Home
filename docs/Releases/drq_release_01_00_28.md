<h1 class="title">Data Request Release 01.00.28</h1>

<div id="cog_post_body">
    <div id="cog_post_body">
        <ul>
	<li>
		CDRMIP request added;</li>
	<li>
		p840 value corrected (&quot;m&quot; --&gt; 84000);</li>
	<li>
		dms long name spelling corrected;</li>
	<li>
		dimension latitude lon name changed to &quot;Latitude&quot; (upper case 1st letter) for consistency with longitude;</li>
	<li>
		lambda550nm dimension bounds attribute changed from &quot;yes&quot; to &quot;&quot; (this dimension should represent a point value fo 550nm, not a range);</li>
	<li>
		debugged the &quot;--txt&quot; option of dreq.py: this functionality was lost in an earlier code rationalisation, now re-introduced;</li>
	<li>
		Variable &quot;ts&quot; renamed to &quot;tsland&quot; when produced on land only.</li>
	<li>
		o3ste (Stratospheric Ozone Tracer) long name and description clarified;</li>
	<li>
		AERmon_oth request variable group, which duplicated AERmon_2d removed (vegHeight added to AERmon_2d to preserve consistency);</li>
	<li>
		Redundant request variable groups removed: AERmon (AERmon_2d and AERmon_3d are used); CFday; CF3hr, DAMIP-Amon-p1, day (replaced by day_ss (2d) and day_oth), ISMIP6-LImon (replaced by ISMIP6-LImon-01), EmonZ, Oyr3dtr, Amon_2d, CFMIP-Omon. This action tidies up the database, it does not remove any variables ... all variables are requested via other groups;</li>
	<li>
		VIACSAB objectives clarified<strong>;</strong></li>
	<li>
		Spurious depth dependent versions of fddtalk, fg14CO2abio, fgco2abio, fgco2nat removed;</li>
	<li>
		Advisory note about use of half levels added for ocean vertical fluxes and velocities;</li>
</ul>
<p>
	Changes after beta release</p>
<ul>
	<li>
		title/long_name of co3sataragos in &quot;var&quot; section corrected.</li>
	<li>
		typo (capital &quot;i&quot; in &quot;ConcetratIon&quot;) corrected in title of co3satarag in &quot;var&quot; section;</li>
	<li>
		misleading standard names for fric, froc, frfe, frn changed to new names introduced in CF Standard Name table version 59, replacing &quot;tendency_of_coean_mole_content_ .... _due_to_sedimentation&quot; with &quot;minus_tendency_of_coean_mole_content_ .... _due_to_sedimentation&quot;, which correctly reflects the sign convention of the sedimentation rate which is the desired diagnostic.</li>
	<li>
		sea ice variables corrected to have cell_measures set to areacello see <a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/252">CMIP6_DataRequest_VariableDefinitions/issues/252</a>;</li>
	<li>
		command line volume estimate changed to allow specification of model source types (e.g. &quot;AOGCM,AER&quot; or &quot;AGCM,BGC&quot;) to allow greater flexibility in volume estimations;</li>
	<li>
		Work on VIACSAB objectives completed;</li>
	<li>
		Realms corrected for several variables in ImonAnt, ImonGre, IyrAnt, IyrGre, see <a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/358">issue 358; </a></li>
	<li>
		Cell methods corrected for snw in 6hrPlevPt: see <a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/355">issue 355; </a></li>
	<li>
		Realm set to atmos for ua100m, va100m, wsgmax10m, wsgmax100m;</li>
	<li>
		Cell methods statements &quot;... where landuse&quot; changed to &quot;... where sector&quot; for consistency with CMOR3 (<a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/348">issue 348</a>);</li>
	<li>
		Redundant variable sltnortha removed (<a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/352">issue 352</a>);</li>
	<li>
		Cell methods for <a href="http://tasminCrop, tasmaxCrop, hursminCrop and prCrop">tasminCrop, tasmaxCrop, hursminCrop and prCrop</a> corrected;</li>
</ul>
<p>
	This version:</p>
<ul>
	<li>
		Install command: sudo pip install dreqPy==1.0.28</li>
	<li>
		Repository:<a href="http://http://proj.badc.rl.ac.uk/svn/exarch/CMIP6dreq/tags/01.00.28/"> </a><a href="http://proj.badc.rl.ac.uk/svn/exarch/CMIP6dreq/tags/01.00.28b1/">http://proj.badc.rl.ac.uk/svn/exarch/CMIP6dreq/tags/01.00.28/</a></li>
</ul>
<p>
	The beta version is available:</p>
<ul>
	<li>
		Install command: sudo pip install dreqPy==1.0.28b1</li>
	<li>
		Repository: <a href="http://proj.badc.rl.ac.uk/svn/exarch/CMIP6dreq/tags/01.00.28b1/">http://proj.badc.rl.ac.uk/svn/exarch/CMIP6dreq/tags/01.00.28b1/</a></li>
</ul>
</div> <!--// end div id=cog_post_body //-->
