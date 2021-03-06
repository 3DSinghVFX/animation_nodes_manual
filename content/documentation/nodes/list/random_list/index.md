---
title : Random List
weight : 1
---

## Description

This node creates a list of defined length filled with random elements
from an input list. Unlike the *Get Random Element List* node, this node
can create a list of any length because its allows duplicates.

![image](random_list_node.png)

## Inputs

- **Seed** - Seed for the random generator, where different seed
    return different random elements.
- **Length** - The length of the output list.
- **Source** - The input source list.

## Outputs

- **List** - A list of length **Length** which contains random
    elements from the input source list.

## Advanced Node Settings

- N/A

## Note

The node has an **extra seed** (*Node Seed*) that can be used to
differentiate between nodes with the same seed, e.g., When using
multiple *Random List* nodes in a loop while using the index as a seed,
you can change the extra seed to get different results from the other
nodes.

Animation Nodes automatically changes the *Node Seed* when you duplicate
or add a new *Random List* node.

## Examples of Usage

{{< video random_list_node_example.mp4 >}}
