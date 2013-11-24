ISU Fall 2013 CDC Anomalies===========================This repository contains collection of the Iowa State University Fall 2013 Cyber Defense Competition anomalies and solutions where applicable.  The ISU CDC anomalies are optional challenges that may be completed by participating teams within the allocated challenge time frame to earn additional points during the competition.  Some anomalies are intentionally designed to provoke teams into performing an unsecure operation that potentially compromises the security of their network.  Other anomalies are simply technical or non-technical challenges designed to engage the participant during the competition.These anomalies were created for the Iowa State University Fall 2013 Cyber Defense Competition held on September 21, 2013.  They are being released under the MIT License in the hopes that they can be reused or in some way aid in learning or promotion of computer security topics.  Aside from the `King of the Hill` anomaly, which contained a vulnerable virtual machine for partipants to attack (not released in this repository), Ben Holland created these anomalies.## ParticipationThe ISU Fall 2013 CDC had 25 teams register to compete in the Fall 2013 Cyber Defense Competition with varying team attendance on competition day.  As a result a few teams disbanded before competition day leaving 20 participating teams during the competition.

<img src="./Results/Team_Attendence.png" alt="Team Attendence" style="width:100%;"/>

## Anomalies
<script type="text/javascript" src="https://www.google.com/jsapi?autoload={'modules':[{'name':'visualization',
       'version':'1','packages':['timeline']}]}"></script>
<script type="text/javascript">
google.setOnLoadCallback(drawChart);

function drawChart() {
  var container = document.getElementById('timeline');

  var chart = new google.visualization.Timeline(container);

  var dataTable = new google.visualization.DataTable();

  dataTable.addColumn({ type: 'string', id: 'Event' });
  dataTable.addColumn({ type: 'string', id: 'Name' });
  dataTable.addColumn({ type: 'date', id: 'Start' });
  dataTable.addColumn({ type: 'date', id: 'End' });

  // date format => Date(year, month, day, hours, minutes, seconds, milliseconds)
  dataTable.addRows([
    [ 'Cyber Defense Competition', 'Cyber Defense Competition', new Date(2013, 9, 21, 8, 0), new Date(2013, 9, 21, 16, 30) ],
    [ 'Anomaly', 'Initial Survey', new Date(2013, 9, 21, 8, 0), new Date(2013, 9, 21, 10, 0) ],
    [ 'Anomaly', 'Employee On-boarding', new Date(2013, 9, 21, 8, 30), new Date(2013, 9, 21, 9, 0) ],
    [ 'Anomaly', 'Crypto 1 - The Cryptonomicon', new Date(2013, 9, 21, 9, 0), new Date(2013, 9, 21, 10, 0) ],
    [ 'Anomaly', 'Add FTP Service', new Date(2013, 9, 21, 9, 0), new Date(2013, 9, 21, 12, 0) ],
    [ 'Anomaly', 'Forensics Analysis of File Types', new Date(2013, 9, 21, 9, 0), new Date(2013, 9, 21, 15, 30) ],
    [ 'Anomaly', 'Dumpster Dive', new Date(2013, 9, 21, 9, 25), new Date(2013, 9, 21, 11, 8) ],
    [ 'Anomaly', 'King Of The Hill', new Date(2013, 9, 21, 9, 30), new Date(2013, 9, 21, 16, 30) ],
    [ 'Anomaly', 'Charles Got Fired', new Date(2013, 9, 21, 10, 0), new Date(2013, 9, 21, 10, 20) ],
    [ 'Anomaly', 'Crypto 2 - The One Time Pad', new Date(2013, 9, 21, 10, 0), new Date(2013, 9, 21, 11, 0) ],
    [ 'Anomaly', 'Oddball', new Date(2013, 9, 21, 10, 0), new Date(2013, 9, 21, 11, 0) ],
    [ 'Anomaly', 'FBI Raid', new Date(2013, 9, 21, 11, 0), new Date(2013, 9, 21, 11, 30) ],
    [ 'Anomaly', 'Harden CVE', new Date(2013, 9, 21, 11, 0), new Date(2013, 9, 21, 15, 11) ],
    [ 'Anomaly', 'Decompile and Analyze Android Application', new Date(2013, 9, 21, 11, 40), new Date(2013, 9, 21, 15, 0) ],
    [ 'Anomaly', 'Restore Services After FBI Raid', new Date(2013, 9, 21, 11, 45), new Date(2013, 9, 21, 12, 15) ],
    [ 'Anomaly', 'Promotion Day', new Date(2013, 9, 21, 12, 40), new Date(2013, 9, 21, 13, 0) ],
    [ 'Anomaly', 'Opensource Web App Again', new Date(2013, 9, 21, 13, 30), new Date(2013, 9, 21, 14, 30) ],
    [ 'Anomaly', 'Crack Password Hashes', new Date(2013, 9, 21, 13, 30), new Date(2013, 9, 21, 15, 30) ],
    [ 'Anomaly', 'Find the Rogue AP', new Date(2013, 9, 21, 14, 30), new Date(2013, 9, 21, 16, 15) ]]);

  var options = {
     timeline: { colorByRowLabel: true },
     colors: ['#cbb69d', '#8d8']
  };

  chart.draw(dataTable, options);
}
</script>
<div id="timeline" style="width: 100%; height: 400px;"></div>