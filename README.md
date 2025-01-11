# Loose Comparison Bug in JavaScript

This repository demonstrates a common error in JavaScript related to loose comparison (==) when handling null and undefined values. The `foo` function intends to return 0 if the input is null, but it incorrectly handles undefined, resulting in NaN.  The solution demonstrates the use of strict equality (===) for more predictable behavior.