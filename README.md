# Towers of Hanoi
This project is a simulation solving the Tower of Hanoi. The algorithm for moving the disks is more efficient that the usual naive implementation because it is iterative instad of recursive, and consequently it does not take up space to store the recursive runtime stack and also it does not it go into repeated recursion. If we have N disks, the space complexity is O(N) and the time complexity is O(2^N). This algorithm is able to achieve such efficienty because it is based on the properties of binary mathematics. Each disk is represented as a bit in a binary number. Every time the 2^0 bit is flipped the 0 disk (the smallest disk) moves. Every time the 2^1 bit is flipped the 1 disk (the next smallest) disk is moves, and so on.

steps for ri=un the project

You can use the application by pressing the Make Move button. The first press will load the Hanoi Tower. Every button press after that iterates through solving the Hanoi Tower. When the Hanoi Tower is solved, on the last button press, you will receive an alert stating Tower is Finished.

I have implement this program using recursion
