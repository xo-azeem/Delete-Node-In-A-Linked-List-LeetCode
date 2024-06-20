# Delete-Node-In-A-Linked-List

LeetCode Q # 237.

There is a singly-linked list head and we want to delete a node node in it.</br>
You are given the node to be deleted node. You will not be given access to the first node of head.</br>
All the values of the linked list are unique, and it is guaranteed that the given node node is not the last node in the linked list.</br>
Delete the given node. Note that by deleting the node, we do not mean removing it from memory. We mean:</br>

- The value of the given node should not exist in the linked list.</br>
- The number of nodes in the linked list should decrease by one.</br>
- All the values before node should be in the same order.</br>
- All the values after node should be in the same order.</br>

Custom testing:

For the input, you should provide the entire linked list head and the node to be given node. node should not be the last node of the list and should be an actual node in the list.</br>
We will build the linked list and pass the node to your function.</br>
The output will be the entire list after calling your function.</br>

Example 1:

<div align = "center">

  ![image](https://github.com/xo-azeem/Delete-Node-In-A-Linked-List-LeetCode/assets/171427226/8b944149-b51f-46b6-ab12-f7c1f8daa80f)

</div>

>Input: head = [4,5,1,9], node = 5</br>
>Output: [4,1,9]</br>
>Explanation: You are given the second node with value 5, the linked list should become 4 -> 1 -> 9 after calling your function.</br>

Example 2:

<div align = "center">

  ![image](https://github.com/xo-azeem/Delete-Node-In-A-Linked-List-LeetCode/assets/171427226/34322b1f-c448-4507-b63e-3c9e9961a756)

</div>

>Input: head = [4,5,1,9], node = 1</br>
>Output: [4,5,9]</br>
>Explanation: You are given the third node with value 1, the linked list should become 4 -> 5 -> 9 after calling your function.</br>

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/xo-azeem/Delete-Node-In-A-Linked-List-LeetCode/assets/171427226/5d8184a0-33e2-4558-b131-05e0fa00a8a4)

  Time complexity: O(1).</br>Space complexity: O(1).
</div>
