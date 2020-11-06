<h1 class="title">Interpolation to standard grids</h1>

<div id="cog_post_body">
    <div id="cog_post_body">
        <p>
	Data providers may wish to interpolate their data to a regular grid, both to make the data more accessible for a wide range of users and to reduce the overall data volume. In the data request, some variables requested by some MIPs (CFMIP, FAFMIP, HighResMIP, LS3MIP, LUMIP, RFMIP, SIMIP) are required on a native grid (e.g. in order to ensure that flux calculations can be performed with sufficient accuracy). For other variables there is a stated preference that they be provided on a regular grid (in order to make comparisons between models easier), and for many variables there is no preference.</p>
<p>
	The data request API will produce volume estimates, and the resulting volume depends on an assumption about the model resolution and the strategy taken for providing regridded data vs. data on a native grid. The default options, since version 01.beta.37, is to assume ocean data will be provided on a 1 degree grid unless there is a specific requirement for the data on the native grid. This default can be changed by running with the argument &quot;--grdpol native&quot;, in which case the data will be assumed to be interpolated only when there is a specific request for this to be done. The argument &quot;--grdforce native&quot; can be used to obtain a volume estimate based on always using the native grid. Similarly [to be introduced in 01.beta.44] &quot;--grdforce 1deg&quot; will give an estimate based on always using a 1 degree grid.</p>
</div> <!--// end div id=cog_post_body //-->
