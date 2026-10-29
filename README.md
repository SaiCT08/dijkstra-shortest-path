# Dijkstra Shortest Path

A Java implementation of Dijkstra's algorithm that finds the shortest route between hubs on a 2D map.

## How it works

- Loads hubs (name and x, y coordinates) and their connections from a data file
- Edge weights are the straight-line (Euclidean) distance between connected hubs
- Runs Dijkstra's algorithm from a chosen starting hub, repeatedly visiting the closest unvisited hub and updating its neighbors' distances and paths
- Returns the shortest path from the start to any destination hub

## Files

- `Hub.java`: a location with coordinates, current shortest distance, and path
- `HubMap.java`: loads the map and runs Dijkstra's algorithm
- `HubFrame.java`, `GetPaths.java`: Swing GUI for choosing hubs and showing paths
- `HubMapRunner.java`: launches the GUI

## Built with

Java, Swing
