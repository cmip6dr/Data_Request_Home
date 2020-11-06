<h1 class="title">Time and Masked Area Averages in the Data Request -- use of Cell Methods.</h1>

<div id="cog_post_body">
    <div id="cog_post_body">
        <h1>
	Time Means</h1>
<p>
	Many variables in CMIP6 are defined as masked means, defined as the mean of a quantity over a portion of the grid cell defined by an area type.</p>
<table border="1" cellpadding="1" cellspacing="1" style="width: 500px;" summary="*: proposed for inclusion .. not yet in the CF table of area types">
	<caption>
		Area Types used for Masked Means</caption>
	<tbody>
		<tr>
			<td>
				&nbsp;</td>
			<td>
				&nbsp;</td>
		</tr>
		<tr>
			<td>
				land</td>
			<td>
				Land is defined to include ice shelves, both grounded and floating. For a minority of CMIP6 models this means that the land mask can evolve with time as floating ice shelves move. For most models, however, the land mask will be fixed.</td>
		</tr>
		<tr>
			<td>
				sea</td>
			<td>
				Sea refers to all areas of the ocean.</td>
		</tr>
		<tr>
			<td>
				ice_free_sea</td>
			<td>
				Sea areas with no sea ice or ice shelves.</td>
		</tr>
		<tr>
			<td>
				sea_ice</td>
			<td>
				Sea ice is floating ice, excluding ice shelves.</td>
		</tr>
		<tr>
			<td>
				land_ice</td>
			<td>
				Land ice includes glaciers, ice caps, ice sheets and ice shelves.</td>
		</tr>
		<tr>
			<td>
				ice_free_sea</td>
			<td>
				Sea area with no sea ice or floating ice shelves.</td>
		</tr>
		<tr>
			<td>
				cloud</td>
			<td>
				Area where there is cloud</td>
		</tr>
		<tr>
			<td>
				floating_ice_shelf*</td>
			<td>
				&nbsp;</td>
		</tr>
		<tr>
			<td>
				grounded_ice_shelf*</td>
			<td>
				&nbsp;</td>
		</tr>
		<tr>
			<td>
				snow_covered_sea_ice*</td>
			<td>
				&nbsp;</td>
		</tr>
	</tbody>
</table>
<h1>
	Temporal means</h1>
<p>
	These area types are used in the following constructions:</p>
<h2>
	Area weighted mean:</h2>
<pre>
area: time: mean where &lt;area_type&gt;</pre>
<p>
	For time invariant area types, this is equivalent to &quot;area: mean where &lt;area_type&gt; time: mean&quot;. This mean gives equal weight to every square metre occupied by the declared area type. It will typically be calculated by first evaluating a masked area mean at each time step, and then calculating a mean of the time series weighted by the masked area at each time step. A spatial map will show values characteristic of the area type, with undefined values where the area type does not exist.</p>
<p>
	A comment field is added to indicate the area fraction field which is associated with the same area type, e.g. &quot;area: time: mean where trees (comment: mask=treeFrac)&quot;. This construction is used for vegetation, shrubs, natural_grasses, trees, sea_ice, sea_ice_melt_pond. For sea_ice, there are two different mask, siconc and siitdconc: the second specifying area fraction in ice thickness categories.</p>
<h2>
	Partial mean</h2>
<pre>
area: mean where &lt;area_type&gt; over all_area_types time: mean</pre>
<p>
	This is equivalent to averaging over the whole cell after assigning a value of zero to areas which do not belong to the declared area type. Equal weight is given to each grid cell.&nbsp; A spatial map will show zero where the area type does not exist.</p>
<h2>
	Partial Mean over Sea</h2>
<pre>
area: mean where &lt;area_type&gt; over sea time: mean</pre>
<p>
	This is similar to the partial mean, except that it is restricted to ocean grid points (treating the sea area as constant: this construction becomes ambiguous if the sea area varies in time).</p>
<h2>
	Mass weighted mean</h2>
<pre>
area: mean where land time: mean (with samples weighted by snow mass)</pre>
<p>
	There is no explicit formulation for a mass weighted mean, which is used for one variable in CMIP6 (the mean temperature of snow), so the option of adding an explanatory comment in brackets is taken.</p>
<h2>
	Mean at a specific height</h2>
<pre>
area: mean where sea depth: minimum (shallowest local minimum) time: mean</pre>
<p>
	This cell methods string is used for one ocean variable, the &quot;Oxygen Minimum Concentration&quot; (o2min). First, a cell average is taken, and then shallowest local minimum is found, and this is averaged over time.</p>
<h2>
	Mean over a set of different area types</h2>
<p>
	When the diagnostic is a vector of values for different area types, as for the &quot;cSoilLut&quot; variable (Soil Carbon Content on Land Use Tiles), the cell methods string takes the form &quot;area: mean where landuse&quot;, and &quot;landuse&quot; is a dimension of the diagnostic.</p>
<h1>
	Examples from CMIP6</h1>
<h2>
	Sea Ice Snow Area Fraction (sisnconc) and Sea Ice Thickness (sithick)</h2>
<p>
	This variable is defined with the standard name &quot;surface_snow_area_fraction&quot;, but uses the cell methods string to restrict the area considered to snow on sea ice. The monthly weighted mean is requested. If, for instance, the sea ice in a grid cell is completely snow covered for the full month, the value of the monthly mean should be 1, even if the sea ice only partially fills the grid cell. Similarly with Sea Ice Thickness (standard name sea_ice_thickness): if ice covers half the grid cell with a uniform depth of 1m, the sithick value will be 1m. Undefined where there is no sea ice.</p>
<h2>
	Sea Ice Mass (simass)</h2>
<p>
	This variable is defined with the standard name &quot;sea_ice_amount&quot; (units kg m-2). It is defined as a partial mean, so that it gives a measure of the amount of sea ice in a grid cell, zero where there is no sea ice.</p>
<h1>
	More Subtle Examples</h1>
<h2>
	Sea-ice thickness in sea-ice thickness categories (siitdthick) and Snow thickness in sea-ice thickness categories (siitdsnthick)</h2>
<p>
	These variables are defined over certain categories of ice thickness. The snow thickness in areas with a specific ice thickness category is undefined if that category does not exist in the grid cell, so we want to mask by the amount of sea-ice in each thickness category. In other wprds, rather than masking by ice amount as a function of space and time, we want to mask by a different variable which gives ive amount as a function of space, time and ice thickness category.</p>
<p>
	&nbsp;</p>
</div> <!--// end div id=cog_post_body //-->
