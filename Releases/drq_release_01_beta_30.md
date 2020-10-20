         

    <!--// START: /cog/templates/cog/post/page_template_main.html //-->
<!--// loading page body from page_template_main.html //-->




  	<!-- Data search widget -->
  	

    <div id="cog_post_body">
        <p>
	<style type="text/css">
H2 { margin-bottom: 0.21cm; }H2.ctl { font-family: "Lohit Hindi"; }P { margin-bottom: 0.21cm; }A:link {  }	</style>
</p>
<p>
	Corrects some further bugs in the generation of variable lists in spreadsheets.</p>
<p>
	There is a new option in the command line interface to list of variables as a text file:</p>
<p style="margin-left: 40px;">
	<kbd>drq -m HighResMIP --txt</kbd></p>
<p>
	Output files are placed in the &quot;xls&quot; subdirectory and include tab separated lists of variables requested for each experiment by HighResMIP. This option is designed to make it easier to track changes in the data request.</p>
<h2>
	Content</h2>
<ul>
	<li>
		<p style="margin-bottom: 0cm">
			where area fractions are requested as percentages, I have started changing the long names and descriptions to refer to &quot;percentage&quot; instead of fraction.</p>
	</li>
	<li>
		<p style="margin-bottom: 0cm">
			clarification of some definitions: e.g. landCoverFrac is more general than plan functional types.</p>
	</li>
	<li>
		<p>
			added a &quot;units&quot; section, which is linked to from variable definitions. This allows more robust checking of units provides a mechanism for comparing related variables.</p>
	</li>
</ul>
    </div> <!--// end div id=cog_post_body //-->

    <!-- include last updated text -->
    <!--// START: /cog/templates/cog/post/_post_last_update.html //-->

    <!--clear:both added to move the last update down if any elements above are floated.-->
    <!--clear:both means no floating elements allowed on either the left or the right side-->
	<div id="last_update_text" style="font-size: 8pt; font-style: italic; text-align:center; clear:both;">
	     Last Update: July 21, 2016, 9:06 a.m. by
         
             <a href="/user/detail/1254/"></a>
         
	</div> <!--// end div id="last_update_text" //-->
