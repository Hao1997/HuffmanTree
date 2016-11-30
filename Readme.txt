Question 3 )


A) Sorted list implemenation takes O(n^2), because it takes O(n) to insert a letter into the queue. Since there is n number of letters then the running time is O(n^2). The rest of the operations minKey and remove min takes O(n) - with n number of letters.

B) unsorted list takes O(n^2), because it takes O(n) to access the minkey. Since theres is n number of letters then the running time is O(n^2). To insert it only takes O(n).

C) Heap list takes O(nlogn), because it takes only O(logn) to insert a key. Thus since there is n number of letters the running time is O(nlogn). The rest of the operations take O(n) for n number of letters.