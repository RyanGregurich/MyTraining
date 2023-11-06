<p style='margin-top:3.0pt;margin-right:0in;margin-bottom:0in;margin-left:42.55pt;font-size:27px;font-family:"Arial",sans-serif;font-weight:bold;text-decoration:underline;'>12&nbsp;The&nbsp;Life&nbsp;of&nbsp;a&nbsp;Packet&nbsp;-&nbsp;Lab&nbsp;Exercise</p>
<p style='margin:0in;font-size:16px;font-family:"Arial MT",sans-serif;'><strong><span style='font-family:"Arial",sans-serif;'>&nbsp;</span></strong></p>
<p style='margin:0in;font-size:16px;font-family:"Arial MT",sans-serif;margin-left:5.0pt;'>This&nbsp;lab&nbsp;explores&nbsp;DNS&nbsp;configuration&nbsp;on&nbsp;Cisco&nbsp;routers&nbsp;and&nbsp;the&nbsp;ARP&nbsp;cache.</p>
<p style='margin:0in;font-size:16px;font-family:"Arial MT",sans-serif;margin-top:13.75pt;'>&nbsp;</p>
<h1 style='margin-top:0in;margin-right:0in;margin-bottom:0in;margin-left:1.0pt;text-align:center;font-size:21px;font-family:"Arial",sans-serif;text-decoration:underline;'>Lab Topology</h1>
<blockquote class="imgur-embed-pub" lang="en" data-id="a/Uzne7RB"><a href="//imgur.com/a/Uzne7RB"></a></blockquote>
<script async="" src="//s.imgur.com/min/embed.js" charset="utf-8"></script>
<p><br></p>
<p style="margin:0in;font-size:16px;font-family:&quot;Arial MT&quot;,sans-serif;"></p>
<p style='margin:0in;font-size:15px;font-family:"Arial MT",sans-serif;margin-top:.05pt;margin-right:.05pt;margin-bottom:.0001pt;margin-left:1.0pt;text-align:center;'><img src="https://i.imgur.com/WWg6iiK.jpg" alt="" width="400"><br></p>
<p style='margin:0in;font-size:15px;font-family:"Arial MT",sans-serif;margin-top:.05pt;margin-right:.05pt;margin-bottom:.0001pt;margin-left:1.0pt;text-align:center;'><strong><u><span style='font-size:21px;font-family:"Arial",sans-serif;'>Load the Startup Configurations</span></u></strong></p>
<p style='margin:0in;font-size:16px;font-family:"Arial MT",sans-serif;margin-top:4.65pt;'><strong><span style='font-family:"Arial",sans-serif;'>&nbsp;</span></strong></p>
<p style='margin:0in;font-size:16px;font-family:"Arial MT",sans-serif;margin-left:5.0pt;'>Open&nbsp;the&nbsp;&rsquo;12&nbsp;The&nbsp;Life&nbsp;of&nbsp;a&nbsp;Packet.pkt&rsquo;&nbsp;file&nbsp;in&nbsp;Packet&nbsp;Tracer&nbsp;to&nbsp;load&nbsp;the&nbsp;lab.</p>
<p style='margin:0in;font-size:16px;font-family:"Arial MT",sans-serif;'>&nbsp;</p>
<p style='margin:0in;font-size:16px;font-family:"Arial MT",sans-serif;margin-top:0in;margin-right:6.95pt;margin-bottom:.0001pt;margin-left:5.0pt;'>This&nbsp;configures&nbsp;the&nbsp;lab&nbsp;topology&nbsp;as&nbsp;shown&nbsp;above&nbsp;and&nbsp;adds&nbsp;static&nbsp;routes&nbsp;between R1 and R3.<span style='font-size:15px;font-family:"Arial MT",sans-serif;'><br>&nbsp;</span></p>
<h1 style='margin-top:4.0pt;margin-right:0in;margin-bottom:0in;margin-left:1.0pt;text-align:center;font-size:21px;font-family:"Arial",sans-serif;text-decoration:underline;'>Configure&nbsp;the&nbsp;Routers&nbsp;as&nbsp;DNS&nbsp;Clients</h1>
<p style='margin:0in;font-size:16px;font-family:"Arial MT",sans-serif;margin-top:4.6pt;'><strong><span style='font-family:"Arial",sans-serif;'>&nbsp;</span></strong></p>
<p style='margin:0in;font-size:15px;font-family:"Arial MT",sans-serif;margin-top:0in;margin-right:4.65pt;margin-bottom:.0001pt;margin-left:5.0pt;'><strong><em><span style='font-size:16px;font-family:"Arial",sans-serif;'>Note that routers cannot be DNS servers in Packet Tracer (it does not support&nbsp;the&nbsp;&lsquo;ip&nbsp;dns&nbsp;server&rsquo;&nbsp;command)&nbsp;so&nbsp;we&nbsp;are&nbsp;using&nbsp;a&nbsp;Packet&nbsp;Tracer server device as the DNS server.</span></em></strong></p>
<p style='margin:0in;font-size:16px;font-family:"Arial MT",sans-serif;'><strong><em><span style='font-family:"Arial",sans-serif;'>&nbsp;</span></em></strong></p>
<p style='margin:0in;font-size:16px;font-family:"Arial MT",sans-serif;margin-top:0in;margin-right:4.65pt;margin-bottom:.0001pt;margin-left:5.0pt;'>The&nbsp;host&nbsp;with&nbsp;IP&nbsp;address&nbsp;10.10.10.10&nbsp;has&nbsp;been&nbsp;configured&nbsp;as&nbsp;a&nbsp;DNS&nbsp;server&nbsp;and is able to resolve DNS requests for &lsquo;R1&rsquo;, &lsquo;R2&rsquo; and &lsquo;R3&rsquo;.</p>
<p style='margin:0in;font-size:16px;font-family:"Arial MT",sans-serif;margin-left:5.0pt;'>A&nbsp;domain&nbsp;name&nbsp;is&nbsp;not&nbsp;in&nbsp;use.</p>
<p style='margin:0in;font-size:16px;font-family:"Arial MT",sans-serif;'>&nbsp;</p>
<div style='margin:0in;font-size:15px;font-family:"Arial MT",sans-serif;'>
    <ol style="margin-bottom:0in;list-style-type: undefined;">
        <li style='margin:0in;font-size:15px;font-family:"Arial MT",sans-serif;'><span style="font-size:16px;">Configure&nbsp;R1,&nbsp;R2&nbsp;and&nbsp;R3&nbsp;to&nbsp;use&nbsp;10.10.10.10&nbsp;as&nbsp;their&nbsp;DNS&nbsp;server.&nbsp;You&nbsp;do not need to configure a domain-name or domain-list.</span></li>
    </ol>
