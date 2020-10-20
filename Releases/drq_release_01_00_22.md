<h1 class="title">Data Request Release 01.00.22</h1>

<div id="cog_post_body">
    <div id="cog_post_body">
        <ul>
	<li>
		tomint: dropped from the request;</li>
	<li>
		cSoilAbove1m, : coordinates added to specify the soil layer;</li>
	<li>
		cSoilBelow1m: removed as redundant (difference between cSoil and cSoilAbove1m);</li>
	<li>
		solbnd: modify standard name to toa_incoming_shortwave_flux (following discussion on CF list);</li>
	<li>
		vegtype: clarify description of this dimension</li>
	<li>
		empty variable descriptions (e.g. ares) filled with standard name descriptions;</li>
	<li>
		cell methods for tSoilPools, cSoilPools corrected to time mean;</li>
	<li>
		tsnl&nbsp; (Eday) --&gt; tsn: snowdepth dimension was re-introduced in 01.00.21 by mistake: removed and name changed to tsn for consistency with monthly snow temperature variable;</li>
	<li>
		pfull.6hrLev changed from time mean to instantaneous;</li>
	<li>
		ISMIP6 requests for data from lig127k and ssp585 corrected.</li>
	<li>
		Priorities corrected for DAMIP request for hfcorr, wfcorr, zfullo, zhalfo (to &quot;1&quot;);</li>
	<li>
		Added DCPP request for ssp245 data;</li>
	<li>
		remove variables droppped by OMIP: omldamax, pbfe (Omon), pbsi (Omon), pnitrate (Omon)</li>
	<li>
		cell_measures corrected to areacello for: Eday/mlotst, t20d; 3hr/tos; Emon/thetaot700, thetaot2000 thetaot300;</li>
	<li>
		jpdftaureliqmodis and jpdftaureicemodis dimensions corrected (removing plev7c) to longitude latitude effectRadLi/Ic tau time;</li>
	<li>
		sdepth1, sdepth10 `valid_max` values adjusted to 0.1m and 1m respectively;</li>
	<li>
		dimensions typewetla and scatratio: declarations corrected (see <a href="https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions/issues/305">Github issue 305, points 4 &amp; 5 );</a></li>
	<li>
		lambda550nm coordinate added for aerosol optical depth variables;</li>
	<li>
		standard names corrected for 16 variables.</li>
</ul>
</div> <!--// end div id=cog_post_body //-->
