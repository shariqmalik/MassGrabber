# MassGrabber
<p>MassGrabber is an advanced form of my previous script named <a href="https://raw.githubusercontent.com/shariqmalik/AdminGrabber">AdminGrabber</a> The changes are it takes both sites list and wordlist to check all provided urls one by one and save results to a .txt file</p>
**Requirements**<br/>
	<li>Python27</li><br/>
**Tested on**<br/>
	<li> Windows 7/8/10 </li>
	<li> Ubuntu 14.04.4 LTS </li><br/>
**Installation**
<p>You can download the latest version of MassGrabber by cloning the GitHub repository:</p>
<pre><code>git clone https://github.com/shariqmalik/MassGrabber.git</code></pre>
**Useage**<br/>
<pre><code>$python massgrab.py</code></pre>
**Load sites list and wordlist**
<pre><code>
user@box:~$python massgrab.py
                          ___            _     _
  /\/\   __ _ ___ ___   / _ \ _ __ __ _| |__ | |__   ___ _ __
 /    \ / _` / __/ __| / /_\// '__/ _` | '_ \| '_ \ / _ \ '__|
/ /\/\ \ (_| \__ \__ \/ /_\ \| | | (_| | |_) | |_) |  __/ |
\/    \/\__,_|___/___/\_____/|_|  \__,_|_.__/|_.__/ \___|_|

        Author: <a href="http://facebook.com/shariqmalik07">Shariq Malik</a>

Enter Sites List: sites.txt
Enter WordList: testlist.txt
</code></pre>
**Script will load list and show results**
<pre><code>
---------------------------------------------------------------------
[Loading]      : Loading Panels & Sites..
[Sites]        : 4 Sites Loaded..
[Panels]       : 4 Panels Loaded..
[Using Sites]  : 4/4 Sites being used (0 duplicates)..
[Using Panels] : 3/4 Panels being used (1 duplicates)..
---------------------------------------------------------------------
[Connecting] : http://google.com...
[Connected]  : http://google.com is connected
[Checking 1/4] : Checking http://google.com

[NO PANEL] : No Panel Found..
---------------------------------------------------------------------
[Connecting] : http://racetech.co.in...
[Connected]  : http://racetech.co.in is connected
[Checking 2/4] : Checking http://racetech.co.in

[OK] : http://racetech.co.in/control
---------------------------------------------------------------------
[Connecting] : http://sdfsdf.co.in
[Failed] : http://sdfsdf.co.in is offline or invalid URL

[NO PANEL] : No Panel Found..
---------------------------------------------------------------------
</code></pre>
**And save results to a *shariq.txt* file as well**
<pre><code>
---------------------------------------------------------------------
[Connecting] : http://youshine.in...
[Connected]  : http://youshine.in is connected
[Checking 4/4] : Checking http://youshine.in

[OK] : http://youshine.in/control
[OK] : http://youshine.in/admin
[OK] : http://youshine.in/admainistrator
---------------------------------------------------------------------
[Task Complete] : Results are saved into shariq.txt

</code></pre>
**Note**
<p>This is just for educational purposes I'll not responsible of any harm!<p>
