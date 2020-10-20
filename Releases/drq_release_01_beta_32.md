<h1 class="title">Data Request Release 01.beta.32</h1>

<div id="cog_post_body">
    <div id="cog_post_body">
        <h2>
	Content</h2>
<h3>
	By MIP</h3>
<p>
	* SIMIP: added ice-sheet cell area (areacelli); added fixed variables on polar grids (2 of these optionally annual, depending on model implementation); option set added to highlight choice of fixed vs. time varying fields for lithk and topg. Sub-selection of CMIP5 variables fixed.</p>
<p>
	* VIACSAB: a small number of additional variable requests added (no new variables).</p>
<h3>
	Variables</h3>
<p>
	* sistryubot, sistrxubot (SIMIP): changed to upwards stresses, to use existing standard names.</p>
<p>
	* tsice --&gt; sitemptop in DCPP, PMIP, CFMIP request, for consistency with SIMIP.</p>
<h3>
	Dimensions</h3>
<ul>
	<li>
		Added p200, p850: used in the coordinate attributes.</li>
</ul>
<h3>
	Schema</h3>
<ul>
	<li>
		Added links for referenced to dimensions, so that it is possible to navigate easily from dimensions to vaiables that use them.</li>
	<li>
		Added a cell methods table which will facilitate checking of correct cell methods specifications.</li>
</ul>
<p>
	&nbsp;</p>
<h2>
	Outstanding Issues</h2>
<ul>
	<li>
		Standard names: around 600 new CF Standard Names are required;</li>
	<li>
		Block copies of variable lists have been implemented for Omon, but not yet for PMIP;</li>
	<li>
		Removal of duplicate CMOR Variables -- there is some duplication between new and old tables;</li>
	<li>
		Missing or ambiguous objectives assigned to data requests;</li>
</ul>
<p>
	&nbsp;</p>
</div> <!--// end div id=cog_post_body //-->
