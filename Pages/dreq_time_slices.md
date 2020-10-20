<h1 class="title">Data Request Time Slices</h1>

<div id="cog_post_body">
    <div id="cog_post_body">
        <p>
	The data request uses a range of time slices which specify sub-sets of an experiment time span, typically used for high frequency data. There is a full list here:<a href="http://clipc-services.ceda.ac.uk/dreq/index/timeSlice.html"> link</a>.</p>
<p>
	There are many cases where different MIPs are asking for a variable from different time slices. In most such cases the slices form a sequence and the data provider should provide the data corresponding to the largest time slice in the sequence.</p>
<h1>
	1. Sequences</h1>
<h2>
	1.1 Historical</h2>
<p>
	Data from historical simulations are requested in slices 20, 36, 55 and 65 years .. all of these are periods ending 2014.</p>
<p>
	DAMIP are also requesting data for 6 years of the historical-ext experiment, and for a 42 year period 1979-2020 (matching the last 36 of the historical experiment plus 6 years of the extension) from a ranage of perturbation experiments. See section 2.3.</p>
<p>
	From CFMIP, there is a request for data from a single year, 2008.</p>
<h2>
	1.2 piControl</h2>
<p>
	Slices in the piControl simulation are mainly relative to the point at which the historical simulation branches away from the control. There are slces of length 20, 30, 40, 50,100, 140, 165, 200.&nbsp; All but the last are defined to end with the last year of the historical simulation, 2014. The 200 year slice starts from the branch time (which is 1850 in the historical experiment) and runs up to the end of the piControl year corresponding to 2049 in the projections extending the historical simulation.</p>
<h1>
	2. Other</h1>
<h2>
	2.1 Selected days</h2>
<p>
	RFMIP has asked for some 3-hourly data. on atmospheric model levels and with spectral band dependancy, on a limited number of days from the . The request also includes a number of 3-hourly surface variables. Selected days of the year are the first days of January, April, July and October. Modelling groups supporting RFMIP Tier 1 should data on these days from 1850 and 2005, those supporting Tier 2 should additonally provide data from 1980 and 1992. We recommend that one data file is provided for each day, so that time intervals are constant at 3 hour in each file.</p>
<p>
	In some cases variables are requested both by RFMIP for these slices and, through the CMIP core request, also requested for the last 55 years of the historical simulation (the CMIP core 3-hourly request only includes surface fields, not the multilevel, multi-band data which motivates the use of shorter slices in RFMIP). The Tier 2 RFMIP slice is completely included in this 55 year period, so only the continuous time series is needed. To comply with the Tier 1 RFMIP request, there should be 4 files for single days from 1850 as well as for the continuous time period from 1950 to 2014.</p>
<h2>
	2.2 DAMIP 20 year slices</h2>
<p>
	DAMIP is requesting some data for the 20 year period 2081 to 2200 and a smaller set of data for two 20 year intervals, 2041 to 2060 and 2081 to 2200.</p>
<h2>
	2.3 Extensions to the historical simulation</h2>
<p>
	The CMIP6 historical simulation uses a set of carefully characterised forcing datasets which end in 2014. There is a historical-ext experiment to run models on using estimates of more recent forcings. For perturbation experiments there is no distinction between before and after 2014, so a single hist-sol experiment, for instance, can run from 1850 to 2020. In DAMIP, for instance, this means that many variables are requested, for example, from 1979 to 2020 of the pertubation experiments and also from 1979 to 2014 of the historical experiment plus 2015 to 2020 of historical-ext.</p>
<h2>
	2.4 Start and 121-150 of abrupt4xCO2</h2>
<p>
	There is a request for 3-hourly data for 5 years at the start of the abrupt4xCO2 experiment and 30 years from year 121 to 150.</p>
<h2>
	2.5 Start of VolMIP experiments</h2>
<p>
	There are requests for 3 year slices at the start of some VolMIP experiments.</p>
</div> <!--// end div id=cog_post_body //-->
