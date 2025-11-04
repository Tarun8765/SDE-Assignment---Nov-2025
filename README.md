SDE Assignment – Merge Discontinuous Time Ranges
📄 Problem Statement

You are given an array of time ranges representing when a system was active.
Each range is [start, end) where start and end are UNIX timestamps in milliseconds.
The goal is to merge all overlapping or nearly continuous time ranges into sorted, non-overlapping intervals.

If the gap between two ranges is smaller than or equal to a threshold, they should be treated as continuous and merged.
