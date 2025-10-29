# Minimum-Loss

This code finds the minimum financial loss when buying a house at a higher price and later selling it at a lower price. It tracks both price values and their original positions, then sorts prices in descending order to efficiently compare potential loss scenarios. The algorithm only considers pairs where the higher price occurs before the lower price in the original sequence, ensuring temporal validity. Finally, it returns the smallest positive difference between such valid price pairs as the minimum loss.
