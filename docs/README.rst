***************
Mattermost Tips
***************

=====
Where
=====
Updates from production data processing scripts are posted to the `RS Data Processing <https://chat.avo.alaska.edu/avo/channels/rs-data-processing>`_ channel on mattermost.
Development systems post their updates to the `RS Processing Test <https://chat.avo.alaska.edu/avo/channels/rs-processing-test>`_ channel on mattermost.
Everyone is welcome to add these channels, but they're both listed as private to keep down clutter in the main channel list. Let Tom know if you need help accessing the channel.


===
Who
===
Each production system processing data has its own user id.

+---------+-----------+------------+---------------------------+
| user id | Location  | Contact    | Tasks                     |
+=========+===========+============+===========================+
| avors1  | Anchorage | Tom Parker | VIIRS retrieval from GINA |
+---------+-----------+------------+---------------------------+

===
How
===

Processing Order
----------------
New data are processed by decending orbit number. Within each orbit, granules are processed in chronological order.

To maximize throughput, multiple files are downloaded concurently. This can make it look like files are downloaded out of order as the download of larger files takes longer to complete.

Timestamps and Delays
---------------------
transfer delay
process delay

================
Mattermost Usage
================

There's too many channels
-------------------------
Create a list of just your frequently used channels. Clicking the star near the channel title will place that channel in a favorites group at the top of the channel list.

Can I stop