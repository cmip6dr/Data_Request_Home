         

    <!--// START: /cog/templates/cog/post/page_template_main.html //-->
<!--// loading page body from page_template_main.html //-->




  	<!-- Data search widget -->
  	

    <div id="cog_post_body">
        <ul>
	<li>
		Redundant variables zoomeso, zoomicro and zoomisc purged from CMORvar records;</li>
	<li>
		redundant dimensions &quot;location&quot; and &quot;icesheet&quot; removed;</li>
	<li>
		rlut: spelling correction in some long names corrected (missing &quot;n&quot; at end of &quot;Radiation&quot;);</li>
	<li>
		Values for siline dimension corrected to CF Convention syntax (lower case, underscore instead of space, as in fram_strait);</li>
	<li>
		nwdFracLut units changed to percentage, for consistency with other area fractions;</li>
	<li>
		Corrected CMOR variable &quot;type&quot; values: &quot;float&quot;--&gt; &quot;real&quot; and &quot;&quot; (empty) --&gt; real;</li>
	<li>
		Corrected non-dimensional units: &quot;1.0&quot; --&gt; &quot;1&quot;;</li>
	<li>
		snm, snmIs: comment corrected to read &quot;report as missing where land fraction is 0&quot;, for consistency with other masked variables.</li>
	<li>
		tsnl: corrected to be the temperature of layers in the snowpack.</li>
	<li>
		tsland: introduced in Eday to distinguish variable requested by LS3MIP (masked by land) from othe requests for unmasked version;</li>
	<li>
		tsl: definition updated to clarify that 6-hourly version requested by HighResMIP is only on one near-surface layer, daily and monthly versions of the variable are on all soil levels.</li>
	<li>
		mrsofc: long name modified to make clear that this is Field Capacity;</li>
	<li>
		OMIP variables: standard names corrected: hfbasinpmadv, hfbasinpmdiff, hfbasinpsmadv, msftmrhompa, msftmzmpa, msftmzsmpa, msftyrhompa, msftyzmpa, ocontempdiff, ocontemppmdiff, ocontemppsmadvect, opottempdiff, opottemppmdiff, opottemppsmadvect, osaltdiff, osaltpmdiff, osaltpsmadvect;</li>
	<li>
		cSoilLevels: standard name corrected and dimension for soil levels added;</li>
	<li>
		rsucsbnd, rsdcsbnd: standard name corrected.</li>
	<li>
		fAnthDisturb: Long name clarified .. to &quot;Carbon Mass Flux from Vegetation, Litter or Soil Pools into the Atmosphere due to Any Human Activity&quot;;</li>
	<li>
		&quot;positive&quot; attribute dropped: gpp*, fco2antt, fco2fos, evs*, fHarvestToProduct, rsdoabsorb;</li>
	<li>
		&quot;positive&quot; attribute added: &quot;up&quot;: rsucsaf, rsucsafbnd, rsucsbnd, fN2O, fNOx,&nbsp; fLulccAtmLut; &quot;down&quot;: siflcondtop, siflcondbot, expfe;</li>
	<li>
		phyfeos: long name corrected: Surface Mole Concentration of Total Phytoplankton expressed as Iron in Sea Water;</li>
	<li>
		redundant OMIP variables pdi, ppdiaz, ppcalc, and pppico removed;</li>
	<li>
		OMIP: standardisation of capitalisation in long names: &quot;sea water&quot; --&gt; &quot;Sea Water&quot; etc.</li>
	<li>
		solbnd: standard name corrected to solar_irradiance.</li>
</ul>
    </div> <!--// end div id=cog_post_body //-->

    <!-- include last updated text -->
    <!--// START: /cog/templates/cog/post/_post_last_update.html //-->

    <!--clear:both added to move the last update down if any elements above are floated.-->
    <!--clear:both means no floating elements allowed on either the left or the right side-->
	<div id="last_update_text" style="font-size: 8pt; font-style: italic; text-align:center; clear:both;">
	     Last Update: March 1, 2018, 9:36 a.m. by
         
             <a href="/user/detail/1254/"></a>
         
	</div> <!--// end div id="last_update_text" //-->
