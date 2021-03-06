# Garbage Collector Refinement proof in PVS

![crime scene 1](https://images.fineartamerica.com/images/artworkimages/mediumlarge/1/le-conti-david-thompson.jpg)

```
 Proof summary for theory Refinement1
    S_TCC1.................................................proved - complete
    sim_mutate.............................................proved - complete
    sim_colour_target......................................proved - complete
    sim_stop_colouring.....................................proved - complete
    sim_colour.............................................proved - complete
    sim_stop_appending.....................................proved - complete
    sim_continue_appending.................................proved - complete
    sim_black_to_white.....................................proved - complete
    sim_append_white.......................................proved - complete
    next_h.................................................proved - complete
    R1_TCC1................................................proved - complete
    R1_TCC2................................................proved - complete
    R1_TCC3................................................proved - complete
    R1_TCC4................................................proved - complete
    Theory totals: 14 formulas, 14 attempted, 14 succeeded.

 Proof summary for theory Garbage_Collector
    IMPORTING1_TCC1........................................proved - complete
    Theory totals: 1 formulas, 1 attempted, 1 succeeded.

 Proof summary for theory Garbage_Collector1_Inv
    IMPORTING1_TCC1........................................proved - complete
    inv1_TCC1..............................................proved - complete
    i_inv1.................................................proved - complete
    i_inv2.................................................proved - complete
    p_inv1.................................................proved - complete
    p_inv2.................................................proved - complete
    p_I....................................................proved - complete
    inv....................................................proved - complete
    Theory totals: 8 formulas, 8 attempted, 8 succeeded.

 Proof summary for theory Garbage_Collector1
    IMPORTING1_TCC1........................................proved - complete
    Rule_colour_target_TCC1................................proved - complete
    Rule_black_to_white_TCC1...............................proved - complete
    Rule_append_white_TCC1.................................proved - complete
    Theory totals: 4 formulas, 4 attempted, 4 succeeded.

 Proof summary for theory Refinement2
    I1_TCC1................................................proved - complete
    sim_mutate.............................................proved - complete
    sim_colour_target......................................proved - complete
    sim_stop_colouring_roots...............................proved - complete
    sim_colour_root........................................proved - complete
    sim_stop_propagating...................................proved - complete
    sim_propagate..........................................proved - complete
    sim_stop_appending.....................................proved - complete
    sim_continue_appending.................................proved - complete
    sim_black_to_white.....................................proved - complete
    sim_append_white.......................................proved - complete
    next_h.................................................proved - complete
    R2_TCC1................................................proved - complete
    R2_TCC2................................................proved - complete
    R2_TCC3................................................proved - complete
    R2_TCC4................................................proved - complete
    Theory totals: 16 formulas, 16 attempted, 16 succeeded.

 Proof summary for theory Garbage_Collector2_Inv
    IMPORTING1_TCC1........................................proved - complete
    i_inv1.................................................proved - complete
    i_inv2.................................................proved - complete
    p_inv1.................................................proved - complete
    p_inv2.................................................proved - complete
    p_I....................................................proved - complete
    inv....................................................proved - complete
    Theory totals: 7 formulas, 7 attempted, 7 succeeded.

 Proof summary for theory Garbage_Collector2
    IMPORTING1_TCC1........................................proved - complete
    Rule_colour_target_TCC1................................proved - complete
    Rule_colour_root_TCC1..................................proved - complete
    Rule_black_to_white_TCC1...............................proved - complete
    Rule_append_white_TCC1.................................proved - complete
    Theory totals: 5 formulas, 5 attempted, 5 succeeded.

 Proof summary for theory Refinement
    ref....................................................proved - complete
    Theory totals: 1 formulas, 1 attempted, 1 succeeded.

 Proof summary for theory Refinement3
    I2_TCC1................................................proved - complete
    sim_mutate.............................................proved - complete
    sim_colour_target......................................proved - complete
    sim_stop_colouring_roots...............................proved - complete
    sim_colour_root........................................proved - complete
    sim_stop_propagating...................................proved - complete
    sim_continue_propagating...............................proved - complete
    sim_white_node.........................................proved - complete
    sim_black_node.........................................proved - complete
    sim_stop_colouring_sons................................proved - complete
    sim_colour_son.........................................proved - complete
    sim_stop_counting......................................proved - complete
    sim_continue_counting..................................proved - complete
    sim_skip_white.........................................proved - complete
    sim_count_black........................................proved - complete
    sim_stop_colouring.....................................proved - complete
    sim_continue_colouring.................................proved - complete
    sim_stop_appending.....................................proved - complete
    sim_continue_appending.................................proved - complete
    sim_black_to_white.....................................proved - complete
    sim_append_white.......................................proved - complete
    next_h.................................................proved - complete
    R3_TCC1................................................proved - complete
    R3_TCC2................................................proved - complete
    R3_TCC3................................................proved - complete
    R3_TCC4................................................proved - complete
    Theory totals: 26 formulas, 26 attempted, 26 succeeded.

 Proof summary for theory Memory_Properties
    IMPORTING1_TCC1........................................proved - complete
    abs_TCC1...............................................proved - complete
    abs_TCC2...............................................proved - complete
    smaller1...............................................proved - complete
    smaller2...............................................proved - complete
    smaller3...............................................proved - complete
    smaller4...............................................proved - complete
    colour1................................................proved - complete
    colour2................................................proved - complete
    blackened1.............................................proved - complete
    blackened2.............................................proved - complete
    blackened3.............................................proved - complete
    blackened4.............................................proved - complete
    blackened5.............................................proved - complete
    blackened6.............................................proved - complete
    blackened7.............................................proved - complete
    blackened8.............................................proved - complete
    black_roots1...........................................proved - complete
    black_roots2...........................................proved - complete
    black_roots3...........................................proved - complete
    bw1....................................................proved - complete
    bw2....................................................proved - complete
    bw3....................................................proved - complete
    bw4....................................................proved - complete
    exists_bw1.............................................proved - complete
    exists_bw2.............................................proved - complete
    exists_bw3.............................................proved - complete
    exists_bw4.............................................proved - complete
    exists_bw5.............................................proved - complete
    exists_bw6.............................................proved - complete
    exists_bw7.............................................proved - complete
    exists_bw8.............................................proved - complete
    exists_bw9.............................................proved - complete
    exists_bw10............................................proved - complete
    exists_bw11............................................proved - complete
    exists_bw12............................................proved - complete
    exists_bw13............................................proved - complete
    exists_bw14............................................proved - complete
    blacks1................................................proved - complete
    blacks2................................................proved - complete
    blacks3................................................proved - complete
    blacks4................................................proved - complete
    blacks5_1..............................................proved - complete
    blacks5_2..............................................proved - complete
    blacks5................................................proved - complete
    blacks6................................................proved - complete
    blacks7................................................proved - complete
    Theory totals: 47 formulas, 47 attempted, 47 succeeded.

 Proof summary for theory Memory_Observers
    IMPORTING1_TCC1........................................proved - complete
    black_roots_TCC1.......................................proved - complete
    blacks_TCC1............................................proved - complete
    blacks_TCC2............................................proved - complete
    Theory totals: 4 formulas, 4 attempted, 4 succeeded.

 Proof summary for theory Accessible_Memory_Properties
    IMPORTING1_TCC1........................................proved - complete
    path_TCC1..............................................proved - complete
    member_cdr_TCC1........................................proved - complete
    set_son_points_to_1....................................proved - complete
    set_son_points_to_2....................................proved - complete
    set_son_points_to_3....................................proved - complete
    path_append............................................proved - complete
    accessible_path........................................proved - complete
    path_member_cdr........................................proved - complete
    length_member_cdr......................................proved - complete
    path_without_duplicates................................proved - complete
    path_set_son...........................................proved - complete
    path_set_son_2.........................................proved - complete
    path_set_son_3.........................................proved - complete
    accessible1............................................proved - complete
    accessible2............................................proved - complete
    Theory totals: 16 formulas, 16 attempted, 16 succeeded.

 Proof summary for theory Coloured_Memory
    IMPORTING1_TCC1........................................proved - complete
    Theory totals: 1 formulas, 1 attempted, 1 succeeded.

 Proof summary for theory Memory
    son_TCC1...............................................proved - complete
    Theory totals: 1 formulas, 1 attempted, 1 succeeded.

 Proof summary for theory Garbage_Collector3
    IMPORTING1_TCC1........................................proved - complete
    Rule_colour_target_TCC1................................proved - complete
    Rule_colour_root_TCC1..................................proved - complete
    Rule_colour_son_TCC1...................................proved - complete
    Rule_colour_son_TCC2...................................proved - complete
    Rule_black_to_white_TCC1...............................proved - complete
    Rule_append_white_TCC1.................................proved - complete
    Theory totals: 7 formulas, 7 attempted, 7 succeeded.

 Proof summary for theory Invariant_Predicates
    preserved_and..........................................proved - complete
    preserved_inv..........................................proved - complete
    Theory totals: 2 formulas, 2 attempted, 2 succeeded.

 Proof summary for theory Garbage_Collector3_Inv
    IMPORTING1_TCC1........................................proved - complete
    inv1_TCC1..............................................proved - complete
    inv4_TCC1..............................................proved - complete
    inv6_TCC1..............................................proved - complete
    c_inv9.................................................proved - complete
    i_inv1.................................................proved - complete
    i_inv2.................................................proved - complete
    i_inv3.................................................proved - complete
    i_inv4.................................................proved - complete
    i_inv5.................................................proved - complete
    i_inv6.................................................proved - complete
    i_inv7.................................................proved - complete
    i_inv8.................................................proved - complete
    i_inv9.................................................proved - complete
    i_inv10................................................proved - complete
    i_inv11................................................proved - complete
    i_inv12................................................proved - complete
    i_inv13................................................proved - complete
    i_inv14................................................proved - complete
    i_inv15................................................proved - complete
    p_inv1.................................................proved - complete
    p_inv2.................................................proved - complete
    p_inv3.................................................proved - complete
    p_inv4.................................................proved - complete
    p_inv5.................................................proved - complete
    p_inv6.................................................proved - complete
    p_inv7.................................................proved - complete
    p_inv8.................................................proved - complete
    p_inv10................................................proved - complete
    p_inv11................................................proved - complete
    p_inv12................................................proved - complete
    p_inv13................................................proved - complete
    p_inv14................................................proved - complete
    p_inv15................................................proved - complete
    p_I....................................................proved - complete
    inv....................................................proved - complete
    Theory totals: 36 formulas, 36 attempted, 36 succeeded.

 Proof summary for theory Refine_Predicate
    Theory totals: 0 formulas, 0 attempted, 0 succeeded.

 Proof summary for theory Traces
    Theory totals: 0 formulas, 0 attempted, 0 succeeded.

 Proof summary for theory Refine_Predicate_Transitive
    transitive.............................................proved - complete
    Theory totals: 1 formulas, 1 attempted, 1 succeeded.

 Proof summary for theory Composed_Refinement
    IMPORTING1_TCC1........................................proved - complete
    ref2...................................................proved - complete
    ref....................................................proved - complete
    Theory totals: 3 formulas, 3 attempted, 3 succeeded.

Grand Totals: 200 proofs, 200 attempted, 200 succeeded.
```