<h1 class="title">Data Request Package Installation and Usage</h1>

<div id="cog_post_body">
    <div id="cog_post_body">
        <p>
	To install from the python repository:</p>
<p style="margin-left: 40px;">
	<kbd><code>pip install -i https://pypi.python.org/pypi [--user]&nbsp; dreqPy==01.00.29</code></kbd></p>
<p style="margin-left: 40px;">
	<kbd><code>or</code></kbd></p>
<p style="margin-left: 40px;">
	<kbd><code>pip install --upgrade dreqPy</code></kbd></p>
<p>
	The package can also be downloaded from the SVN repository:</p>
<p style="margin-left: 40px;">
	<kbd><code>svn co <a href="http://proj.badc.rl.ac.uk/svn/exarch/CMIP6dreq/tags/01.00.29">http://proj.badc.rl.ac.uk/svn/exarch/CMIP6dreq/tags/01.00.29 </a></code></kbd></p>
<p>
	and then installed with:</p>
<p style="margin-left: 40px;">
	<kbd>python setup.py install.</kbd></p>
<p>
	The command line interface can then be accessed with, for instance:</p>
<p style="margin-left: 40px;">
	<kbd>drq -m HighResMIP,C4MIP -e historical --xls</kbd></p>
<p>
	will create a spreadsheet file listing the variables requested by C4MIP and HighResMIP for the &quot;historical&quot; experiment.</p>

<p>
	For more information, see the following documents.</p>
<ul>
	<li>
		<a href="http://proj.badc.rl.ac.uk/svn/exarch/CMIP6dreq/trunk/dreqPy/docs/dreqExamples.pdf">Examples</a></li>
	<li>
		<a href="http://proj.badc.rl.ac.uk/svn/exarch/CMIP6dreq/tags/latest/dreqPy/docs/dreqPy.pdf">Python Library (dreqPy)</a></li>
</ul>
</div> <!--// end div id=cog_post_body //-->
