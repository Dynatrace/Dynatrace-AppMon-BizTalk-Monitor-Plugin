<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>Overview</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
    <meta content="Scroll Wiki Publisher" name="generator"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
    <link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
    <link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
<body>
                <h1>Overview</h1>
    <p>
            <img src="images_community/download/attachments/21823516/icon.png" alt="images_community/download/attachments/21823516/icon.png" class="confluence-embedded-image" />
            </p>
    <p>
Monitors BizTalk Host Instance specific Windows Performance Counters for a specific BizTalk Host Instance. Extends the dynaTrace Windows Performance Counter Monitor.    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<strong class=" ">BizTalk Monitor Plugin</strong>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Plug-In Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
1.0.1    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Compatible with    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
dynaTrace 3.x, 5.6 (verified)    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="http://www.mcg-software.dk/">MCG Systems</a> (Rasmus Toelhoej - rtoelhoej@mcg-systems.dk)    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
License    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Support    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="https://community/display/DL/Support+Levels#SupportLevels-Community">Not Supported </a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Downloads    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_38895636_1_com.dynatrace.diagnostics.plugin.BizTalkPerfMon_1.0.1.jar">BizTalk Monitor Plugin 1.0.1 provided by MCG Systems</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Key benefits    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Makes it easier to subscribe to all relevant BizTalk Windows Performance Counters    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Key features    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Captures a list of windows performance counters specific to a BizTalk Host Instance    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Technical overview    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
The monitor is configured for a specific BizTalk Host Instance Name. The monitor then queries the following performance counters from the BizTalk:MessageAgent object for the specified instance:    </p>
<ul class=" "><li class=" ">    <p>
High database session    </p>
</li><li class=" ">    <p>
High database size    </p>
</li><li class=" ">    <p>
High in-process message count    </p>
</li><li class=" ">    <p>
High message delivery rate    </p>
</li><li class=" ">    <p>
High message publishing rate    </p>
</li><li class=" ">    <p>
High process memory    </p>
</li><li class=" ">    <p>
High system memory    </p>
</li><li class=" ">    <p>
High thread count    </p>
</li><li class=" ">    <p>
Message delivery incoming rate    </p>
</li><li class=" ">    <p>
Message delivery outgoing rate    </p>
</li><li class=" ">    <p>
Message delivery delay (ms)    </p>
</li><li class=" ">    <p>
Message delivery throttling state    </p>
</li><li class=" ">    <p>
Message delivery throttling state duration    </p>
</li><li class=" ">    <p>
Message delivery throttling user override    </p>
</li><li class=" ">    <p>
Message publishing incoming rate    </p>
</li><li class=" ">    <p>
Message publishing outgoing rate    </p>
</li><li class=" ">    <p>
Message publishing delay (ms)    </p>
</li><li class=" ">    <p>
Message publishing throttling state    </p>
</li><li class=" ">    <p>
Message publishing throttling state duration    </p>
</li><li class=" ">    <p>
Message publishing throttling user override    </p>
</li><li class=" ">    <p>
FILE, SQL, SOAP and HTTP Adapter counters for sent/received messages    </p>
</li></ul>            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Install Description    </p>
            </td>
                <td rowspan="1" colspan="1">
    <ul class=" "><li class=" ">    <p>
Import the plugin on your dynaTrace Server    </p>
</li><li class=" ">    <p>
Create a Monitor in your System Profile and configure all required monitor properties    </p>
</li><li class=" ">    <p>
Add the measures to your Dashboard and monitor these values while running BizTalk    </p>
</li></ul>            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Screenshots    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Showing a dashboard with some of the monitor's measures and the configuration dialogs:    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/21823516/icon.png" alt="images_community/download/attachments/21823516/icon.png" class="" />
            </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/21823516/BizTalkMonitorConfiguration.JPG" alt="images_community/download/attachments/21823516/BizTalkMonitorConfiguration.JPG" class="" />
            </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/21823516/PerformanceDashboard.JPG" alt="images_community/download/attachments/21823516/PerformanceDashboard.JPG" class="" />
            </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
        <p>
BizTalk Monitor Configuration    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Dashboard showing BizTalk Monitor Values    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Known Problems    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>
