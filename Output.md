
i.e. output

f(a, 12) = 12
f(a, 13) = 12
f(a, 12) = 12       // number found
f(a, 13) = 12       // smaller number found
f(a, 2) = -1        // out of bounds too small
f(a, 22) = 21       // out of bounds too large
f(a, 3) = 3         // exact left boundary
f(a, 21) = 21       // exact right boundary
f([], x) = -1       // empty array
f(null, x) = -1     // invalid input
