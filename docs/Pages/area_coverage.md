<h1 class="title">Percentage Area Coverage (Area Fractions) and Area Types</h1>

<div id="cog_post_body">
    <div id="cog_post_body">
        <p>
	There are a substantial number of variables which denote the percentage of an area covered by a particular area type. E.g. Sea Ice Concentration (siconc) or grassFracC3 (percentage cover of C3 functional type grasses). Area coverage will always be represented as a percentage.</p>
<h2>
	Fully conformant coverage fields</h2>
<p>
	When the area is designated by a term in the CF Area Type table (<a href="http://cfconventions.org/Data/area-type-table/6/build/area-type-table.html">cfconventions.org/Data/area-type-table/6/build/area-type-table.html</a>), the data can be fully described using explicit CF metadata attributes. That is, the variable `standard_name` attribute is set to `area_fraction` and the `coordinates` attribute contains the name of one or more character variables carrying the Area Type term. These variables have standard name area_type and a value from the area type table.</p>
<p>
	The coverage may be expressed as a percentage of the whole grid cell or as a percentage of a broader category of area type. For instance the sea ice melt pond coverage is expressed as a percentage of the sea ice area. This is represented in the metadata by including &quot;area: mean where sea_ice (comment: mask=siconc)&quot; in the cell methods string.</p>
<p>
	When the area type is only defined on a portion of the grid cell and the result is requested as a fraction of the whole grid cell, the following formulation will be used: &quot;area: mean where land over all_area_types&quot;. This approach is used for land surface diagnostics such as treeFrac, the percentage of a grid cell covered by trees.</p>
<h2>
	Non-conformant coverage fields</h2>
<p>
	When an area is designated by terms which are not in the CF Area Type table, the standard name area_fraction is still used, with a coordinates attribute, but the coordinate variable does not carry a standard name. The &quot;landCoverFraction&quot; variable is one example, as in CMIP5 (in CMIP5, the &quot;vegtype&quot; axis did carry the standard name area_type, but it did not conform to the requirement of having values from the CF Area Type list). Similarly, the &quot;typewetland&quot; coordinate does not carry a standard name.</p>
<p>
	For 4 sub-categorries of tree, narrowleaf deciduous, broadleaf deciduous, narrowleaf evergreen and broadleaf evergreen, the same area_type of &quot;trees&quot; is used, with different long names for the variables to indicate the differences.</p>
<h2>
	Area Types in Cell Methods</h2>
<p>
	There has been much discussion about area type classifications used in the cell methods string. In the CF convention these give qualitative information about the type of area. In CMIP6 there may be an associated masking variable (e.g. one variable giving the surface temperature of sea ice, and a masking variable indicating where sea ice is present). In the CF convention there is no mechanism for explictly identifying the masking variable relevant to an area type classification. For CMIP6, a clue is provided in a cell methods comment string.</p>
<h2>
	Land and Sea</h2>
<p>
	Land and sea area types have been used in many generations of CMIP, but there is a change in CMIP6: for the first time some of the CMIP climate models will explicitly resolve the ocean under floating ice shelves and the temporal evolution of floating ice shelves. Prior to CMIP6 ice shelves could be treated as equivalent to solid land. For many variables, such as surface radiation terms or snow depth, the distinction between floating ice shelve and grounded ice sheet is irrelevant, and it appears to be common practise to handle such variables in the &quot;land&quot; module of the climate models. Hence the &quot;land&quot; area type is considered to include floating ice shelves when applied to surface fields.</p>
<p>
	The sea area type excludes ice shelves when applied to a surface field, but may extend under the ice shelve when applied to variables within the ocean.</p>
<h2>
	&nbsp;</h2>
<p>
	&nbsp;</p>
<p>
	&nbsp;</p>
</div> <!--// end div id=cog_post_body //-->
