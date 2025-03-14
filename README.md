# Client Account Login History Dashboard
This Splunk dashboard provides an overview of client authentication activity across various systems, helping IT security and support teams monitor login history, device usage, and authentication events.

# Features:
Last Machine Logged Into – Displays the most recent endpoint accessed by the user.
PC Logins – Tracks Windows Sign-In events with timestamps, device identifiers, and IP addresses.
GlobalProtect Logins – Logs VPN authentication attempts, showing authentication results and reasons for failures.
Account Locks and Password Resets – Monitors Active Directory account lockouts, unlocks, and password resets, including self-service password resets.
Intune Device Enrollment – Lists devices enrolled in Intune for the client, including operating system, device category, and last sync time.

# Data Sources:
The dashboard queries multiple Splunk indexes and sources for authentication events, AD activity, and device management records, sanitised in this version as INDEX1, INDEX2, etc., and SOURCE1, SOURCE2, etc.

# Use Case:
This dashboard is designed for IT service desks, security analysts, and system administrators who need quick insights into user authentication patterns, device logins, and potential security incidents.