</div>
<p style='margin:0in;font-size:16px;font-family:"Arial MT",sans-serif;'>&nbsp;</p>
<div style='margin:0in;font-size:15px;font-family:"Arial MT",sans-serif;'>
    <ol style="margin-bottom:0in;list-style-type: undefined;">
        <li style='margin:0in;font-size:15px;font-family:"Arial MT",sans-serif;'><span style="font-size:16px;">Verify&nbsp;that&nbsp;you&nbsp;can&nbsp;ping&nbsp;R2&nbsp;and&nbsp;R3&nbsp;from&nbsp;R1&nbsp;using&nbsp;their&nbsp;hostnames&nbsp;&lsquo;R2&rsquo; and &lsquo;R3&rsquo; (it&nbsp;may take some time for the DNS server&nbsp;to resolve the DNS request).</span></li>
    </ol>
</div>
<p style='margin:0in;font-size:16px;font-family:"Arial MT",sans-serif;'>&nbsp;</p>
<div style='margin:0in;font-size:15px;font-family:"Arial MT",sans-serif;'>
    <ol style="margin-bottom:0in;list-style-type: undefined;">
        <li style='margin:0in;font-size:15px;font-family:"Arial MT",sans-serif;'><span style="font-size:16px;">Verify&nbsp;that&nbsp;you&nbsp;can&nbsp;ping&nbsp;R1&nbsp;and&nbsp;R2&nbsp;from&nbsp;R3&nbsp;using&nbsp;their&nbsp;hostnames&nbsp;&lsquo;R1&rsquo; and &lsquo;R2&rsquo;.</span></li>
    </ol>
</div>
<h1 style='margin-top:13.8pt;margin-right:0in;margin-bottom:0in;margin-left:1.0pt;text-align:center;font-size:21px;font-family:"Arial",sans-serif;text-decoration:underline;'>Examine&nbsp;the&nbsp;ARP&nbsp;Cache&nbsp;on&nbsp;the&nbsp;Routers</h1>
<p style='margin:0in;font-size:16px;font-family:"Arial MT",sans-serif;'><strong><span style='font-family:"Arial",sans-serif;'>&nbsp;</span></strong></p>
<div style='margin:0in;font-size:15px;font-family:"Arial MT",sans-serif;'>
    <ol style="margin-bottom:0in;list-style-type: undefined;">
        <li style='margin:0in;font-size:15px;font-family:"Arial MT",sans-serif;'><span style="font-size:16px;">Do&nbsp;you&nbsp;expect&nbsp;to&nbsp;see&nbsp;an&nbsp;entry&nbsp;for&nbsp;R3&nbsp;in&nbsp;the&nbsp;ARP&nbsp;cache&nbsp;of&nbsp;R1?&nbsp;Why&nbsp;or why not?</span></li>
    </ol>
</div>
<p style='margin:0in;font-size:16px;font-family:"Arial MT",sans-serif;'>&nbsp;</p>
<div style='margin:0in;font-size:15px;font-family:"Arial MT",sans-serif;'>
    <ol style="margin-bottom:0in;list-style-type: undefined;margin-left:30.9px;">
        <li style='margin:0in;font-size:15px;font-family:"Arial MT",sans-serif;'><span style="font-size:16px;">Verify the ARP cache on R1, R2 and R3. What do you see?</span></li>
    </ol>
</div>
<p></p>
