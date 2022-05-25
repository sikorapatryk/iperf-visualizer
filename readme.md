# iperf-visualizer

This is a small web application, that will let you visualize json-files created by calling
```bash
iperf3 -c <server-ip> -J --logfile <filename.json>
```

<img src="/images/screen0.png">
<img src="/images/screen1.png">

Chart.js is used to show all the measurements from your network test as a graph, for easier analysis.

Current status:
- 
* Basic json file upload and display working (multiple files for multiple datasets within one graph possible)
* Adding of more than one graph working
* basic styling (preliminary)
* no error handling yet
