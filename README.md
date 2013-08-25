settlersofneo4j
===============

Playing with settlers of catan problems in neo4j

Neo4j is, of course, the answer to all problems. I've previously played around with some settlers of catan problems using python. Now I want to incorporate neo4j. 

For example, last night I was getting crushed in a game and I started thinking about how to build a representation of the settlers board. It seemed really stupid to just manually map out all the nodes and edges. I wanted to build it systematically.

Now I've actually got a two part problem I want to solve.

A) I want to flesh out an algorithm for generating boards of increasing size, one that has very minimal manual inputs.

B) I want go a step further and generate an algorithm for creating a board in which the nodes interact with each other to set up the relevent relationships. This is an interesting thought experiment. What would the nodes have to ask one another (if you set them up to have 1 to 1 random interactions with one another) in order to self assemble into a settlers board?  Would they have to elect a central hex node?  Etc.

Starting a repo for more github practice and on the off chance this gets interesting.
