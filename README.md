# Altern8
A script that converts zig-zag flight plans generated in Mission Planner to the Altern8 flight pattern. 

This flight pattern aims to solve a problem of the sliding racetrack flight pattern, where adjacent transects point in the same direction instead of alternating. If there is a strong tailwind, this can cause entire scan regions to have low coverage. The Altern8 flight pattern solves this problem by flying a sliding "S". This alternates the direction of adjacent transects, but requires that flight paths be an integer multiple of 8 (+1). The script offers the option of adding transects to reach a multiple of 8 or of extending the leftover zigzag transects (to leave more room for turning).

The script can be integrated into a context menu using a tool such as the freeware Default Programs Editor