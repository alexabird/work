curl -X POST -k "https://localhost:8993/services/replication/sync/trigger" -d '{"lastReplicationEvent": 0, "eventId": "101", "targetNodeId": "heavy_node_one"}'
