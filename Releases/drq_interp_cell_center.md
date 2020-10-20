<h1 class="title">Data Request: interpolation to cell centers</h1>

<div id="cog_post_body">
    <div id="cog_post_body">
        <p>
	In general, data variables should be provided at the center of the numerical mesh. There are a few exceptions which are requested on exactly the locations used in the numerical model (e.g. cell vertices or cell sides). When data is requested at the cell center it will have a cell_measures attribute value specified in the data request.</p>
<p>
	The exceptions are:</p>
<h3>
	Optional cell center, vertex or edge</h3>
<p>
	6hrLev: ua, va: this variables are to be used for driving regional models and may either be provided at cell centres or stored as used in the model. The choice is with the data provider. These variables have the cell_measures attribute in the CMORvar record of the data request set to &quot;--OPT&quot;. This value should be treated as a directive, the cell_measures attribute of the variable in the NetCDF file should not be set.</p>
<p>
	Omon: uo, vo, umo, vmo, hfx, hfy, tauuo, tauucorr, tauvo, tauvcorr</p>
<h3>
	Provide as used in model</h3>
<p>
	SIday: siu, siv:</p>
<p>
	SImon: sidmasstranx, sidmasstrany, siforcecoriolx, siforcecorioly, siforcetiltx, siforcetilty, siforceintstrx, siforceintstry, sistrxdtop, sistrydtop, sistrxdbot, sistrydbot, siu, siv.</p>
<p>
	These variables should be provided on the locations used in the models (e.g. cell vertices or edges) to ensure that horizontal fluxes cab be calculated reasonably accurately. These variables have the cell_measures attribute in the CMORvar record of the data request set to &quot;--MODEL&quot;. This value should be treated as a directive, the cell_measures attribute of the variable in the NetCDF file should not be set.</p>
<h2>
	Changes from CMIP5</h2>
<p>
	The variables ua, va in the <strong>day</strong> table where specified with no cell_measures, but in CMIP6 they will be requested on grid centres. In the CMIP5 archive these variables have been archived by all groups on the cell centres.</p>
<h2>
	Comment.</h2>
<p>
	For the 6hrLev fields ua, va, it appears that most groups submitting data to CMIP5 interpolated these to cell centres, which was not required (e.g. MOHC, HadGEM2-ES data has the 6hrLev fields on different grid locations, but IPSL models have them on the cell centres despite running the model with an Arakawa C grid).</p>
</div> <!--// end div id=cog_post_body //-->
