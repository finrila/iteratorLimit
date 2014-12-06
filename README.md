iteratorLimt
============

#有限制的迭代器

###实例：

    iteratorLimit([1,2,3,4,5,6,7, 8, 9, 10, 222], 3, function(next, item, index, source) {
     console.log(item, index, source);
     setTimeout(next, 1000);
    });
    iteratorLimit({1:4,2:78,3:323,7:24234,8:999}, 3, function(next, value, key, source) {    
     console.log(item, key, source);
     setTimeout(next, 1000);
    });
