# Pioneer-Delivery-Company-s-Algorithm-Portfolio

1. The greedy choice is to always select the delivery that finishes the earliest. We do this by first sorting all deliveries by their finish times, and then selecting each delivery whose start time does not overlap with the previously selected delivery.

2. Choosing the delivery that finishes earliest leaves the most time available for future deliveries. This ensures we can select as many non-overlapping deliveries as possible.

3. The overall time complexity is O(n log n), where n is the number of deliveries. Sorting the deliveries by finish time takes O(n log n), and iterating through the deliveries to select compatible ones takes O(n). Therefore, the total running time is O(n log n).
