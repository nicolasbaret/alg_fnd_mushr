# Project 1: Introduction [![tests](../../../badges/submit-proj1/pipeline.svg)](../../../pipelines/submit-proj1/latest)

1. Define in your own words what a node, topic, publisher, and subscriber are and how they relate to each other.

    In ROS, there is a graph which connects all the nodes in the workspace. Each node is a executable file, which is normally supposed to be a very specific action or "feature" we want in the system that we are developing. All the nodes can communicate to eachother via the graph. A topic is a "subject" that nodes can choose to get messages from or to send messages to. Nodes which are subscribed to that topic can listen to the topic, and will recieve those messages when one is sent to the topic. A publisher is a node which sends messages to a specific topic, and a subscriber is one which listens to a topic for messages.

2. What is the purpose of a launch file?

    It's so that we can launch a bunch of different nodes at the same time. It would be exhausting to launch all the nodes we need individually, so this is a helpful file to use so that we can conduct efficient development.

3. Include the RViz screenshot showing the new map.

    
4. Include your runtime_comparison.png figure for the different norm implementations.
5. Include the locations.png and distances.png figures for the plan figure_8.txt.
6. Include the locations.png and distances.png figures for the plan tight_figure_8.txt.

