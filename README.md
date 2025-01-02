# ArrayIndexOutOfBoundsException Bug in Java

This repository demonstrates a common Java bug: an `ArrayIndexOutOfBoundsException`. The bug occurs when trying to access an array element using an index that is out of the array's bounds.  The solution corrects the loop condition to prevent this exception.

## Bug Description

The provided Java code attempts to access an element of an integer array with an invalid index, causing an `ArrayIndexOutOfBoundsException`. The error arises from the loop's condition `i <= arr.length`. This condition causes the loop to iterate one time too many, resulting in an attempt to access an element that is not part of the array.