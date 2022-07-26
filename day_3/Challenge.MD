# Challenge : day 3 🐓

TODO

# Prerequisites ✅

- Make sure you've read all the instructions on how to complete the challenges.

- Follow along with the daily guide.

# Coding 🧑‍💻

For the daily challenges of today, you need to create multiples files. Instead of creating a file day_3.mo, start by creating a folder day_3 and inside create the different files you'll be asked for through the challenges.

- Challenge 1 : Create two files called custom.mo and main.mo, create your own type inside custom.mo and import it in your main.mo file. In main, create a public function<strong> <i> fun </i> </strong> that takes no argument but return a value of your custom type. <br/>
  Note : Be creative 🌈

- Challenge 2 : Create a new file called animal.mo with at least 2 property (specie of type Text, energy of type Nat), import this type in your main.mo and create a variable that will store an animal.

- Challenge 3 : In animal.mo create a public function called animal_sleep that takes an **Animal** and returns the same Animal where the field energy has been increased by 10.
  Note : As this is a public function of a **module**, you don't need to make the return type Async !

- Challenge 4 : In main.mo create a public function called<strong> <i> create_animal_then_takes_a_break <T> </i> </strong> that takes two parameter : a specie of type Text, an number of energy point of type Nat and returns an animal. This function will create a new animal based on the parameters passed and then put this animal to sleep before returning it ! 💤

- Challenge 5 : In main.mo, import the type List from the base Library and create a list that stores animal.

- Challenge 6 : In main.mo : create a function called <strong> <i> push_animal </i> </strong> that takes an animal as parameter and returns nothing this function should add this animal to your list created in challenge 5. Then create a second functionc called <strong> <i> get_animals </i> </strong> that takes no parameter but returns an **Array** that contains all animals stored in the list.

For challenges 7 to 10 : You need to start from a fresh file (call it list.mo) you **cannot** use the List module of the base library, the goal is to reimplement some functionnality of arrays.

- Challenge 7 : Write a function <strong> <i> is_null<T> </i> </strong> that takes <strong> l </strong> of type <strong>List\<T> </strong> and returns a boolean indicating if the list is <strong> <i> null </i> </strong>.
  Tips : Try using a switch/case.

- Challenge 8 : Write a function <strong> <i> last </i> </strong> that takes <strong> l </strong> of type <strong>List\<T> </strong> and returns the optional last element of this list.

- Challenge 9 : Write a function <strong> <i> size </i> </strong> that takes <strong> l </strong> of type <strong>List\<T> </strong> and returns a <strong> Nat </strong> indicating the size of this list. <br/>
  Note : If l is <strong> <i> null </i> </strong>, this function will return 0.

- Challenge 10 : Write a function <strong> <i> get </i> </strong> that takes two arguments : <strong> l </strong> of type <strong>List\<T> </strong> </strong> and <strong> n </strong> of type <strong> Nat</strong> this function should return the optional value at rank n in the list.

- Challenge 11 : Write a function <strong> <i> is_anonymous </i> </strong> that takes no arguments but returns **true** is the caller is anonymous and **false** otherwise.

- Challenge 12 : Create an HashMap called favoriteNumber where the keys are **Principal** and the value are **Nat**.

- Challenge 13 : Write two functions :

  - <strong> <i> add_favorite_number </i> </strong> that takes n of type **Nat** and stores this value in the HashMap where the key is the principal of the caller. This function has no return value.
  - <strong> <i> show_favorite_number </i> </strong> that takes no argument and returns n of type **?Nat**, n is the favorite number of the person as defined in the previous function or null if the person hasn't registered.

- Challenge 14 : Rewrite your function <strong> <i> add_favorite_number </i> </strong> so that if the caller has already registered his favorite number, the value in memory isn't modified. This function will return a text of type **Text** that indicates "You've already registered your number" in that case and "You've successfully registered your number" in the other scenario.

- Challenge 15 : Write two functions

  - <strong> <i> update_favorite_number </strong> </i>
  - <strong> <i> delete_favorite_number </strong> </i>

- Challenge 16 : Write a function <strong> <i> deposit_cycles </strong> </i> that allow anyone to deposit cycles into the canister. This function takes no parameter but returns n of type **Nat** corresponding to the amount of cycles deposited by the call.

- Challenge 17 (hard ⚠️) : Write a function <strong> <i> withdraw_cycles </strong> </i> that takes a parameter n of type **Nat** corresponding to the number of cycles you want to withdraw from the canister and send it to caller asumming the caller has a callback called deposit_cycles()<br/>
  Note : You need two canisters. <br/>
  Note 2 : Don't do that in production without admin protection or your might be the target of a **cycle draining** attack.

- Challenge 18 : Rewrite the counter (of day 1) but this time the counter will be kept accross ugprades. Also declare a variable of type **Nat** called versionNumber that will keep track of how many times your canister has been upgraded.

- Challenge 19 : In a new file, copy and paste the functionnalities you've created in challenges 12 to 15. This time the hashmap and all records should be preserved accross upgrades.

- Challenge 20 (optional) : In autonomy, write a CRUD canister, you can add as much functionnalities as you want, a few examples :

  - Anonymous principal rejection.
  - Cycle functionnality for registration.
  - Admin management.

Note : Only practice challenge 20 if you wish to, this is optional and it will not be taken into account for any ranking.

<br/>
<strong> <i> Good luck 🎉 </strong> </i>
