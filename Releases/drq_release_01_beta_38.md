         

    <!--// START: /cog/templates/cog/post/page_template_main.html //-->
<!--// loading page body from page_template_main.html //-->




  	<!-- Data search widget -->
  	

    <div id="cog_post_body">
        <p>
	Release 01.beta.38&nbsp; (Oct. 21st, 2016)</p>
<p>
	<style type="text/css">
P { margin-bottom: 0.21cm; }	</style>
</p>
<p>
	Anomalies removed from &quot;uid&quot; string. A character restriction is now enforced for the &ldquo;uid&rdquo; string: only characters a-z, A-Z, 0-9, :_.+- are permitted. A quote had appeared in on uid string, causing problems for some software. Space and &ldquo;?&rdquo; characters have also been cleared out.</p>
<p>
	One typographical error in CF Standard Name list: one name included a spurious space.</p>
<p>
	Replaced references to usi, vsi, sit, sic with new variables siu, siv, sithick, siconc.</p>
<p>
	Removed some arbitrary variation in structure records. A number of records had different but equivalent formulations of the cell_measures attribute.</p>
<p>
	Updated AerChemMIP experiment names.</p>
<p>
	Fixed command line option to filter volume estimate on experiment or MIP defining experiments. E.g. to get a volume estimate for LS3MIP requests from ScenarioMIP experiments:</p>
<p>
	drq -m LS3MIP -e ScenarioMIP --sf</p>
<p>
	&nbsp;</p>
    </div> <!--// end div id=cog_post_body //-->

    <!-- include last updated text -->
    <!--// START: /cog/templates/cog/post/_post_last_update.html //-->

    <!--clear:both added to move the last update down if any elements above are floated.-->
    <!--clear:both means no floating elements allowed on either the left or the right side-->
	<div id="last_update_text" style="font-size: 8pt; font-style: italic; text-align:center; clear:both;">
	     Last Update: Jan. 27, 2017, 1:26 a.m. by
         
             <a href="/user/detail/1254/"></a>
         
	</div> <!--// end div id="last_update_text" //-->
