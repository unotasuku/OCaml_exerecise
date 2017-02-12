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

let souba x = float -> int

let x= 100.0
let souba x = 100.0 /1
float -> intの変換の仕方が不明
 
# ???足の数の合計を与えら鶴の数と亀の返す*) 鶴の数と亀の数を 返す*)
  (*と足の数の合計を与えら鶴の数を返す*)ent.
  (*tsurukame : int -> int -> int -><fun>*)ら 鶴の数を返す*)
  let tsurukame d c = 4*d - c;;nt -><fun>*)
  let tsurukame d c = 4*d - c;;
Error: Illegal character (\129)
# let tsurukame d c = 4 * d - c;;
val tsurukame : int -> int -> int = <fun>
# tsurukame 12 42 ;;
- : int = 6
# let tsurukmae a b = (4*b - c) /2;;
Error: Unbound value c
# let tsurukame  a b = (4*b - c)/2;;
Error: Unbound value c
# let tsurukme a b = (4*b - a) / 2;;
val tsurukme : int -> int -> int = <fun>
# tsurukame 12 42 ;;
- : int = 6
# let tsurukame a b = (c - 4*d)/2;;
Error: Unbound value c
# let tsurukme c d = ( c - 4*d)/2;;
val tsurukme : int -> int -> int = <fun>
# tsurukame 12 42;;
- : int = 6
# let tsurukame a b = 2 * b -a;;
val tsurukame : int -> int -> int = <fun>
# tsurukame 12 42;;
- : int = 72
# tsurukame 42 12;;
- : int = -18
# let tsurukame a b = (4*b -a )/2;;
val tsurukame : int -> int -> int = <fun>
# tsurukame 12 42;;
- : int = 78
# tsurukame 42 12;;
- : int = 3

# let jikan x = if x > 1 && x<=12 then "AM" 
                                  else if x >= 13 && x < 25 then "PM"
                                  else "N.W.A";
                                  
val jikan : int -> string = <fun>
# (*2次方程式の係数を与えたら判別式の値を返す*)
  (*float->float->float->float*)
  let hanbetsusiki a b c = b**2. -. 4.*.a*.c;;
val hanbetsusiki : float -> float -> float -> float = <fun>

  (*2次方の係数が与え解の個数を返す*)omment.
  (*kosuu: int ->string*) えられたら 解の個数を返す*)
  # let kai_no_kosuu a b c = if b**2. -. 4.*.a*.c > 0. then 2
  					             else if b**2. -. 4.*.a*.c = 0. then 1
                                                     else 0;;    
val kai_no_kosuu : float -> float -> float -> int = <fun>
# 
# (*2次方程式を与えられたら虚数解の有無を返す*)
  (*float->float->float->string*)
  let kyosukai a b c = if B**2. - 4*a*c < 0 then "YES"
                                            else "NO";;
Error: Unbound constructor B
# let kyosuukai a b c = if b**2. -. 4.*a*c < 0. then "YES"
  						else "NO";;
Error: This expression has type float but an expression was expected of type
         int
# let kyosuukai a b c = if b**2. -.4.*.a*.c < 0. then "Yes"
  						 else"No";;
val kyosuukai : float -> float -> float -> string = <fun>
# kyosukai 3. 4. 5.;;
Error: Unbound value kyosukai
# kyosuukai 3. 4. 5.;;
- : string = "Yes"

# (*BMIを計算し体型を返す*) す*)
  (*BMI:float->float->float->string*)
  let taikei a b = if a**2./.b < 18.5 then "Yase"
                                      else if a**2. /.b >30 then "Hyoujyun";;
Error: This expression has type int but an expression was expected of type
         float
# let taike a b = if a**2. /. b < 18.5 then "Yase"
                                       else if a**2. /. b > 30. then "Hyoujyun"
                                       else "Debu";;
val taike : float -> float -> string = <fun>
