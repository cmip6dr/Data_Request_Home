         

    <!--// START: /cog/templates/cog/post/page_template_main.html //-->
<!--// loading page body from page_template_main.html //-->




  	<!-- Data search widget -->
  	

    <div id="cog_post_body">
        <ul>
	<li>
		cell methods correction from longitude: mean to longitude: sum;</li>
	<li>
		Long names (titles) of CMORvar and var records made consistent where appropriate;</li>
	<li>
		&quot;depth: mean&quot; added to cell methods for <a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/347">thetaot2000, thetaot700, thetaot300 and thetaot, and bounds added to vertical coords;</a></li>
	<li>
		Units &quot;1e-3 kg m-2&quot;, &quot;1e6 J m-1 s-1&quot; and &quot;1e-6 m s-1&quot; replaced with equivalent &quot;g m-2&quot;, &quot;MJ m-1 s-1&quot; and &quot;micron s-1&quot; because the use of a numerical prefix, which is allowed by Udunits and accepted by the CF checker is not strictly CF complient. <a href="http://mailman.cgd.ucar.edu/pipermail/cf-metadata/2018/020650.html">Under discussion: &quot;1e3 km3&quot; and &quot;1e6 km2&quot;. </a></li>
	<li>
		Descriptions shortened (where descriptions copied from standard names result in unwieldy text, greater than 1000 charecters -- see <a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/290">github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/290</a> );</li>
	<li>
		Bug in dreqPy causing exception when no variables found fixed (<a href="https://github.com/cmip6dr/dreqPy/issues/21">dreqPy/issues/21);</a></li>
	<li>
		Bug in dreqPy causing failure to parse argument when run with python3 fixed (<a href="https://github.com/cmip6dr/dreqPy/issues/20">dreqPy/issues/20</a>);</li>
	<li>
		Experiments groups: Meaningful titles added for groups in RFMIP, VolMIP, GeoMIP, GMMIP, HighResMIP, ISMIP6, LS3MIP; 6 redundant records removed.</li>
	<li>
		variable sltnortha removed as redundant (<a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/352">CMIP6_DataRequest_VariableDefinitions/issues/352)</a></li>
</ul>
<h2>
	Addtional modifications in full release:</h2>
<ul>
	<li>
		Capitalisation in variable long names updated (<a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/368">CMIP6_DataRequest_VariableDefinitions/issues/368</a>);</li>
	<li>
		Hyphenation in variable long names updated (<a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/369">CMIP6_DataRequest_VariableDefinitions/issues/369</a>);</li>
</ul>
<p>
	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Capitalisation and hyphenation now follow <a href="https://github.com/cmip6dr/cmip7_forward_look/blob/master/StyleGuideForTitles.md">the new style guide</a>.</p>
<ul>
	<li>
		Snow-on-sea-ice variables: corrected desription of sisnmass (<a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/351">CMIP6_DataRequest_VariableDefinitions/issues/351</a>);</li>
	<li>
		Variable descriptions modified so that they are all less than 1000 characters in length;</li>
	<li>
		Spell check applied to variable titles and descriptions;</li>
	<li>
		dreqPy: improved warning for inconsistent command line options;</li>
	<li>
		dreqPy: corrected a bug in the generation of web pages summarising the data volumes for each MIP;</li>
	<li>
		corrected implementation of google analytics tracking in web pages;</li>
	<li>
		Corrected description of vo from &quot;x-ward&quot; to &quot;y-ward&quot; (<a href="https://github.com/PCMDI/cmip6-cmor-tables/issues/221">cmip6-cmor-tables/issues/221</a>).</li>
	<li>
		Correction to theatot -- to introduce &quot;depth: mean&quot; as intended in beta release.</li>
	<li>
		Basin mean meridional heat fluxes updated to have same cell methods as basin mean meridional mass fluxes, and same guidance on use of zig-zag path for models which have a grid not aligned with latitude. Guidance on zig-zag path corrected to say it is the flux **across** the zig-zag path, not **along** it.</li>
</ul>
<p>
	&nbsp;</p>
    </div> <!--// end div id=cog_post_body //-->

    <!-- include last updated text -->
    <!--// START: /cog/templates/cog/post/_post_last_update.html //-->

    <!--clear:both added to move the last update down if any elements above are floated.-->
    <!--clear:both means no floating elements allowed on either the left or the right side-->
	<div id="last_update_text" style="font-size: 8pt; font-style: italic; text-align:center; clear:both;">
	     Last Update: July 22, 2019, 9 a.m. by
         
             <a href="/user/detail/1254/"></a>
         
	</div> <!--// end div id="last_update_text" //-->
