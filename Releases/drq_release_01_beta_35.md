<h1 class="title">Release 01.beta.35</h1>

<div id="cog_post_body">
    <div id="cog_post_body">
        <p>
	Release 01.beta.35&nbsp; (Sept. 19th, 2016)</p>
<p>
	ua, va in &quot;day&quot; (on 8 pressure levels): changed to cell_measures=area: areacella (from unset). This implies values should be interpolated to grid cell centres, rather than being provided on exact positions used in the model.</p>
<p>
	Added directives &quot;--OPT&quot; and &quot;--MODEL&quot; in the cell_measures attribute for variables which should or may be provided on cell vertices or edges rather than cell centres. See <a href="https://earthsystemcog.org/projects/wip/drq_interp_cell_center">Interpolation to cell center</a> for details.</p>
<p>
	Fixed a data base corruption introduced in 01.beta.34 which led to many request variable groups being empty, and cleaned up treatment of request groups.</p>
<p>
	Fixed a bug in scope_utils which prevented generation of spreadsheets from working.</p>
<p>
	Fixed python imports so that the package now works with python 3.</p>
<p>
	Fixed some inconsistencies in the version information.</p>
<p>
	Added, in the web interface, a usage summary for each request variable group: for each group a table shows the objectives it is requested for against the MIPs and experiments (e.g <a href="http://clipc-services.ceda.ac.uk/dreq/u/ef12e22c-5629-11e6-9079-ac72891c3257__xx.html">http://clipc-services.ceda.ac.uk/dreq/u/ef12e22c-5629-11e6-9079-ac72891c3257__xx.html</a> ).</p>
</div> <!--// end div id=cog_post_body //-->
