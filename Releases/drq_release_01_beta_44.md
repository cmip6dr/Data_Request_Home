         

    <!--// START: /cog/templates/cog/post/page_template_main.html //-->
<!--// loading page body from page_template_main.html //-->




  	<!-- Data search widget -->
  	

    <div id="cog_post_body">
        <ul>
	<li>
		Fixed SIMIP cell methods: clarification and two corrections. See <a href="https://www.earthsystemcog.org/projects/wip/time_averages">www.earthsystemcog.org/projects/wip/time_averages</a> for general discusion of use of cell methods;</li>
	<li>
		Resolved realms for 100+ variable records;</li>
	<li>
		Updated C4MIP, VIACSAB, LUMIP, OMIP chemistry variables;</li>
	<li>
		Fixed broken request links for ~10 variables (leaving 18).</li>
	<li>
		Changed names on ocean variables zfull, zhalf, rsds, rsdl: adding &quot;o&quot; to avoid different standard names being associated with one variable name;</li>
</ul>
<p>
	The python API has been changed so that volume estimate include the CMIP request of core variables by default. To get information restricted to variables specifically requested by a MIP, use the argument &quot;--omitCmip&quot;. E.g.</p>
<p>
	drq -m LS3MIP --omitCmip</p>
<p>
	As before, there are two modules in the package which compute volume estimates. The newer version (previously only used when the &quot;--sf&quot; flag was added) is now the default. The older version can be used with the flag &quot;--legacy&quot;.</p>
<p>
	&nbsp;</p>
    </div> <!--// end div id=cog_post_body //-->

    <!-- include last updated text -->
    <!--// START: /cog/templates/cog/post/_post_last_update.html //-->

    <!--clear:both added to move the last update down if any elements above are floated.-->
    <!--clear:both means no floating elements allowed on either the left or the right side-->
	<div id="last_update_text" style="font-size: 8pt; font-style: italic; text-align:center; clear:both;">
	     Last Update: Jan. 27, 2017, 1:27 a.m. by
         
             <a href="/user/detail/1254/"></a>
         
	</div> <!--// end div id="last_update_text" //-->
