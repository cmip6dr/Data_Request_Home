<h1 class="title">Zonal and Quasi-zonal means</h1>

<div id="cog_post_body">
    <div id="cog_post_body">
        <p>
	The CMIP6 request includes zonal means and some variants.</p>
<ul>
	<li>
		The simple zonal mean, an average around a complete circle of constant latitude, is indicated by &quot;<strong>longitude: mean</strong>&quot; in the cell methods string.</li>
	<li>
		When the mean is restricted to a single ocean basin, the cell methods string is modified by a comment: &quot;<strong>longitude: mean (basin)</strong>&quot;.</li>
	<li>
		For a set of ocean circulation diagnostics there are explicit instructions on how to evaluate the zonal mean in the case of a model grid which is not aligned with latitude and longitude: the mean circulation should be calculated using a line of integration which zig-zags along grid boundaries which cross the chosen latitude. This is indicated with a longer comment: &quot;<strong>longitude: mean (comment: basin mean along zig-zag grid path)</strong>&quot;.</li>
	<li>
		When the ocean grid is not a regular latitude-longitude grid, additional diagnostics are requested averaged along a grid latitude. The cell methods string for these diagnostics contains &quot;<strong>grid_longitude: mean</strong>&quot;. In CMIP5 the only diagnostics submitted in this category were from a model with a rotated pole grid.</li>
</ul>
<p>
	&nbsp;</p>
</div> <!--// end div id=cog_post_body //-->
