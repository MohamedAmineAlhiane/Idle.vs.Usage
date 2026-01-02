# Idle vs Usage

## Hypotheses
Before performing any observation, the following expectations were defined:

- When the device is idle, network traffic should be minimal and sporadic
- Idle traffic is expected to consist mainly of background services and periodic system checks
- When the device is actively used, traffic volume and frequency should increase noticeably
- Active usage should result in more consistent and immediate responses from the gateway

## Observations
During the observation period, the device exhibited different network behavior depending on its state.

When idle, network traffic appeared infrequent and sporadic, with noticeable gaps between packets.  
When actively used, traffic volume increased significantly, showing continuous communication and faster response timing.

## Analysis
The observed behavior aligns with the initial hypotheses.

Idle-state traffic reflects normal background activity and does not indicate abnormal behavior.  
In contrast, active usage generates a predictable increase in traffic driven by user interaction, resulting in higher packet frequency and reduced response delays.

This comparison highlights the importance of understanding baseline behavior before assessing potential anomalies in network traffic.

## Conclusion
This project demonstrated how device state directly affects network traffic patterns.  
Understanding the difference between idle and active behavior is essential for building accurate baselines in defensive network analysis.

## Ethical Notice
All observations were conducted on a privately owned network using personal devices.  
The project focused exclusively on passive observation for educational purposes.
