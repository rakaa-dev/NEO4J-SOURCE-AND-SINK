# NEO4J-SOURCE-AND-SINK


Create label in neo4j
merge (ts:TestSource {id: 444}) SET ts.name="test 34", ts.timestamp = apoc.date.currentTimestamp();
