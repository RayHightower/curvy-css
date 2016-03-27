curvy-css
===

Based on work created by [Ana Tudor](http://codepen.io/thebabydino/pen/dlGJI) and shared by [Josh Cheek](https://twitter.com/josh_cheek).

Mesh-like version of [this earlier pen](http://codepen.io/thebabydino/pen/xfAed). Uses `transform-style: preserve-3d;` so no IE, not even 11. Tested & works in Firefox 27 (z-index tramples 3D order :( choppy animation, edges don't look that good), Chrome 32 & 34 Canary on Windows 7. 

Graphs the function `f(x, y) = p*x/e^(x^2 + y^2)` where `p` is made to vary over time.
