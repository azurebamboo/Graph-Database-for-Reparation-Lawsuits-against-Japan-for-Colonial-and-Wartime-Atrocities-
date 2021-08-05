This is an ongoing project to digitize reparation lawsuits against Japanese colonial and wartime atrocities (most famously the "comfort women" system and Nanjing Massacre) into a graph database. Information about the lawsuits is taken from publicly available sources such as the 日本戦後補償裁判総覧 (http://justice.skr.jp/souran/souran-jp-web.htm), digitized, processed, and exported as cypher codes executable by graph database management or processing systems such as Neo4j. The database seeks to not only preserve historical materials produced in this transnational movement but also aid academic research and teaching of it. 

The all-plain.cypher file can be loaded into graph database systems like Neo4j (https://sandbox.neo4j.com) to generate the database. The all data Kineviz-graphxr 2021-08-05 04-38-08.graphxr file can be loaded into the web-based graph visualization and processing tool GraphXR(https://graphxr.kineviz.com/register) with an account (free). 

Here are some visulaization made with the databse using GraphXR:

![image](https://user-images.githubusercontent.com/88473250/128296246-64194f55-1919-431d-8ddf-6377c93f230e.png)
Figure 1: Locations at which the lawsuits in the movement were filed

![image](https://user-images.githubusercontent.com/88473250/128296819-c4fef015-c61b-455f-9760-09059d99eeb1.png)
Figure 2: Rough 3D graph of the relationships between lawsuits and lawyers in the movement
