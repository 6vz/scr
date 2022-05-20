---
order: 10
label: Train Priority
---
Train priority in SCR works as follows: Headcode > Lateness > Operator.

This means that headcode priority is looked at first. If the priority conflict cannot be resolved with the
headcodes, you move onto lateness priority. Finally, if lateness does not resolve the conflict, you look
at the operator priority.

Headcodes have four figures and identify a train (and its service). The headcode takes the format of
#X##, or number, letter, number, number. For headcode priority, we are concerned about the first
number. Headcode priority is as follows: 9 > 1 > 2 > 3.

Lateness priority is simple. The later train receives priority.

Operator priority is as follows: Express > AirLink > Connect > WaterLine.

Priority only applies if a train is arriving while another train in your platform group is still loading. If the
train that has already arrived is finished loading and ready to leave the station, you can dispatch it first
regardless of priority.