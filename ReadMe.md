1. What is Git?
Git is a version control system that you download onto your computer. 
It is essential that you use Git if you want to collaborate with other developers on a coding project or work on your own project.
In order to check if you already have Git installed on your computer you can type the command git --version in the terminal.

2. What is Github?
GitHub is a product that allows you to host your Git projects on a remote server somewhere (or in other words, in the cloud).
It's important to remember that GitHub is not Git. GitHub is just a hosting service. 
There are other companies who offer hosting services that do the same thing as GitHub, such as Bitbucket and GitLab.


<img width="960" alt="2022-02-08" src="https://user-images.githubusercontent.com/65388647/152986992-823ebfc4-29d4-4398-b4c1-8a61e1d8059f.png">
<img width="960" alt="2022-02-08 (2)" src="https://user-images.githubusercontent.com/65388647/152987033-3f64f7b6-0e26-49b0-83b6-2a5f35fc0fd6.png">
<img width="960" alt="2022-02-08 (1)" src="https://user-images.githubusercontent.com/65388647/152987063-460629af-97dd-45b0-add5-e7c5654e37bf.png">
.
## QUICK SORT

This algorithm (also called partition exchange sort algorithm) can be implemented both recursively and iteratively. However the iterative approach is discouraged ( easier to write ~ahem ahem~ and understand. The time and space complexity of both is relatively similar, that is, 0(nlogn) for average and 0(n**2) for worst case (when the elements need sorting to the smallest partition) . However we consider the worst case not the average case)
Okay now to the algorithm. Quick sort, like merge sort is a divide and conquer algorithm. While merge sort concentrates on merging ( i know i know, spoiler alert), quick sort concentrates on dividing.
How the algorithm works: The array is partitioned using an element chosen called pivot( key element).
Consider the first element of array as the pivot.
Define two variables, start -element at index 1 and end -(element at len(data) -1)
Increment start if start is less than pivot and decrements end if end is more than pivot.
If start is greater than end, swap the two values.
These steps are repeated till start > end
Swap pivot and end.
This same procedure is used for the partitions.
Here is an example of array sorted using quick sort.

![quicksort](https://user-images.githubusercontent.com/65388647/152988180-ef2076e3-36bd-40ee-ad04-c14a8161c6eb.jpeg)

The following example is quick sort algorithm in python.

![quick](https://user-images.githubusercontent.com/65388647/152988195-2d0d46a5-2f06-46d3-9a98-a1c332aea7ed.png)
