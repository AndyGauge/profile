----
layout: efi
----
<div id="pageheader">
	<h2><a class="titles" href="./viewtopic.php?f=45&amp;t=2110">json, CAN</a></h2>


</div>

<br clear="all" /><br />

<div id="pagecontent">

	<table width="100%" cellspacing="1">
	<tr>
		
			<td align="left" valign="middle" nowrap="nowrap">
				<a href="./posting.php?mode=reply&amp;f=45&amp;t=2110"><img src="./styles/diyavalon/imageset/en/button_topic_reply.gif" height="22" alt="Reply to topic" title="Reply to topic" /></a>
			</td>
		
			<td class="nav" valign="middle" nowrap="nowrap">&nbsp;Page <strong>1</strong> of <strong>5</strong><br /></td>
			<td class="gensmall" nowrap="nowrap">&nbsp;[ 43 posts ]&nbsp;</td>
			<td class="gensmall" width="100%" align="right" nowrap="nowrap"><b><a href="#" onclick="jumpto(); return false;" title="Click to jump to page…">Go to page</a> <strong>1</strong><span class="page-sep">, </span><a href="./viewtopic.php?f=45&amp;t=2110&amp;start=10">2</a><span class="page-sep">, </span><a href="./viewtopic.php?f=45&amp;t=2110&amp;start=20">3</a><span class="page-sep">, </span><a href="./viewtopic.php?f=45&amp;t=2110&amp;start=30">4</a><span class="page-sep">, </span><a href="./viewtopic.php?f=45&amp;t=2110&amp;start=40">5</a> &nbsp;<a href="./viewtopic.php?f=45&amp;t=2110&amp;start=10">Next</a></b></td>
		
	</tr>
	</table>

			<table width="100%" cellspacing="0">
			<tr>
				<td class="nav" nowrap="nowrap">
				<a href="./viewtopic.php?uid=2833&amp;f=45&amp;t=2110&amp;watch=topic&amp;start=0&amp;hash=b378c6b3" title="Subscribe topic">Subscribe topic</a> | <a href="./viewtopic.php?f=45&amp;t=2110&amp;bookmark=1&amp;hash=b378c6b3" title="Bookmark topic">Bookmark topic</a> | <a href="./viewtopic.php?f=45&amp;t=2110&amp;view=print" title="Print view">Print view</a> | <a href="./memberlist.php?mode=email&amp;t=2110" title="E-mail friend">E-mail friend</a> | <a href="./posting.php?mode=bump&amp;f=45&amp;t=2110&amp;hash=b378c6b3" title="Bump topic">Bump topic</a>
				</td>
				<td class="nav" align="right" nowrap="nowrap"><a href="./viewtopic.php?f=45&amp;t=2110&amp;view=previous">Previous topic</a> | <a href="./viewtopic.php?f=45&amp;t=2110&amp;view=next">Next topic</a>&nbsp;</td>
			</tr>
			</table>

	<div class="block-start">
	<div class="cap-div"><div class="cap-left"><div class="cap-right">json, CAN&nbsp;</div></div></div>
	<table class="tablebg" width="100%" cellspacing="0">
        
        <tr>
            <th>Author</th>
            <th width="100%">Message</th>
        </tr>
        <tr class="row1">

			<td align="center" valign="top" class="row">
				<a name="p33716"></a>
				<div class="postauthor">andg</div>
				<div class="postonline"><img src="./styles/diyavalon/imageset/en/icon_user_online.gif" height="11" alt="Online" title="Online" /></div><div class="posterrank">SOT-223 - Salvaje</div>

				<div class="postdetails">
					<br /><b>Joined:</b> Wed Apr 17, 2013 6:21 pm<br /><b>Posts:</b> 90<br /><b>Location:</b> Portland OREGON
				</div>
				<img src="./styles/diyavalon309/theme/images/spacer.gif" width="120" height="1" alt="" />
			</td>
			<td width="100%" height="25" class="row" valign="top">
				<div style="float: right;"><a href="./posting.php?mode=edit&amp;f=45&amp;p=33716"><img src="./styles/diyavalon/imageset/en/icon_post_edit.gif" height="13" alt="Edit post" title="Edit post" /></a> <a href="./posting.php?mode=quote&amp;f=45&amp;p=33716"><img src="./styles/diyavalon/imageset/en/icon_post_quote.gif" height="13" alt="Reply with quote" title="Reply with quote" /></a></div>
				<div class="postsubject"><a href="./viewtopic.php?p=33716#p33716"><img src="./styles/diyavalon/imageset/icon_topic_latest.gif" width="13" height="9" alt="Post" title="Post" /></a>&nbsp;json, CAN</div>

					

						<div class="postbody">so the idea is to talk about mongo db in an implementation prepared to log data that doesn't necessarily have a schema.  So json is a standard that defines data at a state in time.  A sample user of a forum example.<br /><br />Hi my name is Nathan Sparks and I have 42 posts on the diy_efi board.<br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">user<br />{ _id: BSON_id //a number like 0xb2d91ae6f8416660<br />{first_name: &quot;Nathan&quot;,<br />last_name: &quot;Sparks&quot;,<br />post_count: 42,<br />memberships:<br />{board_name: &quot;diy_efi&quot;}<br />}<br /></div></div><br />Honestly I see the memberships embedded document being deeper but this is for a sample, and I'm trying to keep this simple.  In use in engine management this could be used in combination with the network of sensors standard known as CAN.  It provides banks of sensors so it would look something like this:<br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">{<br />p_0: 15.0<br />p_1: 0<br />p_5: duh is this getting boring?<br />}</div></div><br />that could be dynamically appended a t value that defines where in the sequence of the logging and that value would be indexed.</div>

					
						<br clear="all" /><br />

						<div class="attachwrapper"><div class="attachtitle">Attachments:</div>
						
						<div class="attachcontent">
			<span class="gensmall"><b>File comment:</b> from my laptop on the hammock on my fort the first half finished project</span><br />
		
			<a href="./download/file.php?id=1356&amp;mode=view"><img src="./download/file.php?id=1356&amp;t=1" alt="hammock_speak.jpg" /></a><br />
			<span class="gensmall">hammock_speak.jpg [ 209.08 KiB | Viewed 34 times ]</span>
		

		<br />
	</div>
						
						</div>
					
						<div class="postbody signature"><br /><span class="line">_________________</span><br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">{url: &quot;andrewgauger.com, skype: andrgaug, email: andg@andrewgauger.com, car: 25, fb: facebook.com/DonatoArrighi}</div></div></div>
					
							<br /><br />
							<div class="edited">
    							<p class="gensmall">Last edited by <a href="./memberlist.php?mode=viewprofile&amp;u=2833">andg</a> on Sun Apr 28, 2013 11:57 am, edited 4 times in total.</p>
    						</div>
						
			</td>
		</tr>

		<tr class="row1">

			<td class="postbottom" align="center">Fri Apr 26, 2013 7:10 pm</td>
			<td class="postbottom postbuttons" valign="middle">
				
					<div style="float: right">
					<a href="./report.php?f=45&amp;p=33716"><img src="./styles/diyavalon/imageset/icon_post_report.gif" width="11" height="13" alt="Report this post" title="Report this post" /></a> 
					</div>
				<a href="./memberlist.php?mode=viewprofile&amp;u=2833"><img src="./styles/diyavalon/imageset/en/icon_user_profile.gif" height="13" alt="Profile" title="Profile" /></a> <a href="./ucp.php?i=pm&amp;mode=compose&amp;action=quotepost&amp;p=33716"><img src="./styles/diyavalon/imageset/en/icon_contact_pm.gif" height="13" alt="Send private message" title="Send private message" /></a> <a href="http://andrewgauger.com"><img src="./styles/diyavalon/imageset/icon_contact_www.gif" width="27" height="13" alt="WWW" title="WWW" /></a> 
			</td>
    	
		</tr>
	
	<tr>
		<td class="spacer" colspan="2" height="1"><img src="./styles/diyavalon309/theme/images/spacer.gif" alt="" width="1" height="1" /></td>
	</tr>
	<tr class="row2">

			<td align="center" valign="top" class="row">
				<a name="p33717"></a>
				<div class="postauthor">andg</div>
				<div class="postonline"><img src="./styles/diyavalon/imageset/en/icon_user_online.gif" height="11" alt="Online" title="Online" /></div><div class="posterrank">SOT-223 - Salvaje</div>

				<div class="postdetails">
					<br /><b>Joined:</b> Wed Apr 17, 2013 6:21 pm<br /><b>Posts:</b> 90<br /><b>Location:</b> Portland OREGON
				</div>
				<img src="./styles/diyavalon309/theme/images/spacer.gif" width="120" height="1" alt="" />
			</td>
			<td width="100%" height="25" class="row" valign="top">
				<div style="float: right;"><a href="./posting.php?mode=edit&amp;f=45&amp;p=33717"><img src="./styles/diyavalon/imageset/en/icon_post_edit.gif" height="13" alt="Edit post" title="Edit post" /></a> <a href="./posting.php?mode=quote&amp;f=45&amp;p=33717"><img src="./styles/diyavalon/imageset/en/icon_post_quote.gif" height="13" alt="Reply with quote" title="Reply with quote" /></a></div>
				<div class="postsubject"><a href="./viewtopic.php?p=33717#p33717"><img src="./styles/diyavalon/imageset/icon_topic_latest.gif" width="13" height="9" alt="Post" title="Post" /></a>&nbsp;Re: json, CAN</div>

					

						<div class="postbody">perfect place to put un implemented features so if at a later date we have data that is expected to be 0.  we can filter that out easily later.  so _max and _avg can be filtered until the register stars responding like an O2 sensor.  <br /><br />So the engine is at the mercy of the ecu until the feedback from the o2 sensor can keep the engine running.  Before that time, the ecu needs to deal with throttle position, air bypass injection and spark.<br /><br />voltage of the sensor ranges from 100 to 900 mV.  and the current ECU will throw a trouble code if the range remains below 300 or above 800.<br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">{_id: BSON,<br />o2: 0.134,<br />t_value: 1},<br />&#93;{_id: BSON,<br />o2: 0.1356,<br />t_value: 2},<br />&#93;{_id: BSON,<br />o2: 0.256,<br />t_value: 3},</div></div><br />if I were in the console I could query the data<br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">db.sensors.find({t_value: {$lt:&nbsp; 4}})</div></div></div>

					
						<div class="postbody signature"><br /><span class="line">_________________</span><br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">{url: &quot;andrewgauger.com, skype: andrgaug, email: andg@andrewgauger.com, car: 25, fb: facebook.com/DonatoArrighi}</div></div></div>
					
							<br /><br />
							<div class="edited">
    							<p class="gensmall">Last edited by <a href="./memberlist.php?mode=viewprofile&amp;u=2833">andg</a> on Sun Apr 28, 2013 1:07 pm, edited 3 times in total.</p>
    						</div>
						<br clear="all" /><br />
			</td>
		</tr>

		<tr class="row2">

			<td class="postbottom" align="center">Fri Apr 26, 2013 7:28 pm</td>
			<td class="postbottom postbuttons" valign="middle">
				
					<div style="float: right">
					<a href="./report.php?f=45&amp;p=33717"><img src="./styles/diyavalon/imageset/icon_post_report.gif" width="11" height="13" alt="Report this post" title="Report this post" /></a> 
					</div>
				<a href="./memberlist.php?mode=viewprofile&amp;u=2833"><img src="./styles/diyavalon/imageset/en/icon_user_profile.gif" height="13" alt="Profile" title="Profile" /></a> <a href="./ucp.php?i=pm&amp;mode=compose&amp;action=quotepost&amp;p=33717"><img src="./styles/diyavalon/imageset/en/icon_contact_pm.gif" height="13" alt="Send private message" title="Send private message" /></a> <a href="http://andrewgauger.com"><img src="./styles/diyavalon/imageset/icon_contact_www.gif" width="27" height="13" alt="WWW" title="WWW" /></a> 
			</td>
    	
		</tr>
	
	<tr>
		<td class="spacer" colspan="2" height="1"><img src="./styles/diyavalon309/theme/images/spacer.gif" alt="" width="1" height="1" /></td>
	</tr>
	<tr class="row1">

			<td align="center" valign="top" class="row">
				<a name="p33718"></a>
				<div class="postauthor">andg</div>
				<div class="postonline"><img src="./styles/diyavalon/imageset/en/icon_user_online.gif" height="11" alt="Online" title="Online" /></div><div class="posterrank">SOT-223 - Salvaje</div>

				<div class="postdetails">
					<br /><b>Joined:</b> Wed Apr 17, 2013 6:21 pm<br /><b>Posts:</b> 90<br /><b>Location:</b> Portland OREGON
				</div>
				<img src="./styles/diyavalon309/theme/images/spacer.gif" width="120" height="1" alt="" />
			</td>
			<td width="100%" height="25" class="row" valign="top">
				<div style="float: right;"><a href="./posting.php?mode=edit&amp;f=45&amp;p=33718"><img src="./styles/diyavalon/imageset/en/icon_post_edit.gif" height="13" alt="Edit post" title="Edit post" /></a> <a href="./posting.php?mode=quote&amp;f=45&amp;p=33718"><img src="./styles/diyavalon/imageset/en/icon_post_quote.gif" height="13" alt="Reply with quote" title="Reply with quote" /></a></div>
				<div class="postsubject"><a href="./viewtopic.php?p=33718#p33718"><img src="./styles/diyavalon/imageset/icon_topic_latest.gif" width="13" height="9" alt="Post" title="Post" /></a>&nbsp;Re: json, CAN</div>

					

						<div class="postbody">so it takes event handlers like <br />t_value = now - 150 _avg<br />if we need to evaluate if a sensor has been offline for 150 cycles we need listeners<br />small mongodb instances that are self garbage collecting using capped collections<br />optimized data evaluation<br /><br />This same capped collection can be used to determine a sensor is out of range.<br /><br />Since we don't know many documents per second that we are going to receive we set the capped collection to be tuned on the least number that can be metriced when saving only the single sensor to the database.  Since documents performance are based on size of the document, the best performant implementation can be set as a value based on the test.  <br /><br />You can then gauge your performance when you do a query on the t value for the time range the test was for.  If our isolated test revealed maximized performance tooks 3000 documents and in implementation there were 2000 documents returned from<br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">db.sensor_log.find({created_at: { $lte: new Timestamp() - 0x10000 } } )</div></div><br /><br />MongoDB support for timestamps <a href="http://docs.mongodb.org/manual/core/document/#timestamps" class="postlink" rel="nofollow" target="_blank">docs.mongodb.org</a><br /><div class="quotewrapper"><div class="quotetitle">mongo reference timestamps wrote:</div><div class="quotecontent">Timestamp values are a 64 bit value where:<br /><br />the first 32 bits are a time_t value (seconds since the Unix epoch)<br />the second 32 bits are an incrementing ordinal for operations within a given second.<br /></div></div></div>

					
						<div class="postbody signature"><br /><span class="line">_________________</span><br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">{url: &quot;andrewgauger.com, skype: andrgaug, email: andg@andrewgauger.com, car: 25, fb: facebook.com/DonatoArrighi}</div></div></div>
					
							<br /><br />
							<div class="edited">
    							<p class="gensmall">Last edited by <a href="./memberlist.php?mode=viewprofile&amp;u=2833">andg</a> on Sun Apr 28, 2013 1:08 pm, edited 4 times in total.</p>
    						</div>
						<br clear="all" /><br />
			</td>
		</tr>

		<tr class="row1">

			<td class="postbottom" align="center">Fri Apr 26, 2013 7:56 pm</td>
			<td class="postbottom postbuttons" valign="middle">
				
					<div style="float: right">
					<a href="./report.php?f=45&amp;p=33718"><img src="./styles/diyavalon/imageset/icon_post_report.gif" width="11" height="13" alt="Report this post" title="Report this post" /></a> 
					</div>
				<a href="./memberlist.php?mode=viewprofile&amp;u=2833"><img src="./styles/diyavalon/imageset/en/icon_user_profile.gif" height="13" alt="Profile" title="Profile" /></a> <a href="./ucp.php?i=pm&amp;mode=compose&amp;action=quotepost&amp;p=33718"><img src="./styles/diyavalon/imageset/en/icon_contact_pm.gif" height="13" alt="Send private message" title="Send private message" /></a> <a href="http://andrewgauger.com"><img src="./styles/diyavalon/imageset/icon_contact_www.gif" width="27" height="13" alt="WWW" title="WWW" /></a> 
			</td>
    	
		</tr>
	
	<tr>
		<td class="spacer" colspan="2" height="1"><img src="./styles/diyavalon309/theme/images/spacer.gif" alt="" width="1" height="1" /></td>
	</tr>
	<tr class="row2">

			<td align="center" valign="top" class="row">
				<a name="p33719"></a>
				<div class="postauthor">andg</div>
				<div class="postonline"><img src="./styles/diyavalon/imageset/en/icon_user_online.gif" height="11" alt="Online" title="Online" /></div><div class="posterrank">SOT-223 - Salvaje</div>

				<div class="postdetails">
					<br /><b>Joined:</b> Wed Apr 17, 2013 6:21 pm<br /><b>Posts:</b> 90<br /><b>Location:</b> Portland OREGON
				</div>
				<img src="./styles/diyavalon309/theme/images/spacer.gif" width="120" height="1" alt="" />
			</td>
			<td width="100%" height="25" class="row" valign="top">
				<div style="float: right;"><a href="./posting.php?mode=edit&amp;f=45&amp;p=33719"><img src="./styles/diyavalon/imageset/en/icon_post_edit.gif" height="13" alt="Edit post" title="Edit post" /></a> <a href="./posting.php?mode=quote&amp;f=45&amp;p=33719"><img src="./styles/diyavalon/imageset/en/icon_post_quote.gif" height="13" alt="Reply with quote" title="Reply with quote" /></a></div>
				<div class="postsubject"><a href="./viewtopic.php?p=33719#p33719"><img src="./styles/diyavalon/imageset/icon_topic_latest.gif" width="13" height="9" alt="Post" title="Post" /></a>&nbsp;Re: json, CAN</div>

					

						<div class="postbody">use it as an extaction layor for an existing SQL instance by issuing sql commands and interpreting the results into a JSON log output and output to targit {name to be determined, I know it starts with the letter x and released in a later version of their bi tool; the whole reason I'm implementing it in a data center with the upgraded release version so all the new features unlock as part of the migration] which is designed to show multi dimensional views of predefined unputs.<br /><br />In troubleshooting large sql tables I often start by query with a <br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">SELECT TOP 1 * from PBAInstanceTable</div></div><br /><br />which returns column names of the table that is used to define a product model which has configuration options for a product like <a href="http://www.rejuvenation.com/catalog/products/kent-quick-ship-ob" class="postlink" rel="nofollow" target="_blank">Kent</a> which can be seen in the <a href="http://www.rejuvenation.com/catalog/products/cascade" class="postlink" rel="nofollow" target="_blank">configuration engine</a>.<br /><br />Options like vaulted, or finish, length, shade are records in sql using referencial number.  I would want another SQL statement to return the collection of these configurations.  By the way it will return pre and post configuration engine variables so you will actually need to filter on that as well if you want to return a single configuration detail set.<br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">SELECT * from PBATABLEINSTANCE WHERE INVENTTRANSID = {#instance_variable}</div></div><br /><br />I would want to have JSON logging like this<br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">{ _id: BSON ,<br />query: &quot;SELECT TOP 1 * from PBAInstanceTable&quot;,<br />headers: &quot;INVENTTRANSID, variable, value&quot;<br />rows: &quot;1, pba_model_number, 1&quot;<br />},<br />{_id: BSON,<br />query: &quot;SELECT * from PBATABLEINSTANCE WHERE INVENTTRANSID = 3245&quot;,<br />rows: {<br />3245, pba_model_number, 25<br />3245, finish, &quot;old_brass&quot;,<br />3245, shade, &quot;Mission Satin Etched Flared Shade$35.00&quot;<br />3245, upshade, &quot;Mission Satin Etched Flared Gas-Style Shade$50.00&quot;<br />3245, lights, 8<br />3245, lengths, 36<br />3245, socket, :turnkey<br />3245, vaulted, false<br />}</div></div><br /><br />Asynchronous process at a higher level language can parse this document and run an  update statement that appends to the model embedded document like<br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">db.pba_instance.find({_id:&nbsp; bson}).shade</div></div><br />Can be queried to return the string<br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">db.pba_instance.update({_id:&nbsp; bson} , $set : {shade : &quot;Mission Satin Etched Flared Shade$35.00&quot;, state: &quot;processed&quot;}})<br /></div></div><br />The state is the addition of statemachine which allows the document processing state to follow the document.  It allows built in error handling that happens within the document itself.  MongoDB is a great thing to add features like statemachine for some documents, and a capped collection so those that were old fall off and those that were in error which have likely been fixed by the time the error drops off makes for efficient troubleshooting with built in analytics.<br /><br />For example your state machine might be inspecting the model for the product and validating that all of the required config variables exist and if it detects an anomoly against the model it can set the state to <div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">state: &quot;expecting value for pba_model 25 variables &#91;priority, gu24_bulb, gu24_socket_count&#93;, variables out of range &#91;&#93;&quot;</div></div></div>

					
						<div class="postbody signature"><br /><span class="line">_________________</span><br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">{url: &quot;andrewgauger.com, skype: andrgaug, email: andg@andrewgauger.com, car: 25, fb: facebook.com/DonatoArrighi}</div></div></div>
					
							<br /><br />
							<div class="edited">
    							<p class="gensmall">Last edited by <a href="./memberlist.php?mode=viewprofile&amp;u=2833">andg</a> on Sun Apr 28, 2013 1:14 pm, edited 5 times in total.</p>
    						</div>
						<br clear="all" /><br />
			</td>
		</tr>

		<tr class="row2">

			<td class="postbottom" align="center">Fri Apr 26, 2013 8:00 pm</td>
			<td class="postbottom postbuttons" valign="middle">
				
					<div style="float: right">
					<a href="./report.php?f=45&amp;p=33719"><img src="./styles/diyavalon/imageset/icon_post_report.gif" width="11" height="13" alt="Report this post" title="Report this post" /></a> 
					</div>
				<a href="./memberlist.php?mode=viewprofile&amp;u=2833"><img src="./styles/diyavalon/imageset/en/icon_user_profile.gif" height="13" alt="Profile" title="Profile" /></a> <a href="./ucp.php?i=pm&amp;mode=compose&amp;action=quotepost&amp;p=33719"><img src="./styles/diyavalon/imageset/en/icon_contact_pm.gif" height="13" alt="Send private message" title="Send private message" /></a> <a href="http://andrewgauger.com"><img src="./styles/diyavalon/imageset/icon_contact_www.gif" width="27" height="13" alt="WWW" title="WWW" /></a> 
			</td>
    	
		</tr>
	
	<tr>
		<td class="spacer" colspan="2" height="1"><img src="./styles/diyavalon309/theme/images/spacer.gif" alt="" width="1" height="1" /></td>
	</tr>
	<tr class="row1">

			<td align="center" valign="top" class="row">
				<a name="p33720"></a>
				<div class="postauthor">andg</div>
				<div class="postonline"><img src="./styles/diyavalon/imageset/en/icon_user_online.gif" height="11" alt="Online" title="Online" /></div><div class="posterrank">SOT-223 - Salvaje</div>

				<div class="postdetails">
					<br /><b>Joined:</b> Wed Apr 17, 2013 6:21 pm<br /><b>Posts:</b> 90<br /><b>Location:</b> Portland OREGON
				</div>
				<img src="./styles/diyavalon309/theme/images/spacer.gif" width="120" height="1" alt="" />
			</td>
			<td width="100%" height="25" class="row" valign="top">
				<div style="float: right;"><a href="./posting.php?mode=edit&amp;f=45&amp;p=33720"><img src="./styles/diyavalon/imageset/en/icon_post_edit.gif" height="13" alt="Edit post" title="Edit post" /></a> <a href="./posting.php?mode=quote&amp;f=45&amp;p=33720"><img src="./styles/diyavalon/imageset/en/icon_post_quote.gif" height="13" alt="Reply with quote" title="Reply with quote" /></a></div>
				<div class="postsubject"><a href="./viewtopic.php?p=33720#p33720"><img src="./styles/diyavalon/imageset/icon_topic_latest.gif" width="13" height="9" alt="Post" title="Post" /></a>&nbsp;GridFS for large documents</div>

					

						<div class="postbody">now lets say we want to tie in a shutter from an external web cam.<br />we need to tie in an embedded document within the logger with the image captured from the camera so it gets tied to the sensors<br /><br />BSON id begins with the timestamp so just by logging data we get the timestamp and we can log any type of data, since the nature of binary storage is to save raw data.  GridFS is also available if you intend to save very large dumps.  GridFS would be applicable if you wanted to locally save images of computers under version control.  Replication would come in handy but these machines should have a network control task to limit their bandwith, monitored, reported.<br /><br />binary data storage makes storing any types of documents.  UTF-8 seems to work well for me and   file storage, and sensor data are all well optimized <br /><br />The problem comes in with the overhead of a large database engine on top of small memory footprints.  Transactional data being tied directly to point in time better suited application.  User registrations, orders, inventory with relationships are far better suited.  Mongo facilitates this through <a href="http://docs.mongodb.org/manual/reference/database-references/#dbrefs" class="postlink" rel="nofollow" target="_blank">doc ref</a><br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">user<br />{_id,<br />name: {first: &quot;Andrew&quot;,last: &quot;Gauger&quot;}}<br />order<br />{_id,<br />user: { &quot;$ref&quot; : user, &quot;$id&quot; : BSON}<br /></div></div><br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">db.order.find( { ... }).user.name,first</div></div></div>

					
						<div class="postbody signature"><br /><span class="line">_________________</span><br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">{url: &quot;andrewgauger.com, skype: andrgaug, email: andg@andrewgauger.com, car: 25, fb: facebook.com/DonatoArrighi}</div></div></div>
					
							<br /><br />
							<div class="edited">
    							<p class="gensmall">Last edited by <a href="./memberlist.php?mode=viewprofile&amp;u=2833">andg</a> on Sun Apr 28, 2013 11:38 am, edited 3 times in total.</p>
    						</div>
						<br clear="all" /><br />
			</td>
		</tr>

		<tr class="row1">

			<td class="postbottom" align="center">Fri Apr 26, 2013 8:48 pm</td>
			<td class="postbottom postbuttons" valign="middle">
				
					<div style="float: right">
					<a href="./report.php?f=45&amp;p=33720"><img src="./styles/diyavalon/imageset/icon_post_report.gif" width="11" height="13" alt="Report this post" title="Report this post" /></a> 
					</div>
				<a href="./memberlist.php?mode=viewprofile&amp;u=2833"><img src="./styles/diyavalon/imageset/en/icon_user_profile.gif" height="13" alt="Profile" title="Profile" /></a> <a href="./ucp.php?i=pm&amp;mode=compose&amp;action=quotepost&amp;p=33720"><img src="./styles/diyavalon/imageset/en/icon_contact_pm.gif" height="13" alt="Send private message" title="Send private message" /></a> <a href="http://andrewgauger.com"><img src="./styles/diyavalon/imageset/icon_contact_www.gif" width="27" height="13" alt="WWW" title="WWW" /></a> 
			</td>
    	
		</tr>
	
	<tr>
		<td class="spacer" colspan="2" height="1"><img src="./styles/diyavalon309/theme/images/spacer.gif" alt="" width="1" height="1" /></td>
	</tr>
	<tr class="row2">

			<td align="center" valign="top" class="row">
				<a name="p33721"></a>
				<div class="postauthor">andg</div>
				<div class="postonline"><img src="./styles/diyavalon/imageset/en/icon_user_online.gif" height="11" alt="Online" title="Online" /></div><div class="posterrank">SOT-223 - Salvaje</div>

				<div class="postdetails">
					<br /><b>Joined:</b> Wed Apr 17, 2013 6:21 pm<br /><b>Posts:</b> 90<br /><b>Location:</b> Portland OREGON
				</div>
				<img src="./styles/diyavalon309/theme/images/spacer.gif" width="120" height="1" alt="" />
			</td>
			<td width="100%" height="25" class="row" valign="top">
				<div style="float: right;"><a href="./posting.php?mode=edit&amp;f=45&amp;p=33721"><img src="./styles/diyavalon/imageset/en/icon_post_edit.gif" height="13" alt="Edit post" title="Edit post" /></a> <a href="./posting.php?mode=quote&amp;f=45&amp;p=33721"><img src="./styles/diyavalon/imageset/en/icon_post_quote.gif" height="13" alt="Reply with quote" title="Reply with quote" /></a></div>
				<div class="postsubject"><a href="./viewtopic.php?p=33721#p33721"><img src="./styles/diyavalon/imageset/icon_topic_latest.gif" width="13" height="9" alt="Post" title="Post" /></a>&nbsp;Precision</div>

					

						<div class="postbody">.sensor from laser readings nightly to apollo 1 Gw laser measuring the distance to a trillinth.<br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">{_id,<br />timestamp: 64bit_int,<br />distance: 356,700.83482019383433<br />}</div></div><br />allows very precise point in time to dynamic events<br /><br />Further precision can be created by continually updating thought the millisecond. These inserts can then be averaged.</div>

					
						<div class="postbody signature"><br /><span class="line">_________________</span><br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">{url: &quot;andrewgauger.com, skype: andrgaug, email: andg@andrewgauger.com, car: 25, fb: facebook.com/DonatoArrighi}</div></div></div>
					
							<br /><br />
							<div class="edited">
    							<p class="gensmall">Last edited by <a href="./memberlist.php?mode=viewprofile&amp;u=2833">andg</a> on Sun Apr 28, 2013 11:42 am, edited 5 times in total.</p>
    						</div>
						<br clear="all" /><br />
			</td>
		</tr>

		<tr class="row2">

			<td class="postbottom" align="center">Fri Apr 26, 2013 8:54 pm</td>
			<td class="postbottom postbuttons" valign="middle">
				
					<div style="float: right">
					<a href="./report.php?f=45&amp;p=33721"><img src="./styles/diyavalon/imageset/icon_post_report.gif" width="11" height="13" alt="Report this post" title="Report this post" /></a> 
					</div>
				<a href="./memberlist.php?mode=viewprofile&amp;u=2833"><img src="./styles/diyavalon/imageset/en/icon_user_profile.gif" height="13" alt="Profile" title="Profile" /></a> <a href="./ucp.php?i=pm&amp;mode=compose&amp;action=quotepost&amp;p=33721"><img src="./styles/diyavalon/imageset/en/icon_contact_pm.gif" height="13" alt="Send private message" title="Send private message" /></a> <a href="http://andrewgauger.com"><img src="./styles/diyavalon/imageset/icon_contact_www.gif" width="27" height="13" alt="WWW" title="WWW" /></a> 
			</td>
    	
		</tr>
	
	<tr>
		<td class="spacer" colspan="2" height="1"><img src="./styles/diyavalon309/theme/images/spacer.gif" alt="" width="1" height="1" /></td>
	</tr>
	<tr class="row1">

			<td align="center" valign="top" class="row">
				<a name="p33722"></a>
				<div class="postauthor">andg</div>
				<div class="postonline"><img src="./styles/diyavalon/imageset/en/icon_user_online.gif" height="11" alt="Online" title="Online" /></div><div class="posterrank">SOT-223 - Salvaje</div>

				<div class="postdetails">
					<br /><b>Joined:</b> Wed Apr 17, 2013 6:21 pm<br /><b>Posts:</b> 90<br /><b>Location:</b> Portland OREGON
				</div>
				<img src="./styles/diyavalon309/theme/images/spacer.gif" width="120" height="1" alt="" />
			</td>
			<td width="100%" height="25" class="row" valign="top">
				<div style="float: right;"><a href="./posting.php?mode=edit&amp;f=45&amp;p=33722"><img src="./styles/diyavalon/imageset/en/icon_post_edit.gif" height="13" alt="Edit post" title="Edit post" /></a> <a href="./posting.php?mode=quote&amp;f=45&amp;p=33722"><img src="./styles/diyavalon/imageset/en/icon_post_quote.gif" height="13" alt="Reply with quote" title="Reply with quote" /></a></div>
				<div class="postsubject"><a href="./viewtopic.php?p=33722#p33722"><img src="./styles/diyavalon/imageset/icon_topic_latest.gif" width="13" height="9" alt="Post" title="Post" /></a>&nbsp;Installation distributed computing and timing</div>

					

						<div class="postbody">oscilllation and synch<br />the per second signal is ignored, it is just log data.  It may come in faster or slower depending on CPU utilization<br /><br />basing distributed storage on universal cycle count of an engine rather than per second or per transaction.<br /><br />In distributed environments dedicated database quickly becomes off loaded.  development works best with a local instance.  Mongo is easy to set up and works in Linux and mac very easily <a href="http://docs.mongodb.org/manual/installation/" class="postlink" rel="nofollow" target="_blank">installation by environment</a></div>

					
						<div class="postbody signature"><br /><span class="line">_________________</span><br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">{url: &quot;andrewgauger.com, skype: andrgaug, email: andg@andrewgauger.com, car: 25, fb: facebook.com/DonatoArrighi}</div></div></div>
					
							<br /><br />
							<div class="edited">
    							<p class="gensmall">Last edited by <a href="./memberlist.php?mode=viewprofile&amp;u=2833">andg</a> on Sun Apr 28, 2013 11:43 am, edited 3 times in total.</p>
    						</div>
						<br clear="all" /><br />
			</td>
		</tr>

		<tr class="row1">

			<td class="postbottom" align="center">Fri Apr 26, 2013 8:56 pm</td>
			<td class="postbottom postbuttons" valign="middle">
				
					<div style="float: right">
					<a href="./report.php?f=45&amp;p=33722"><img src="./styles/diyavalon/imageset/icon_post_report.gif" width="11" height="13" alt="Report this post" title="Report this post" /></a> 
					</div>
				<a href="./memberlist.php?mode=viewprofile&amp;u=2833"><img src="./styles/diyavalon/imageset/en/icon_user_profile.gif" height="13" alt="Profile" title="Profile" /></a> <a href="./ucp.php?i=pm&amp;mode=compose&amp;action=quotepost&amp;p=33722"><img src="./styles/diyavalon/imageset/en/icon_contact_pm.gif" height="13" alt="Send private message" title="Send private message" /></a> <a href="http://andrewgauger.com"><img src="./styles/diyavalon/imageset/icon_contact_www.gif" width="27" height="13" alt="WWW" title="WWW" /></a> 
			</td>
    	
		</tr>
	
	<tr>
		<td class="spacer" colspan="2" height="1"><img src="./styles/diyavalon309/theme/images/spacer.gif" alt="" width="1" height="1" /></td>
	</tr>
	<tr class="row2">

			<td align="center" valign="top" class="row">
				<a name="p33723"></a>
				<div class="postauthor">andg</div>
				<div class="postonline"><img src="./styles/diyavalon/imageset/en/icon_user_online.gif" height="11" alt="Online" title="Online" /></div><div class="posterrank">SOT-223 - Salvaje</div>

				<div class="postdetails">
					<br /><b>Joined:</b> Wed Apr 17, 2013 6:21 pm<br /><b>Posts:</b> 90<br /><b>Location:</b> Portland OREGON
				</div>
				<img src="./styles/diyavalon309/theme/images/spacer.gif" width="120" height="1" alt="" />
			</td>
			<td width="100%" height="25" class="row" valign="top">
				<div style="float: right;"><a href="./posting.php?mode=edit&amp;f=45&amp;p=33723"><img src="./styles/diyavalon/imageset/en/icon_post_edit.gif" height="13" alt="Edit post" title="Edit post" /></a> <a href="./posting.php?mode=quote&amp;f=45&amp;p=33723"><img src="./styles/diyavalon/imageset/en/icon_post_quote.gif" height="13" alt="Reply with quote" title="Reply with quote" /></a></div>
				<div class="postsubject"><a href="./viewtopic.php?p=33723#p33723"><img src="./styles/diyavalon/imageset/icon_topic_latest.gif" width="13" height="9" alt="Post" title="Post" /></a>&nbsp;Re: json, CAN</div>

					

						<div class="postbody">allows abstraction of bi tools to analyze pulse of signal that can be tied to signals that include voltages of every sensor providing feedback<br /><br />Analyzing sensors with direct access to query the signals at different intervals within the stroke will allow tuning control to tie back into the forecasted tables.  It is the only way to reliably test.</div>

					
						<div class="postbody signature"><br /><span class="line">_________________</span><br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">{url: &quot;andrewgauger.com, skype: andrgaug, email: andg@andrewgauger.com, car: 25, fb: facebook.com/DonatoArrighi}</div></div></div>
					
							<br /><br />
							<div class="edited">
    							<p class="gensmall">Last edited by <a href="./memberlist.php?mode=viewprofile&amp;u=2833">andg</a> on Sat Apr 27, 2013 8:05 am, edited 1 time in total.</p>
    						</div>
						<br clear="all" /><br />
			</td>
		</tr>

		<tr class="row2">

			<td class="postbottom" align="center">Fri Apr 26, 2013 8:58 pm</td>
			<td class="postbottom postbuttons" valign="middle">
				
					<div style="float: right">
					<a href="./report.php?f=45&amp;p=33723"><img src="./styles/diyavalon/imageset/icon_post_report.gif" width="11" height="13" alt="Report this post" title="Report this post" /></a> 
					</div>
				<a href="./memberlist.php?mode=viewprofile&amp;u=2833"><img src="./styles/diyavalon/imageset/en/icon_user_profile.gif" height="13" alt="Profile" title="Profile" /></a> <a href="./ucp.php?i=pm&amp;mode=compose&amp;action=quotepost&amp;p=33723"><img src="./styles/diyavalon/imageset/en/icon_contact_pm.gif" height="13" alt="Send private message" title="Send private message" /></a> <a href="http://andrewgauger.com"><img src="./styles/diyavalon/imageset/icon_contact_www.gif" width="27" height="13" alt="WWW" title="WWW" /></a> 
			</td>
    	
		</tr>
	
	<tr>
		<td class="spacer" colspan="2" height="1"><img src="./styles/diyavalon309/theme/images/spacer.gif" alt="" width="1" height="1" /></td>
	</tr>
	<tr class="row1">

			<td align="center" valign="top" class="row">
				<a name="p33724"></a>
				<div class="postauthor">andg</div>
				<div class="postonline"><img src="./styles/diyavalon/imageset/en/icon_user_online.gif" height="11" alt="Online" title="Online" /></div><div class="posterrank">SOT-223 - Salvaje</div>

				<div class="postdetails">
					<br /><b>Joined:</b> Wed Apr 17, 2013 6:21 pm<br /><b>Posts:</b> 90<br /><b>Location:</b> Portland OREGON
				</div>
				<img src="./styles/diyavalon309/theme/images/spacer.gif" width="120" height="1" alt="" />
			</td>
			<td width="100%" height="25" class="row" valign="top">
				<div style="float: right;"><a href="./posting.php?mode=edit&amp;f=45&amp;p=33724"><img src="./styles/diyavalon/imageset/en/icon_post_edit.gif" height="13" alt="Edit post" title="Edit post" /></a> <a href="./posting.php?mode=quote&amp;f=45&amp;p=33724"><img src="./styles/diyavalon/imageset/en/icon_post_quote.gif" height="13" alt="Reply with quote" title="Reply with quote" /></a></div>
				<div class="postsubject"><a href="./viewtopic.php?p=33724#p33724"><img src="./styles/diyavalon/imageset/icon_topic_latest.gif" width="13" height="9" alt="Post" title="Post" /></a>&nbsp;Re: json, CAN</div>

					

						<div class="postbody">controllable multi core<br />assign processes to muliple cores based on number of detected cores as indicated by hearbeat of co processors<br /><br />Ever played a ps3? coda <br /><br /><a href="https://www.google.com/search?q=coda+ps3&amp;aq=f&amp;oq=coda+ps3&amp;aqs=chrome.0.57j0.2562j0&amp;sourceid=chrome&amp;ie=UTF-8&quot;" class="postlink" rel="nofollow" target="_blank">google search</a><br />also an example of point in time data.<br /><br />monitoring of an online app is the single greatest ROI example<br /><br />So here is where things get really interesting.  We no longer need an engine mangement system.  The car is autonomous.  The injectors sense that the key is turned since they received their wake up 1x cam signal.  They know to fire and they will begin to do so.<br /><br />Spark is already calculated at the GM DIS interface  this is really the basis of the project.  This is where a 6 and 1 7x signal is translated to 3x which will inform the system of the 3x signal and the injectors will self align since they have their own computer chip in line with the harness that receives the CAN signal.This cpu is responsible for sending the MAP and CHT back to the system.</div>

					
						<div class="postbody signature"><br /><span class="line">_________________</span><br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">{url: &quot;andrewgauger.com, skype: andrgaug, email: andg@andrewgauger.com, car: 25, fb: facebook.com/DonatoArrighi}</div></div></div>
					
							<br /><br />
							<div class="edited">
    							<p class="gensmall">Last edited by <a href="./memberlist.php?mode=viewprofile&amp;u=2833">andg</a> on Sun Apr 28, 2013 10:39 am, edited 2 times in total.</p>
    						</div>
						<br clear="all" /><br />
			</td>
		</tr>

		<tr class="row1">

			<td class="postbottom" align="center">Fri Apr 26, 2013 9:07 pm</td>
			<td class="postbottom postbuttons" valign="middle">
				
					<div style="float: right">
					<a href="./report.php?f=45&amp;p=33724"><img src="./styles/diyavalon/imageset/icon_post_report.gif" width="11" height="13" alt="Report this post" title="Report this post" /></a> 
					</div>
				<a href="./memberlist.php?mode=viewprofile&amp;u=2833"><img src="./styles/diyavalon/imageset/en/icon_user_profile.gif" height="13" alt="Profile" title="Profile" /></a> <a href="./ucp.php?i=pm&amp;mode=compose&amp;action=quotepost&amp;p=33724"><img src="./styles/diyavalon/imageset/en/icon_contact_pm.gif" height="13" alt="Send private message" title="Send private message" /></a> <a href="http://andrewgauger.com"><img src="./styles/diyavalon/imageset/icon_contact_www.gif" width="27" height="13" alt="WWW" title="WWW" /></a> 
			</td>
    	
		</tr>
	
	<tr>
		<td class="spacer" colspan="2" height="1"><img src="./styles/diyavalon309/theme/images/spacer.gif" alt="" width="1" height="1" /></td>
	</tr>
	<tr class="row2">

			<td align="center" valign="top" class="row">
				<a name="p33725"></a>
				<div class="postauthor">andg</div>
				<div class="postonline"><img src="./styles/diyavalon/imageset/en/icon_user_online.gif" height="11" alt="Online" title="Online" /></div><div class="posterrank">SOT-223 - Salvaje</div>

				<div class="postdetails">
					<br /><b>Joined:</b> Wed Apr 17, 2013 6:21 pm<br /><b>Posts:</b> 90<br /><b>Location:</b> Portland OREGON
				</div>
				<img src="./styles/diyavalon309/theme/images/spacer.gif" width="120" height="1" alt="" />
			</td>
			<td width="100%" height="25" class="row" valign="top">
				<div style="float: right;"><a href="./posting.php?mode=edit&amp;f=45&amp;p=33725"><img src="./styles/diyavalon/imageset/en/icon_post_edit.gif" height="13" alt="Edit post" title="Edit post" /></a> <a href="./posting.php?mode=quote&amp;f=45&amp;p=33725"><img src="./styles/diyavalon/imageset/en/icon_post_quote.gif" height="13" alt="Reply with quote" title="Reply with quote" /></a></div>
				<div class="postsubject"><a href="./viewtopic.php?p=33725#p33725"><img src="./styles/diyavalon/imageset/icon_topic_latest.gif" width="13" height="9" alt="Post" title="Post" /></a>&nbsp;Re: json, CAN</div>

					

						<div class="postbody">If multiple cores of co processors and I need to re google incase it was cuda processors.<br />We timestamp whenever the processor is able to process in the most thread safe manner<br /><br />Also designing the system to handle failures by passing through the original voltage back through the harness.  an inline fail back controller exists inline with the existing ecu as backup</div>

					
						<div class="postbody signature"><br /><span class="line">_________________</span><br /><div class="codewrapper"><div class="codetitle"><b>Code:</b></div><div class="codecontent">{url: &quot;andrewgauger.com, skype: andrgaug, email: andg@andrewgauger.com, car: 25, fb: facebook.com/DonatoArrighi}</div></div></div>
					
							<br /><br />
							<div class="edited">
    							<p class="gensmall">Last edited by <a href="./memberlist.php?mode=viewprofile&amp;u=2833">andg</a> on Sat Apr 27, 2013 8:10 am, edited 1 time in total.</p>
    						</div>
						<br clear="all" /><br />
			</td>
		</tr>

		<tr class="row2">

			<td class="postbottom" align="center">Fri Apr 26, 2013 9:08 pm</td>
			<td class="postbottom postbuttons" valign="middle">
				
					<div style="float: right">
					<a href="./report.php?f=45&amp;p=33725"><img src="./styles/diyavalon/imageset/icon_post_report.gif" width="11" height="13" alt="Report this post" title="Report this post" /></a> 
					</div>
				<a href="./memberlist.php?mode=viewprofile&amp;u=2833"><img src="./styles/diyavalon/imageset/en/icon_user_profile.gif" height="13" alt="Profile" title="Profile" /></a> <a href="./ucp.php?i=pm&amp;mode=compose&amp;action=quotepost&amp;p=33725"><img src="./styles/diyavalon/imageset/en/icon_contact_pm.gif" height="13" alt="Send private message" title="Send private message" /></a> <a href="http://andrewgauger.com"><img src="./styles/diyavalon/imageset/icon_contact_www.gif" width="27" height="13" alt="WWW" title="WWW" /></a> 
			</td>
    	
		</tr>
	
	<tr>
		<td class="cat" colspan="2" align="center"><form name="viewtopic" method="post" action="./viewtopic.php?f=45&amp;t=2110"><span class="gensmall">Display posts from previous:</span> <select name="st" id="st"><option value="0" selected="selected">All posts</option><option value="1">1 day</option><option value="7">7 days</option><option value="14">2 weeks</option><option value="30">1 month</option><option value="90">3 months</option><option value="180">6 months</option><option value="365">1 year</option></select>&nbsp;<span class="gensmall">Sort by</span> <select name="sk" id="sk"><option value="a">Author</option><option value="t" selected="selected">Post time</option><option value="s">Subject</option></select> <select name="sd" id="sd"><option value="a" selected="selected">Ascending</option><option value="d">Descending</option></select>&nbsp;<input class="btnlite" type="submit" value="Go" name="sort" /></form></td>
	</tr>
	
	</table>
	<div class="block-end-left"><div class="block-end-right"></div></div></div>

	<table width="100%" cellspacing="1">
	<tr>
		
			<td align="left" valign="middle" nowrap="nowrap">
				<a href="./posting.php?mode=reply&amp;f=45&amp;t=2110"><img src="./styles/diyavalon/imageset/en/button_topic_reply.gif" height="22" alt="Reply to topic" title="Reply to topic" /></a>&nbsp;<a href="javascript:void(0);" onclick="var qr = document.getElementById('ca-qr'); qr.style.display = (qr.style.display == 'none') ? '' : 'none'; return false;"><img src="./styles/diyavalon/imageset/en/quick_reply.gif" /></a>
			</td>
		
			<td class="nav" valign="middle" nowrap="nowrap">&nbsp;Page <strong>1</strong> of <strong>5</strong><br /></td>
			<td class="gensmall" nowrap="nowrap">&nbsp;[ 43 posts ]&nbsp;</td>
			<td class="gensmall" width="100%" align="right" nowrap="nowrap"><b><a href="#" onclick="jumpto(); return false;" title="Click to jump to page…">Go to page</a> <strong>1</strong><span class="page-sep">, </span><a href="./viewtopic.php?f=45&amp;t=2110&amp;start=10">2</a><span class="page-sep">, </span><a href="./viewtopic.php?f=45&amp;t=2110&amp;start=20">3</a><span class="page-sep">, </span><a href="./viewtopic.php?f=45&amp;t=2110&amp;start=30">4</a><span class="page-sep">, </span><a href="./viewtopic.php?f=45&amp;t=2110&amp;start=40">5</a> &nbsp;<a href="./viewtopic.php?f=45&amp;t=2110&amp;start=10">Next</a></b></td>
		
	</tr>
	</table>

</div>

<div id="ca-qr" style="display: none;">
<form method="post" action="./posting.php?mode=reply&amp;f=45&amp;t=2110">
<div class="block-start">
<div class="cap-div"><div class="cap-left"><div class="cap-right">Quick Reply&nbsp;</div></div></div>
<table class="tablebg" width="100%" cellspacing="0">
		<tr>
			<td class="row1" width="22%"><b class="genmed">Subject:</b></td>
			<td  class="row2" width="78%"><input class="post" style="width:450px" type="text" name="subject" size="45" maxlength="64" tabindex="2" value="Re: json, CAN" /></td>
		</tr>
		<tr>
			<td class="row1" width="22%"><b class="genmed">Message:</b></td>
			<td class="row2" valign="top" align="left" width="78%"><textarea name="message" rows="7" cols="76" tabindex="3"  style="width: 98%;"></textarea> </td>
		</tr>
		<tr>
			<td class="cat" colspan="2" align="center">
				<input class="btnmain" type="submit" accesskey="s" tabindex="6" name="post" value="Submit" />&nbsp;
				<input class="btnlite" type="submit" accesskey="f" tabindex="7" name="full_editor" value="Full Editor" />

				<input type="hidden" name="creation_time" value="1367199708" />
<input type="hidden" name="form_token" value="729a2df440f584fcc58fa164c5d46770a058e430" />

				<input type="hidden" name="topic_cur_post_id" value="33762" />
<input type="hidden" name="lastclick" value="1367199708" />
<input type="hidden" name="topic_id" value="2110" />
<input type="hidden" name="forum_id" value="45" />
<input type="hidden" name="attach_sig" value="1" />

			</td>
		</tr>
</table>