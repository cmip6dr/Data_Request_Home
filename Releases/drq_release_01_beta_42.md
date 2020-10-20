         

    <!--// START: /cog/templates/cog/post/page_template_main.html //-->
<!--// loading page body from page_template_main.html //-->




  	<!-- Data search widget -->
  	

    <div id="cog_post_body">
        <h2>
	Release 01.beta.42&nbsp; (Nov. 15th, 2016)</h2>
<p>
	One variable corrected in RFMIP;</p>
<p>
	Trimming of requests from C4MIP and VolMIP: reductions in the amount of high volume variables requested.</p>
<p>
	Around 20 missing cell_methods attributes filled in for CMOR variables;</p>
<p>
	8 misdirected request variable records corrected (e.g. in HighResMIP two variables intended to be on 7 pressure levels were mistakenly labelled as all model levels);</p>
<p>
	Missing units filled in.</p>
<p>
	Updates to experiments in several MIPs.</p>
<p>
	Update to DECK and historical experiments: the original template sent to MIP co-chairs at the end of 2014 asked them to specify requirements for control, amip, 1pctCO2, abrupt4xCO2 and historical experiments. The set of experiments defined by the CMIP panel has now expanded to: <font size="2"><span style="font-size:10pt;">1pctCO2, abrupt-4xCO2, amip, esm-hist, esm-hist-ext, esm-piControl, esm-piControl-spinup, historical, historical-ext, piControl, piControl-spinup. In this revsion, requests from MIP co-chairs for &quot;historical&quot; are interpreted as applying to <font size="2"><span style="font-size:10pt;">historical, historical-ext, <font size="2"><span style="font-size:10pt;">esm-hist, esm-hist-ext. Requests previously entered under &quot;control&quot; now apply to piControl and esm-piControl.</span></font></span></font></span></font></p>
<p>
	Cleaned up time slice specifications for the piControl experiment. Data from the piControl experiment is requested for slices of length 200, 165, 140, 100, 50, 30, and 20 years. These are to be interpreted as: 200 years from the branch point for a/the historical simulation;&nbsp; the time corresponding to the full historical simulation, and, for n=140 to 20, the years corresponding to the last n years of the historical simulation. It may be possible to reduce the number of different options here -- I will be contacting the MIP cochairs this to clarify. &nbsp;</p>
<p>
	&nbsp;</p>
<p>
	&nbsp;</p>
    </div> <!--// end div id=cog_post_body //-->

    <!-- include last updated text -->
    <!--// START: /cog/templates/cog/post/_post_last_update.html //-->

    <!--clear:both added to move the last update down if any elements above are floated.-->
    <!--clear:both means no floating elements allowed on either the left or the right side-->
	<div id="last_update_text" style="font-size: 8pt; font-style: italic; text-align:center; clear:both;">
	     Last Update: Jan. 23, 2017, 10:24 a.m. by
         
             <a href="/user/detail/1254/"></a>
         
	</div> <!--// end div id="last_update_text" //-->
