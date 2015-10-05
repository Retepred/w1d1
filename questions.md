1. Assign to the value `6` to the variable `number_six`
number_six = 6

2. What is the datatype of `"Matz"`?
string

3. What do the following expressions evaluate to:
  * `"Cool" + "Cool" + "Cool"`
    CoolCoolCool

  * `t = "Troy"
    a = "Abed"
    "#{t} and #{a} in the Morning"` 
    Troy and Abed in the Morning

  * `10 * 3`
    30

  * `10 ** 3`
    1000

  * `10 % 3`
    3

  * `10 / 3`
3

  * `0.7 + 0.1`
  0.7999999999999999


4. Can you explain why the expressions all give the same result?
  * `"Ronnie " + "Pickering"`
  string + string
  * `"Ronnie ".+("Pickering")`
  string + string
  * `"Ronnie ".send(:+, "Pickering")`
  All of these statements are effectively just adding the same two strings. The first one is simple because of syntactic sugar.

5. Please fix the following buggy expressions:
  * `number six = 6` 'number_six = 6'
  * `"Maroon" + 5` '"Maroon" + 5.to_s'
  * `ture == flase` true == false