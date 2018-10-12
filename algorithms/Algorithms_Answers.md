Add your answers to the Algorithms exercises here.


Exercise I

a) O(n)

b) O(n^3)

c) O(n)

Exercise II

 partition the floors (fl),

 fl_base = math.ceil(fl_above/2)
 top = floors
 bottom = 1
 broken_eggs = 0

 flUp()
    bottom = fl_base
    floors above = top - bottom
    fl_base = fl_base + math.ceil( floors_above / 2)
    
 flDown()
        top = fl_base
        floor_below = top - bottom
        fl_base = fl_base -math.ceil(floor_below / 2)

 while fl_base > 0
   if fl_base > 0 flDown
        broken_eggs =broken_eggs + 1
    return fl_base, broken eggs

elif fl_base > fl
    broken_eggs = 0
    flUp()
else
    flDown()
