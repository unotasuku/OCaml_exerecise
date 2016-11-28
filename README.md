# OCaml_exerecise_igarashi2007
abs(3- 5)
1 + 2 
( 1 + 2)
6 / 4 + 2
5 - 8 - 7
56 / 4 /5
0b1111
-0o274
-0x1A3F
練習2.2.5
2.1
1.　ーー1 
2. - 2 + 3 
3. 9 / -4
4. -3 + 5
すべてint　type

2.2
float_of_int 3 +. 2.5
int_of_float 0.7
char_of_int((int_of_char'A') + 20)
5.0 ** 2.0

2.3
1. float_of_int(int_of_float 5.0)
2. (sin 3.0 /. 2.0) ** 2.0 +. cos (3.0 /. 2.0) ** 2.0
3. sqrt (3*3) + (4*4)

3. 関数言語の醍醐味；関数
let pi = 3.14
let area_of_circle r = r*. r*. pi(半径rの円の面積を求める)

let abs x = if x >0 then x else if x= 0 then 0 else -(x)

let hitoketa x = 1 <= x && x<=10

let pi = 3.14 (*ｐi の定義*)
let cone_of_heightTwo r =　(*三角錐の体積の求め方*)
 let base = r *. r *. pi in
 base *. 2.0 /. 3.0
 
 let f x = （*合成関数の定義*)
  let x3 = x* x* x in
  let x3_1 = x3 + 1 in
  x3 +x3_1
  
let g x  =
 let power3 x = x*x*x in
 (power3 x) + (power3 (x+1))
 

 
