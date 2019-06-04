### Free Blocks Management Using a Linked List

a)

| Block #    |  17 | 18 |
| ---------- |:----:|--:|
| Next Block |  18 | 0 |
|            | 4589 | 24353 |
|            | 43546 | 98745 |
|            | 718 | 76345 |
|            | 345 | 9877 |
|            |     | 7345 |
|            |     | 34535 |
|            |     | 154698 |
|            |     | 967 |
|            |     | 8657 |

b)

| Block #    |  17 | 18 |
| ---------- |:----:|--:|
| Next Block |  18 | 0 |
|            | 4589 | 24353 |
|            | 43546 | 98745 |
|            | 718 | 76345 |
|            | 345 | 9877 |
|            | 22  | 7345 |
|            |     | 34535 |
|            |     | 154698 |
|            |     | 967 |
|            |     | 8657 |

c)

| Block #    |  17 | 18 |
| ---------- |:----:|--:|
| Next Block |  18 | 0 |
|            |     | 24353 |
|            |     | 98745 |
|            |     | 76345 |
|            |     | 9877 |
|            |     | 7345 |
|            |     | 34535 |
|            |     | 154698 |
|            |     | 967 |
|            |     | 8657 |

d)

| Block #    |  17 | 18 |
| ---------- |:----:|--:|
| Next Block |     | 0 |
|            |     | 24353 |
|            |     | 98745 |
|            |     | 76345 |
|            |     | 9877 |
|            |     | 7345 |
|            |     | 34535 |
|            |     | 154698 |
|            |     | 967 |
|            |     | 17 |

e)

| Block #    |  17 | 18 |
| ---------- |:----:|--:|
| Next Block |     | 0 |
|            |     | 24353 |
|            |     | 98745 |
|            |     | 76345 |
|            |     | 9877 |
|            |     | 7345 |
|            |     | 34535 |
|            |     |     |
|            |     |     |
|            |     |     |

f)

| Block #    |  17 | 18 |
| ---------- |:----:|--:|
| Next Block | 18  | 0 |
|            |     | 24353 |
|            |     | 98745 |
|            |     | 76345 |
|            |     | 9877 |
|            |     | 7345 |
|            |     | 34535 |
|            |     | 23456 |
|            |     | 8345345 |
|            |     | 634534 |

### Free Blocks Management — Comparision

The more filled the disk gets the Linked List uses less storage space,
the bitmap uses always the same amount. So if more space is occupied the disk will get more available
space which you can use with the Linked List system.
