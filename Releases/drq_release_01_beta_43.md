         

    <!--// START: /cog/templates/cog/post/page_template_main.html //-->
<!--// loading page body from page_template_main.html //-->




  	<!-- Data search widget -->
  	

    <div id="cog_post_body">
        <p>
	Added in the &quot;CMIP Request&quot;: this is a core set of variables, requested from the DECK and CMIP6 historical simulations. The &quot;CMIP&quot; requested variables should be provided for all models. This does not include any new variables (except for thos being introduced into the Omon and Oyr tables by OMIP);</p>
<p>
	Corrected clisccp assigment to cfDay_3d (was getting assigned to cfDay_2d, inflating request volume). (editted in util_anal.py, util_gen.py);</p>
<p>
	Adjusted LS3MIP requirements for 3-hourly data from the historical simulation: reduced to 35 years;</p>
<p>
	Updates ISMIP6, DAMIP, OMIP (physical oceanography) requests. Further updates from the OMIP bio-geochemistry and chemistry variables will be implemented soon;</p>
<p>
	Fixed a number of bugs raised on https://github.com/cmip6dr/CMIP6_DataRequest_VariableDefinitions;</p>
<p>
	Added time period of requested data to spreadsheets of variables requested for individual experiments (3 additional columns to the right);</p>
<p>
	Added a feature to the python API to provide variable sheets sorted by frequency and realm, rather than by table:</p>
<p>
	drq -m &lt;mip1&gt;[,&lt;mip2]&nbsp; --sf --xfr</p>
    </div> <!--// end div id=cog_post_body //-->

    <!-- include last updated text -->
    <!--// START: /cog/templates/cog/post/_post_last_update.html //-->

    <!--clear:both added to move the last update down if any elements above are floated.-->
    <!--clear:both means no floating elements allowed on either the left or the right side-->
	<div id="last_update_text" style="font-size: 8pt; font-style: italic; text-align:center; clear:both;">
	     Last Update: Jan. 27, 2017, 1:27 a.m. by
         
             <a href="/user/detail/1254/"></a>
         
	</div> <!--// end div id="last_update_text" //-->
