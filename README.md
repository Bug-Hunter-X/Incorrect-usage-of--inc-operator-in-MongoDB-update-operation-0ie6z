# Incorrect Usage of $inc operator in MongoDB
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB, resulting in an error. The `$inc` operator is used to increment a numerical field by a specified value.  It's crucial that this value is a number, not a string.

**Bug:**
The code attempts to increment the `field1` by the string value '10', which causes an error.

**Solution:**
The correct usage involves providing a numerical value (integer or float) to the `$inc` operator.
