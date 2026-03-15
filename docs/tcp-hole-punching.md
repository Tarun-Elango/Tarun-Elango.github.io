# TCP Hole Punching

TCP hole punching is a technique used to establish direct connections between peers behind NAT.

## Problem

Two peers behind NAT cannot directly connect.

## Solution

1. Both peers connect to a rendezvous server
2. The server exchanges their addresses
3. Both attempt simultaneous connections

This allows NAT mappings to open on both sides.