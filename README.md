### data-structure
    make queue,stack,linked list,tree using javascript
  
#### demo result

#####  tree
    -------------------------------------------------------------
    insert  7
    -------------------------------------------------------------
            7
    -------------------------------------------------------------
    insert  4
    -------------------------------------------------------------
                    7
            /               ＼
            4               -
    -------------------------------------------------------------
    insert  3
    -------------------------------------------------------------
                                    7
                    /                               ＼
                    4                               -
            /               ＼              /               ＼
            3               -               -               -
    -------------------------------------------------------------
    insert  3
    -------------------------------------------------------------
                                    7
                    /                               ＼
                    4                               -
            /               ＼              /               ＼
            3               -               -               -
    -------------------------------------------------------------
    insert  8
    -------------------------------------------------------------
                                    7
                    /                               ＼
                    4                               8
            /               ＼              /               ＼
            3               -               -               -
    -------------------------------------------------------------
    insert  9
    -------------------------------------------------------------
                                    7
                    /                               ＼
                    4                               8
            /               ＼              /               ＼
            3               -               -               9
    -------------------------------------------------------------
    insert  9
    -------------------------------------------------------------
                                    7
                    /                               ＼
                    4                               8
            /               ＼              /               ＼
            3               -               -               9
    -------------------------------------------------------------
    insert  4.5
    -------------------------------------------------------------
                                    7
                    /                               ＼
                    4                               8
            /               ＼              /               ＼
            3               4.5             -               9
    -------------------------------------------------------------
    insert  4.5
    -------------------------------------------------------------
                                    7
                    /                               ＼
                    4                               8
            /               ＼              /               ＼
            3               4.5             -               9
    -------------------------------------------------------------
    insert  7.8
    -------------------------------------------------------------
                                    7
                    /                               ＼
                    4                               8
            /               ＼              /               ＼
            3               4.5             7.8             9
    -------------------------------------------------------------
    insert  7.8
    -------------------------------------------------------------
                                    7
                    /                               ＼
                    4                               8
            /               ＼              /               ＼
            3               4.5             7.8             9
    -------------------------------------------------------------
    del 7
    -------------------------------------------------------------
                                    7.8
                    /                               ＼
                    4                               8
            /               ＼              /               ＼
            3               4.5             -               9
    -------------------------------------------------------------
    del 8
    -------------------------------------------------------------
                                    7.8
                    /                               ＼
                    4                               9
            /               ＼              /               ＼
            3               4.5             -               -
    -------------------------------------------------------------
    del 4
    -------------------------------------------------------------
                                    7.8
                    /                               ＼
                    4.5                             9
            /               ＼              /               ＼
            3               -               -               -
    -------------------------------------------------------------
    del 4.5
    -------------------------------------------------------------
                    7.8
            /               ＼
            3               9
    -------------------------------------------------------------
    del 3
    -------------------------------------------------------------
                    7.8
            /               ＼
            -               9
##### linked_list
    -------------------------------------------
    add 1
    position 1
    -------------------------------------------
    linkedList : 1 ->
    -------------------------------------------
    add 2
    position 2
    -------------------------------------------
    linkedList : 1 -> 2 ->
    -------------------------------------------
    add 3
    position 3
    -------------------------------------------
    linkedList : 1 -> 2 -> 3 ->
    -------------------------------------------
    add 3
    position 1
    -------------------------------------------
    linkedList : 3 -> 1 -> 2 -> 3 ->
    -------------------------------------------
    add 1
    position 5
    -------------------------------------------
    linkedList : 3 -> 1 -> 2 -> 3 -> 1 ->
    -------------------------------------------
    position 0
    remove 3
    -------------------------------------------
    linkedList : 1 -> 2 -> 3 -> 1 ->
    -------------------------------------------
    position 3
    remove 1
    -------------------------------------------
    linkedList : 1 -> 2 -> 3 ->
    
#####stack
    -------------------------------------------------------------
    push  3
    -------------------------------------------------------------
    │ 3 │
    └---┘
    -------------------------------------------------------------
    push  5
    -------------------------------------------------------------
    │ 5 │
    │ 3 │
    └---┘
    -------------------------------------------------------------
    push  1
    -------------------------------------------------------------
    │ 1 │
    │ 5 │
    │ 3 │
    └---┘
    -------------------------------------------------------------
    push  6
    -------------------------------------------------------------
    │ 6 │
    │ 1 │
    │ 5 │
    │ 3 │
    └---┘
    -------------------------------------------------------------
    pop!
    return 6
    -------------------------------------------------------------
    │ 1 │
    │ 5 │
    │ 3 │
    └---┘
    -------------------------------------------------------------
    pop!
    return 1
    -------------------------------------------------------------
    │ 5 │
    │ 3 │
    └---┘
    -------------------------------------------------------------
    push  9
    -------------------------------------------------------------
    │ 9 │
    │ 5 │
    │ 3 │
    └---┘
    -------------------------------------------------------------
    push  8
    -------------------------------------------------------------
    │ 8 │
    │ 9 │
    │ 5 │
    │ 3 │
    └---┘

#####queue
    -------------------------------------------------------------
    enqueue  5
    -------------------------------------------------------------
    [ 5 ]
    -------------------------------------------------------------
    enqueue  3
    -------------------------------------------------------------
    [ 5, 3 ]
    -------------------------------------------------------------
    dequeue, return  5
    -------------------------------------------------------------
    [ 3 ]
    -------------------------------------------------------------
    enqueue  8
    -------------------------------------------------------------
    [ 3, 8 ]
    -------------------------------------------------------------
    enqueue  7
    -------------------------------------------------------------
    [ 3, 8, 7 ]
    -------------------------------------------------------------
    dequeue, return  3
    -------------------------------------------------------------
    [ 8, 7 ]
    -------------------------------------------------------------
    enqueue  9
    -------------------------------------------------------------
    [ 8, 7, 9 ]
    -------------------------------------------------------------
    enqueue  10
    -------------------------------------------------------------
    [ 8, 7, 9, 10 ]
    -------------------------------------------------------------
    dequeue, return  8
    -------------------------------------------------------------
    [ 7, 9, 10 ]


  
  
