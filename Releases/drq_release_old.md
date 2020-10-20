<h1 class="title">Infromation on previous releases (before 01.beta.30)</h1>

<div id="cog_post_body">
    <div id="cog_post_body">
        <p>
	<style type="text/css">
<!-- 
		BODY,DIV,TABLE,THEAD,TBODY,TFOOT,TR,TH,TD,P { font-family:"Calibri"; font-size:x-small }
		 -->	</style>
	Previous versions</p>
<ul>
	<li>
		overview tables expanded to include more information about total request from each MIP;</li>
	<li>
		OMIP and AerChemMIP requests incorporated more fully;</li>
	<li>
		Minor updates and corrections for RFMIP, SIMIP, DCPP, DAMIP;</li>
	<li>
		some examples documented (<a href="http://proj.badc.rl.ac.uk/svn/exarch/CMIP6dreq/trunk/dreqPy/docs/dreqExamples.pdf">Examples);</a></li>
	<li>
		consistency of units checked (2 errors remain: tntr, ppmisc);</li>
	<li>
		better error handling for incomplete or mis-typed command line arguments;</li>
</ul>
<p>
	Version 01.beta.26 removal of duplication of CMOR variables names within each table; updates from DAMIP, AerChemMIP, OMIP, FAFMIP and a range of corrections. There is a new document describing how to use the request for example use-cases, describing different approaches (web site, command line, python library, XML</p>
<ul>
	<li>
		New feature added to API to generate lists of variables required for each experiment;</li>
	<li>
		30 broken requestVar links fixed, around 60 remaining</li>
	<li>
		Frequency of &quot;aero&quot; table corrected;</li>
	<li>
		500 broken requestVar links fixed, around 100 remaining;</li>
	<li>
		Around 60 duplicated records in the &quot;CMORvar&quot; section removed;</li>
	<li>
		Overview tables showing volume of data requested by each MIP for experiments specified by each MIP debugged;</li>
	<li>
		Lists of variables by requesting MIP and experiment;</li>
	<li>
		Added separate tables for instantaneous fields, e.g. &quot;em6hrpt&quot;, to resolve ambiguity between variables which are requested as both instantaneous and time mean values;</li>
	<li>
		Improved web interface;</li>
	<li>
		Removed several most of the duplicate CMOR variables;</li>
	<li>
		Added ranking of some DynVar pressure level options, to support selection of 10, 17 or 23 levels depending on priority (not fully implemented for all variables);</li>
	<li>
		Replaced OImon with SImon and SIday;</li>
	<li>
		Fixed some issues in DAMIP;</li>
	<li>
		Fixed a dependency on a python core library featture which was withdrawn in python 2.7;</li>
	<li>
		Added column in CMIP6_MIP_tables.xlsx to list, for each variable, the MIPs associated with experiments for which the variable is requested;</li>
	<li>
		Cleaned up some cell_methods specifications;</li>
	<li>
		Corrected some vertical coordinate specifications;</li>
	<li>
		Cleaned up references to thetaot;</li>
	<li>
		Added section for CMOR dimensions;</li>
	<li>
		Added a usage page for each MIP variable (e.g. <a href="http://clipc-services.ceda.ac.uk/dreq/t/agesno.html">clipc-services.ceda.ac.uk/dreq/t/agesno.html </a>) providing a technical view of where a variable is used.</li>
</ul>
<h2>
	Addtional resources:</h2>
<ul>
	<li>
		Template to be filled in and returned by Feb 28th (see revised timetable in guidance notes): 
		         <a href="/Documents/CMIP6DataRequestCompilationTemplate_20141218.xls?raw=True"> template</a></li>
	<li>
		Table of previously used variable names: 
		       <a href="/Documents/MIPVariableNames.xls?raw=True">MIP Variable Names</a></li>
	<li>
		Guidance on information request issued in December 2014 (updated, Jan. 16, 2015): <a href="/Documents/CMIP6DataRequestCompilationGuidanceNote_150116.pdf"><strong>CMIP6 </strong>Data Request Compilation Guidance <strong>Note</strong></a><
	</li>
	<li>
		Enter observational dataset to be used for data validation: <a href="http://goo.gl/forms/LBN9yninxS">dataset registry form</a> (or <a href="https://docs.google.com/spreadsheets/d/1X-IProjJWaKUVAtPdaOCq0lPypUcOi102AD_2oL6748/edit#gid=1181296695">view registry</a>)</li>
</ul>
</div> <!--// end div id=cog_post_body //-->
