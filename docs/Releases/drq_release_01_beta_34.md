<h1 class="title">Data Request Release 01.beta.34</h1>

<div id="cog_post_body">
    <div id="cog_post_body">
        <p>
	Replaced by 01.beta.35, September 19th.</p>
<h2>
	Content</h2>
<h3>
	By MIP</h3>
<p>
	* SIMIP: cell methods for weighted time mean over snow area on sea ice corrected (affects sisnthick and sisnhc). <font size="2"><span style="font-size:10pt;">For example, if there is a 1m snow layer over 50% of a grid cell for half the month and 3m over 25% for the 2nd half of the month (the rest of the cell being snow free), the weighted time mean of 1.6667m is wanted, not a simple mean of 2m.</span></font></p>
<p>
	<font size="2"><span style="font-size:10pt;">* CFMIP: ISCCP variables, cell_methods changed to specify weighted time mean, consistent with variable definition.</span></font></p>
<h2>
	<font size="2"><span style="font-size:10pt;">General</span></font></h2>
<p>
	<font size="2"><span style="font-size:10pt;">* Duplication reduced in *structure* records by ensuring that cell_measures and cell_methods are used consistently.&nbsp; </span></font></p>
<p>
	<font size="2"><span style="font-size:10pt;">* Re-worked the ingestion software, removing conflicts which created broken links in the database </span></font></p>
<h2>
	Package</h2>
<p>
	* Imports cleared up to enable python3 support.</p>
<p>
	* Cleaned up version communication in the package (the module dreq carries the software version, instances if the loadDreq class carry the version of the XML document used to initialise them) so that the package can be used to compare different request document versions.</p>
<p>
	* Issues with installation fixed for python 2, some problems persist for python 3</p>
<h2>
	Web site</h2>
<p>
	An annotation feature has been added to the variable pages (e.g. http://clipc-services.ceda.ac.uk/dreq/u/51e0588121783d77407236e0d2eb5d14.html ), using the CHARMe package. This is still in a trial phase ... it may be useful, but some work is needed on the moderation workflow.</p>
<p>
	A restful pre-fill option has been added to the variable index at http://clipc-services.ceda.ac.uk/dreq/mipVars.html , e.g http://clipc-services.ceda.ac.uk/dreq/mipVars.html?variable=tas will palce &quot;tas&quot; in the variable search box. This only works for the variable search box.</p>
<p>
	Unfortunately, http://clipc-services.ceda.ac.uk/dreq/mipVars.html is no longer working in IE.</p>
<p>
	&nbsp;</p>
<p>
	&nbsp;</p>
<p>
	&nbsp;</p>
</div> <!--// end div id=cog_post_body //-->
