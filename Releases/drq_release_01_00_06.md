<h1 class="title">Data Request Release 01.00.06</h1>

<div id="cog_post_body">
    <div id="cog_post_body">
        <p>
	Corrected standard name for hfdsl (surface downward heat flux over land)</p>
<p>
	LS3MIP: sic, sit --&gt; siconc, sithick (as for SIMIP)</p>
<p>
	DCPP daily data: broken link fixed</p>
<p>
	Changed cell_methods for siitdthick, siitdsnthick, siitdsnconc, simpmass, simprefrozen, sirdgthick: to reflect the definitions more accurately .. the first three are defined with respect to sea ice thickness bands, and weitghted by the area in each band, so &quot;mask=siitdconc&quot; is added to the comment section of the cell_methods string. simpmass and simprefrozen are wieghted by melt pond area, and sirdgthick by sea ice ridge area.</p>
<p>
	Fixed broken links in HighResMIP and PMIP requests</p>
<p>
	Removed cpocean, rhozero and equations of state removed from data request, as they will be collected in the ES-DOC model documentation;</p>
<p>
	Corrected frequency to &quot;monClim&quot; for climatological fields in Amon;</p>
<p>
	Added monthly global orography variable, for use when ice sheet has time varying orography;</p>
<p>
	FIxed a number of broken links in request variables.</p>
<p>
	Corrected units of &quot;spectband&quot; axis used by RFMIP to &quot;m-1&quot; (wavenumber).</p>
<p>
	&nbsp;</p>
<p>
	&nbsp;</p>
</div> <!--// end div id=cog_post_body //-->
