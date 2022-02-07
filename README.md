# GolangRefresher


# Datatypes difference

# Implementation independent 
# int and uint 
# if you use int and uint --> your golang program will work even if you run it in any kind of architecure either in 32 bit machine or 64 bit machine

# Go has the following architecture-independent integer types:

uint8       unsigned  8-bit integers (0 to 255)
uint16      unsigned 16-bit integers (0 to 65535)
uint32      unsigned 32-bit integers (0 to 4294967295)
uint64      unsigned 64-bit integers (0 to 18446744073709551615)
int8        signed  8-bit integers (-128 to 127)
int16       signed 16-bit integers (-32768 to 32767)
int32       signed 32-bit integers (-2147483648 to 2147483647)
int64       signed 64-bit integers (-9223372036854775808 to 9223372036854775807)


# Floats and complex numbers also come in varying sizes:

float32     IEEE-754 32-bit floating-point numbers
float64     IEEE-754 64-bit floating-point numbers
complex64   complex numbers with float32 real and imaginary parts
complex128  complex numbers with float64 real and imaginary parts

# There are also a couple of alias number types, which assign useful names to specific data types:

byte        alias for uint8
rune        alias for int32

# IT IS ALWAYS BETTER TO USE 'int' and 'uint' SO THAT IT CAN ACCOMODATE ITSELF FOR ANY KIND OF ARCHITECUTRE


# Types of variable declaration


![image](https://user-images.githubusercontent.com/80065996/151996906-108b36d8-9916-4c8a-b537-4073833b8617.png)


![image](https://user-images.githubusercontent.com/80065996/151996947-7e90cfe6-4023-4040-ae3d-0d54bf84e654.png)


![image](https://user-images.githubusercontent.com/80065996/151998376-2d2fc0c6-71ce-4f36-b7c7-775381f321e6.png)


![image](https://user-images.githubusercontent.com/80065996/151998430-d20d25df-1175-4c9e-a2aa-9f079ec6723e.png)


# DEFAULT FORMATTING for float will not display as 0.0. it will display only as 0. if you need formatting you have to do it on your own


# the default formatting for floating point values omits the decimal point if the value is an integer. if you need different formatting, you'll need to use Printf or otherwise # # format it yourself.


![image](https://user-images.githubusercontent.com/80065996/152000886-7548b262-7854-4372-b8d6-c7a54dba5803.png)


![image](https://user-images.githubusercontent.com/80065996/152000928-01be3233-521b-4d76-b4e2-9f274a3aad95.png)


# formatting using "fmt.Printf"


![image](https://user-images.githubusercontent.com/80065996/152002218-7c56464b-f420-45ef-a3a2-ef6abbc11237.png)


![image](https://user-images.githubusercontent.com/80065996/152002267-9475cf9f-b044-4d17-83fb-ea3e5fa96090.png)



# boolean zero value


![image](https://user-images.githubusercontent.com/80065996/152002902-cabe6193-7322-4e96-9f2b-dbd991763cec.png)


![image](https://user-images.githubusercontent.com/80065996/152002934-84cd76f1-8e18-4701-88d8-5f45e078dbfb.png)


# 'nil' values zero value data types


![image](https://user-images.githubusercontent.com/80065996/152004359-06382268-04e0-4b4c-a79a-0fabf76dbc46.png)


![image](https://user-images.githubusercontent.com/80065996/152004391-7b947973-da31-43a1-b2da-0074af7b025a.png)


# Special 'nil' condition for map


![image](https://user-images.githubusercontent.com/80065996/152004942-c234354d-308d-4c80-9037-8a60edad8e19.png)


# error for nil map


![image](https://user-images.githubusercontent.com/80065996/152005045-bea30098-c7f1-48a1-a60a-33c0d46a83f0.png)


# Resolution. Always use make function for map


![image](https://user-images.githubusercontent.com/80065996/152005183-7f5b1a68-d69e-45ce-a860-633bfb5e37fb.png)


![image](https://user-images.githubusercontent.com/80065996/152005251-b817334e-dc8b-473d-906e-b97cafe145cb.png)


# Another usage of map


![image](https://user-images.githubusercontent.com/80065996/152005843-ebad2ed8-6c13-4aa8-9375-1bf1c4d40b8a.png)


![image](https://user-images.githubusercontent.com/80065996/152005871-92fc1dc9-4639-41c2-838e-dc8688b2b850.png)


# printf examples,


![image](https://user-images.githubusercontent.com/80065996/152008179-0c276836-30c6-4384-b8bd-63064caad609.png)


![image](https://user-images.githubusercontent.com/80065996/152008222-ed792834-7cb9-4897-a623-3dc0a3be0eb4.png)


# sprintf example,


![image](https://user-images.githubusercontent.com/80065996/152010194-9828e0bd-0224-4117-8252-942a73cdfd5e.png)


![image](https://user-images.githubusercontent.com/80065996/152010273-17ee329d-1cfe-4190-a661-47acd6b981e9.png)


# fprintf is for displaying output from server


# Zero value of func() also nil


![image](https://user-images.githubusercontent.com/80065996/152109137-21ab9dc0-f659-41cf-9a90-c1f9970cc5fd.png)


![image](https://user-images.githubusercontent.com/80065996/152109165-2a36699f-785b-42d2-888c-e8715712e13b.png)


# function operation and nuances


![image](https://user-images.githubusercontent.com/80065996/152109384-e37afbf3-b25e-46bd-898f-d8a441fece17.png)


![image](https://user-images.githubusercontent.com/80065996/152109423-b3e3496f-1d26-4785-bbec-4a2ecb180764.png)


![image](https://user-images.githubusercontent.com/80065996/152109663-44c99e55-0376-4f33-bdb9-ed2dc8dff4c8.png)


![image](https://user-images.githubusercontent.com/80065996/152109684-34f4d6d2-0db3-4f72-bd4d-83355a6f6970.png)


![image](https://user-images.githubusercontent.com/80065996/152109856-7244fe03-417c-4776-825e-f15f18eab9df.png)


![image](https://user-images.githubusercontent.com/80065996/152109882-7898213f-893f-4a79-b902-e0186b9f1ffe.png)


# Function returning a function


![image](https://user-images.githubusercontent.com/80065996/152110573-eaf9a3dd-82c9-4eb8-b60a-d8ad69de5cb2.png)


![image](https://user-images.githubusercontent.com/80065996/152110603-ab760e36-7542-495a-bd2d-280213e55ea8.png)


# Function closure


![image](https://user-images.githubusercontent.com/80065996/152112538-2bbef069-b295-4705-af22-40ceb23eefd2.png)


![image](https://user-images.githubusercontent.com/80065996/152112580-b50ea6aa-f5ad-4ac1-ac5e-941f23f295b0.png)


# everytime new variable is used a new closure will be created. (function returning a function)


# Global scope


![image](https://user-images.githubusercontent.com/80065996/152113094-e6040111-50b9-4fd7-90fb-f322e086db9d.png)


![image](https://user-images.githubusercontent.com/80065996/152113122-6e94a5e1-6218-4c7a-817b-b5f58ab20bf4.png)


# scope limitation


![image](https://user-images.githubusercontent.com/80065996/152113429-a5045bde-169c-4302-802d-e76768b8be11.png)


![image](https://user-images.githubusercontent.com/80065996/152113472-05e4f1e8-5c91-471d-884d-1a7b00061fe6.png)


# variable declared outside (local scope) throws error


![image](https://user-images.githubusercontent.com/80065996/152113843-998fa394-5f9e-4be3-8314-3bb7220f7838.png)


# Function passed as argument to other function


![image](https://user-images.githubusercontent.com/80065996/152115577-2dd19315-0257-4c1a-8309-5c6ee5c94b83.png)


![image](https://user-images.githubusercontent.com/80065996/152115610-b649d455-bfb6-469a-aa1e-e0a94e968687.png)


# Closure clear explanation


![image](https://user-images.githubusercontent.com/80065996/152115736-d8ce2273-2be2-42a2-8fc8-23cb6f40724a.png)


# Variadic parameter Always use variadic parameter at the last


![image](https://user-images.githubusercontent.com/80065996/152117473-b0b7d6fc-166d-440b-9440-3ed2789b6948.png)


![image](https://user-images.githubusercontent.com/80065996/152117505-8c884cdd-f49f-4918-b31c-341542e5d679.png)


# Slice - dynamic memory allocation. Preferred way of grouping similar data in GO is slice


![image](https://user-images.githubusercontent.com/80065996/152119036-5b586361-d3c2-458a-be0b-16cd6aafe462.png)


![image](https://user-images.githubusercontent.com/80065996/152119068-9db6a190-7eda-461f-a95d-6c3d08a5a443.png)


# Altering slice inside another function.


![image](https://user-images.githubusercontent.com/80065996/152289564-d6e9bd24-bdc3-4583-a9b6-c52d9a159ba2.png)


# Result: even if you didnt returned the altered slice, the changed value will reflect in the slice data


![image](https://user-images.githubusercontent.com/80065996/152289696-63ab1bdc-7ebe-48ef-b644-0c2c7f64a2ca.png)


# same operation with append will not alter the slice data


![image](https://user-images.githubusercontent.com/80065996/152289785-6f562369-cbfd-4707-9c2a-7ada32d413a1.png)


# result:


![image](https://user-images.githubusercontent.com/80065996/152289812-e0dbb157-6e64-4cba-891d-9b9471bb3c7f.png)


# map altered inside another function and even if you are not returning the altered value it will get changed


![image](https://user-images.githubusercontent.com/80065996/152290033-1ebc3673-d885-4172-8311-9435e89178dd.png)


# result


![image](https://user-images.githubusercontent.com/80065996/152290063-74f81a57-fb16-494f-bf55-446c0781de15.png)


# Map + Slice operation


![image](https://user-images.githubusercontent.com/80065996/152290485-5d693ae8-b79a-4d02-8032-38453e4038f3.png)


# Result


![image](https://user-images.githubusercontent.com/80065996/152290542-404a780a-238d-4552-915b-07e550d5de18.png)


# map is unordered collection


![image](https://user-images.githubusercontent.com/80065996/152291587-be28e92e-edce-4631-ba93-86318563204a.png)


# if you range it we cannot be sure on which value comes first and which comes next


![image](https://user-images.githubusercontent.com/80065996/152291697-4bd46f1d-ed15-42d6-9fa7-fa2a26ba6d85.png)


# Deleting a value from a map


![image](https://user-images.githubusercontent.com/80065996/152292293-a4c65b41-076b-4cb3-b8de-5ddb9929fbe1.png)


![image](https://user-images.githubusercontent.com/80065996/152292327-f16d07c0-d117-4cba-b7e6-6f62453861e3.png)


# Deleting value from slice -  slice of slice deleting mid value


![image](https://user-images.githubusercontent.com/80065996/152293183-8019858d-dcd2-4ff8-bd93-8cd831f5a88f.png)


![image](https://user-images.githubusercontent.com/80065996/152293206-8d97587e-5fee-4d15-ab42-98ec39dab139.png)


# Multi dimensional slice


![image](https://user-images.githubusercontent.com/80065996/152295492-286388bf-95e9-4b95-8c9a-dfaa4b7b8feb.png)


# Result:


![image](https://user-images.githubusercontent.com/80065996/152295539-a14c2fd6-21f6-484a-acd9-21b5809b2a31.png)


# Under the hood processing for a slice :


![image](https://user-images.githubusercontent.com/80065996/152298350-5355e53f-092e-4bed-b2e2-7ae63a65395e.png)


![image](https://user-images.githubusercontent.com/80065996/152298375-eb0ff212-c3d0-4da0-b33b-e468efd3f9ea.png)


# dont's in using slice.


![image](https://user-images.githubusercontent.com/80065996/152298651-efbce5eb-a251-487f-ba4d-23970e4f6753.png)


![image](https://user-images.githubusercontent.com/80065996/152298700-ce3eb2c4-91f4-4944-8a07-2ca46d71f4db.png)


![image](https://user-images.githubusercontent.com/80065996/152298782-49263efd-edc1-4f68-9fbb-e22b2eea68d6.png)


![image](https://user-images.githubusercontent.com/80065996/152298817-24038dbc-5bc5-4a52-85e5-ad5a70f4bd90.png)


# Declaration of slice using Var keyword with append function works properly. but var key word with allocation of value using index will fail


![image](https://user-images.githubusercontent.com/80065996/152298988-b81cc481-2860-414c-adc8-8144af1e5ce1.png)


![image](https://user-images.githubusercontent.com/80065996/152299019-4b182399-3321-41cf-aac4-bd13fb3ef5d4.png)


# len and cap scenarios


![image](https://user-images.githubusercontent.com/80065996/152301805-b654eca5-6c0d-494c-bb61-cb2878f37ebf.png)


![image](https://user-images.githubusercontent.com/80065996/152301843-3a8e8e55-7f41-437e-96ea-21ae2baed9d0.png)


# in the first scenario, we are exceeding the maximum capacity of slice so new underlying array is created
# in the second scenario, we are not exceeding the capactiy so same underlying array is used


![image](https://user-images.githubusercontent.com/80065996/152302241-60be3885-520c-41a9-9600-7d816710ceef.png)


![image](https://user-images.githubusercontent.com/80065996/152302271-7477d53d-c51f-47ff-a594-9330724003e3.png)


# so slice operation purely depends on maximum capacity. so if maximum capacity exceeded new array will be created or else it used same underlying array


![image](https://user-images.githubusercontent.com/80065996/152302507-f3cb9397-ac80-4e1b-9a3b-bb5c8309c862.png)



![image](https://user-images.githubusercontent.com/80065996/152302532-66189a29-5092-4880-aa3d-0f322b7c551f.png)


# mentioning length and cap if slice as 0


![image](https://user-images.githubusercontent.com/80065996/152306885-e7f9a71e-f714-48ad-a28c-548c0a2572f0.png)


![image](https://user-images.githubusercontent.com/80065996/152306932-53f32849-38ce-4823-b6a9-1de959923a21.png)


# for the first time the number of values we are appending will become length and cap


![image](https://user-images.githubusercontent.com/80065996/152321494-782d2746-f3b7-4521-bda4-17999aafc905.png)


# next time when u append, it will work as per cap*2 when length is exceeded


![image](https://user-images.githubusercontent.com/80065996/152321650-a15cbde6-5ee4-49a0-b865-44cff0f3ea60.png)



# struct - group of different data types combined together


![image](https://user-images.githubusercontent.com/80065996/152322606-d2133a79-fd82-41af-a50b-8d27e10f1bdd.png)


![image](https://user-images.githubusercontent.com/80065996/152322653-82daac09-d7d5-4b18-9a4b-5bca2926f451.png)


![image](https://user-images.githubusercontent.com/80065996/152322721-d562a92b-2637-4834-9324-e023fed1273c.png)


![image](https://user-images.githubusercontent.com/80065996/152322795-0aafa3c2-c538-420f-a701-7d409e12ac0a.png)


# Embedded struct


![image](https://user-images.githubusercontent.com/80065996/152324786-4030c0dc-0b24-46e8-8daf-d5aeff2762b6.png)


![image](https://user-images.githubusercontent.com/80065996/152324836-bea0cbec-9880-42ec-966e-5cd3984d6687.png)


![image](https://user-images.githubusercontent.com/80065996/152324896-37d48786-9dc9-4f06-a991-f251a01e615d.png)


![image](https://user-images.githubusercontent.com/80065996/152325017-715e8bd9-ac12-46df-9935-bd4632bee949.png)


# Another construct of struct without mentioning data types


![image](https://user-images.githubusercontent.com/80065996/152325914-b0d69dc4-4585-402f-a41c-946c9507d095.png)


![image](https://user-images.githubusercontent.com/80065996/152325985-bb653101-0f2c-4892-a188-960d2cd37714.png)


![image](https://user-images.githubusercontent.com/80065996/152326014-7e57f0f5-64c6-4040-aa02-4fe561f4bbb1.png)


![image](https://user-images.githubusercontent.com/80065996/152327744-2f956e98-58ba-4421-92ad-8bc1c1900bcc.png)


![image](https://user-images.githubusercontent.com/80065996/152327772-8e576b63-8f05-4f07-921c-f149b7e7e81b.png)


# Another syntax of using a struct


![image](https://user-images.githubusercontent.com/80065996/152327951-89cc67da-7566-4755-88c1-b66d1061eed9.png)


![image](https://user-images.githubusercontent.com/80065996/152327984-70bdea96-1ba3-4f04-ac7f-ae2e86fc7c13.png)


# Ananymous struct


![image](https://user-images.githubusercontent.com/80065996/152329371-ba81ed74-4492-435b-ac68-286dc43530c6.png)


![image](https://user-images.githubusercontent.com/80065996/152329458-f3ce5d81-bb30-4771-8439-13a37502214d.png)


# Data type mismatch scenarios
# we cannot compare and do any operation even with subtypes. 


# float32 and float64 are different


![image](https://user-images.githubusercontent.com/80065996/152330460-35be4684-c22e-4b50-896b-3fefdbdd627f.png)


# int32 and int8 are different. 


![image](https://user-images.githubusercontent.com/80065996/152330531-45d828ab-53c6-482c-bc21-03c271ea1767.png)


# conclusion := we cannot compare even subtype from main data types


# int32 = rune, int8 -byte


![image](https://user-images.githubusercontent.com/80065996/152330845-6ab924b1-cb2b-458a-ad01-f85fcb898a7d.png)



# we cannot perform even mathematical operation (addition,subtraction,mulitplication,division) by using different data types. it will throw error


![image](https://user-images.githubusercontent.com/80065996/152331232-24060107-2a45-4a91-84eb-f471257f0598.png)


# Type conversion


![image](https://user-images.githubusercontent.com/80065996/152331684-b17cf3a5-d228-46f2-b95f-0ee5c718e622.png)


![image](https://user-images.githubusercontent.com/80065996/152331862-c3b9907b-9abc-4b54-b4ac-ac2041ba311b.png)


# custom type vs basic primitive types -- limitation of type conversion


![image](https://user-images.githubusercontent.com/80065996/152333164-597c66af-1aa7-4109-92e7-f441c3d3870f.png)


![image](https://user-images.githubusercontent.com/80065996/152333195-a2c4a222-2345-4f90-ac77-9c7f0c575a9f.png)


# type convert the custom type 


![image](https://user-images.githubusercontent.com/80065996/152334761-6675c9d2-f501-47dc-a1ca-c6a5345ba4d4.png)


![image](https://user-images.githubusercontent.com/80065996/152334786-df4add45-2508-4e60-8af2-a963fb883330.png)


# Defer  - executed at the last. in case of multiple defer statement it will be exected in LIFO fashion


![image](https://user-images.githubusercontent.com/80065996/152382224-53248fa2-1e88-4f6c-af84-9e7651f38504.png)


![image](https://user-images.githubusercontent.com/80065996/152382265-58da9b38-1870-43cf-a346-bf2029fa5840.png)


# 'defer' usage in panic and recover


![image](https://user-images.githubusercontent.com/80065996/152386406-985de4ed-e121-4604-8b06-2c74f6cacd62.png)


![image](https://user-images.githubusercontent.com/80065996/152389228-f7a526fc-ca8d-46e3-896e-a686edc1c4fb.png)



# if any 'defer' function executed before any panic statement, before the panic stack trace is printed. so we can use the logic to recover the panicked program


# recovering the panicked function instead of abending and printing stack trace


![image](https://user-images.githubusercontent.com/80065996/152483410-541d3edd-8b8c-4186-866e-0903586ef43e.png)


![image](https://user-images.githubusercontent.com/80065996/152483448-2cdf677a-6c45-4fe5-b8c5-c342abe42627.png)


# Simple method creation using custome data type with underlying primitive data type


![image](https://user-images.githubusercontent.com/80065996/152484899-deacd580-7dfd-46e5-afb1-98db51c121d8.png)


![image](https://user-images.githubusercontent.com/80065996/152484920-332ecde1-6947-4ef9-823d-d1e0b6387913.png)


# Method concept with struct - non pointer object case


![image](https://user-images.githubusercontent.com/80065996/152489898-2e769447-4e04-42b6-abdf-d394284b4b24.png)


![image](https://user-images.githubusercontent.com/80065996/152489916-b43022a2-7efa-4b5b-b0db-62df726894eb.png)


# Method concept with struct - pointer scenario


![image](https://user-images.githubusercontent.com/80065996/152490023-74c88d58-398c-4479-95af-82b27e2d59cd.png)


![image](https://user-images.githubusercontent.com/80065996/152490242-1651f71a-68b1-4247-99d9-835947689711.png)


# altering the value of object by using method and pointers


![image](https://user-images.githubusercontent.com/80065996/152492345-3f671686-e12b-4f1f-a7ca-aeb356ea27c4.png)


![image](https://user-images.githubusercontent.com/80065996/152492370-5b5529e3-a5a9-4757-b709-6bcfe828e794.png)


# passing value from non pointer to pointer method


![image](https://user-images.githubusercontent.com/80065996/152492701-90c27d4e-5fea-4116-9f41-44d049e5cdff.png)


![image](https://user-images.githubusercontent.com/80065996/152492729-e87e38ca-7067-47d5-a404-0fe900977458.png)


# passing value from non-pointer to non-pointer


![image](https://user-images.githubusercontent.com/80065996/152492808-4c98b402-b24a-414a-844d-91e17d0b6ea2.png)


![image](https://user-images.githubusercontent.com/80065996/152492840-e04b7eeb-f682-4c3d-8d45-26da0c1b527f.png)


# passing pointer to non-pointer method


![image](https://user-images.githubusercontent.com/80065996/152493113-2c810529-9153-425d-8477-e330db9054aa.png)


![image](https://user-images.githubusercontent.com/80065996/152493146-6c450747-8f86-4133-991b-76764c3a2cc6.png)


# Total method operation expectation
# Recieving method should be having pointer reciever in order to make any change to object created for a struct datatype


![image](https://user-images.githubusercontent.com/80065996/152493961-eaaa6709-4c9f-43fb-bd6d-4ed33f29108a.png)


# calling method from another method


![image](https://user-images.githubusercontent.com/80065996/152495319-73783ec1-d7f5-4029-b08c-53bb95b31168.png)


![image](https://user-images.githubusercontent.com/80065996/152495373-0bb585b4-f666-43ce-8309-9ddfc4e90ab3.png)


# Memory leak scenarios


# fmt package will create memory leak issue fmt.Println(). 
# Example


![image](https://user-images.githubusercontent.com/80065996/152550084-60173b70-a226-4e4a-95b0-73dd216216d9.png)


![image](https://user-images.githubusercontent.com/80065996/152550130-0d75de2a-a92d-4577-8d74-845a5357f382.png)


# you can see "s1" escapes to heap memory


# If golang is Garbage collected why do we need to really taking care of all these memory leaking performance considerations. 
# Answer is even if go is garbage collected, we should not put more pressure to garbage collector to collect the unused space. 
# if we do this, garbage collector will take more effort and time to remove unused space and thus it will slow the application performance

# one of the solution instead of using 'fmt' package is default 'println' to print any values instead of 'fmt.println'

# demo


![image](https://user-images.githubusercontent.com/80065996/152551391-d8c9f4d8-bb62-4dda-9dc1-2186c5cd28a0.png)


![image](https://user-images.githubusercontent.com/80065996/152551446-8a57d409-5170-41f7-97ba-55205fb5cabf.png)


# gc flag command to perform the escape analysis

# go build -gcflags "-m"


# Also use of strings can be more effective if we use buffer using strings builer


# https://go101.org/article/memory-leaking.html  - refer this link for efficient string operations


# demo of string operation with buffer


![image](https://user-images.githubusercontent.com/80065996/152554253-0013b04b-3351-4abc-91b6-bb656f717992.png)


![image](https://user-images.githubusercontent.com/80065996/152554690-ddb4d6c1-9cf5-42e6-887f-edd4b97f48a8.png)


# Note: if we use interface it will be stored in heap we cannot avoid that. Interface will always store in heap

# copy function reference : https://yourbasic.org/golang/copy-explained/


# Slice - what happend under the hood ?
# when we do slice operation within its length then underlying array will remain the same. 
# when we exceeeds the maximum capacity of slice, then it will grow := grow in the sense, new underlying array will be created and it will copy the old date
# to the new array and starts updating the extra value into new array. this is how slice grows. new array creation will be of formula cap*2


# copy function should be used only in the scenarios where your underlying array will not get altered


![image](https://user-images.githubusercontent.com/80065996/152578811-61a8e35e-517d-48fd-9bbf-5772a2ea60c8.png)


# we have to harcode the legnth and cap in destination slice then only copy() function will work



# interface - polymophism - type assertion (run time datatype check for interface) - interface passed as parameter to a function


![image](https://user-images.githubusercontent.com/80065996/152670141-09b83f2d-e907-433e-9919-35cb189d947f.png)


![image](https://user-images.githubusercontent.com/80065996/152670151-55b200cb-3f5a-43a4-853f-a59aa7840361.png)


![image](https://user-images.githubusercontent.com/80065996/152670159-f401bfcf-35c7-495e-8f48-38dc320a9018.png)


# Result:


![image](https://user-images.githubusercontent.com/80065996/152670174-4a302efb-15ea-46d3-8753-12d9cdf91c56.png)


# we can use type assertion only inside of 'switch' case statement. we cannot use it outside of switch case statement


![image](https://user-images.githubusercontent.com/80065996/152670833-65b03fe8-c23d-4c83-9ca2-af540e4e0800.png)


![image](https://user-images.githubusercontent.com/80065996/152670838-9fd06e36-f93f-487f-b16e-d821381dab52.png)


![image](https://user-images.githubusercontent.com/80065996/152670917-115e0eb0-7bcd-476c-9e54-4d4e927f4cee.png)



# interface variable 'a' is assigned with object 'p1' of class 'person' which implements interface 'human'.
# we can check the type of interface by using 'fmt.Printf' we cannot use type assertion outside of 'switch' construct


![image](https://user-images.githubusercontent.com/80065996/152670934-8b41a479-d28e-4b0f-8c55-ce38a876dd6d.png)


# notice when use type assertion outside of 'switch' construct, it throws the error


![image](https://user-images.githubusercontent.com/80065996/152671336-9e90c604-cfe0-47fe-9576-b45a092813cb.png)


![image](https://user-images.githubusercontent.com/80065996/152671376-9fbbcf50-815a-477e-a2e7-6e2f8660afc4.png)


# pointers

# pointer is the placeholder for storing address of another variable

# How pointer is working - see below diagram


![image](https://user-images.githubusercontent.com/80065996/152673010-9e475fe2-1949-47ed-bd02-aa1fc3ce3b5c.png)


![image](https://user-images.githubusercontent.com/80065996/152673017-e8d2b0b4-549b-4529-94c6-4f6fdbe08849.png)


![image](https://user-images.githubusercontent.com/80065996/152673033-1a774f5b-718a-42de-93ac-f067d38ccdf2.png)


![image](https://user-images.githubusercontent.com/80065996/152673047-a645e22b-4f44-4ddc-ac5a-fbc6cc548fa4.png)


# result:


![image](https://user-images.githubusercontent.com/80065996/152673057-f79912aa-145f-4149-b6b9-0939d71cf5e6.png)


# JSON marshal - converting golang structure to JSON - below is simple Example


![image](https://user-images.githubusercontent.com/80065996/152684024-1bfe0488-a6e7-4d48-b2ac-7ca8a2c76e37.png)


![image](https://user-images.githubusercontent.com/80065996/152684044-36fdb0a5-2a3b-40e3-ab40-e09000b90861.png)


# slight complex example,


![image](https://user-images.githubusercontent.com/80065996/152685009-21b611b8-89f3-4d1e-a26f-94acaacdeb3b.png)


![image](https://user-images.githubusercontent.com/80065996/152685024-7b55e267-57fb-4419-aa7e-9db22883a0bd.png)


# Result:


![image](https://user-images.githubusercontent.com/80065996/152685049-9c05090b-955a-434e-8e09-06753a1945ec.png)


# Another example of JSON Marshal


![image](https://user-images.githubusercontent.com/80065996/152685490-6efc7a79-f9fa-4a77-9c65-8579002555cc.png)


![image](https://user-images.githubusercontent.com/80065996/152685500-e57cd93c-532a-4fe2-a353-f5b3ead2bbb6.png)


# Result:


![image](https://user-images.githubusercontent.com/80065996/152685513-ae98122c-b655-4ffb-a9ce-59e09d2e63ee.png)


# Json Unmarshal - converting from JSON to Golang struct


# We can always use the website link to convert Json to Golang struct

# link for the website whic supports conversion : https://mholt.github.io/json-to-go/


![image](https://user-images.githubusercontent.com/80065996/152686018-a4e0b397-30d6-4e40-bdec-20992ec94835.png)


# Always paste the JSON without any spaces to get Golang struct. we got the struct structure of Golang


![image](https://user-images.githubusercontent.com/80065996/152686267-be282ecc-60cc-43e1-91f9-26045f6fe03c.png)


# result: we got golang struct


![image](https://user-images.githubusercontent.com/80065996/152686338-3a7202c6-45df-4c72-8517-d53e93a613d0.png)


# For Unmarshal - we can use map of key as 'string' type and value as 'empty interface' type instead of struct to achieve the same result


![image](https://user-images.githubusercontent.com/80065996/152686598-c5658f1c-d55b-4c7c-9399-1c43d0617215.png)


# result: Instead of struct everything converted to a map


![image](https://user-images.githubusercontent.com/80065996/152686727-661933a0-500b-4de1-98cc-37508e419e6e.png)


# putting the result in Notepad with indendation for clear view of result


![image](https://user-images.githubusercontent.com/80065996/152686702-4c64d5a7-960c-40eb-8ec8-8f4491a5c000.png)


# Json tag in struct


![image](https://user-images.githubusercontent.com/80065996/152690563-e60a9527-a190-4508-9308-125d6331baeb.png)


# Result:


![image](https://user-images.githubusercontent.com/80065996/152690577-b6c2f376-0caf-4a9e-a427-49ecfc3ac502.png)


#   JSON encoder and decoder reference link : https://medium.com/what-i-talk-about-when-i-talk-about-technology/go-code-snippet-json-encoder-and-json-decoder-818f81864614


# Json Encoder := sending reponse to client from server in form of JSON 
# Json Decoder := Decode the request "body" we sent via postman and store it in golang struct inside the server


# Avoid ioutil.Readall refer :=  https://haisum.github.io/2017/09/11/golang-ioutil-readall/


# Buffers in golang


# reference link := https://www.educba.com/golang-buffer/


# Buffer examples.


![image](https://user-images.githubusercontent.com/80065996/152746356-4ce789b3-4eae-494e-949d-61f85b5ed34f.png)


# Result:


![image](https://user-images.githubusercontent.com/80065996/152746386-79c545e1-e3c0-4319-8bcc-2256508fc1d4.png)


# creating a buffer - we need to use bytes.buffer package 
# var strbuffer bytes.Buffer

# writing to the buffer

# strbuffer.WriteString("Hai")   //writing a string to buffer
# strbuffer.WriteString(" ")     // writing another string to buffer
# strbuffer.WriteString("Hello") //writing another string to buffer
# strbuffer.WriteString(" ")     //writing another string to buffer
# strbuffer.WriteString("How")   //writing another string to buffer


# printing out values from buffer := fmt.Println("output from buffer :", strbuffer.String())


# we can reset the buffer after using it. if we did not reset the buffer, the contents will remain in there in the buffer. 
# also it depends on the use case whether to clear the contents of the buffer after using it. for clearing we need to check the use case


![image](https://user-images.githubusercontent.com/80065996/152749559-4efcc94c-1a5f-4503-aef8-2659484efcab.png)


# Result:


![image](https://user-images.githubusercontent.com/80065996/152749612-ac2a476e-4171-46a8-8aed-667445999908.png)


# length of the string identification
# we have to do with utf8 package


![image](https://user-images.githubusercontent.com/80065996/152750611-0666e19b-6038-4b31-ac72-50dc3824d3c4.png)


# Result:


![image](https://user-images.githubusercontent.com/80065996/152750657-9ca90007-8245-4520-a6a0-f07a43fc414c.png)


# Limitation in identifying the length of the string using len() method.


![image](https://user-images.githubusercontent.com/80065996/152751421-bba5af63-e13b-446f-93aa-8f658c1b3820.png)


# use any of the above symbol in our string and check the length using len() method

# first check with UTF8 package


![image](https://user-images.githubusercontent.com/80065996/152751790-05e3938c-272c-4eec-b3d5-f484100cf032.png)


# Result: UTF8 counted correctly


![image](https://user-images.githubusercontent.com/80065996/152751714-d461afee-7730-48c3-8fec-6edbea1ed049.png)


# using len() methood which gives number of bytes string is occupying


![image](https://user-images.githubusercontent.com/80065996/152752473-d22b5f55-36f7-446c-b400-ead09c9bb6e4.png)


# result:
# instead of 2 it gave 4 bytes because symbol occupy 4 bytes in the string


![image](https://user-images.githubusercontent.com/80065996/152752578-a3ade46f-ebd7-4aca-9c97-b06ac0674ddb.png)


# result:


![image](https://user-images.githubusercontent.com/80065996/152753255-cff98628-0b3f-4a62-b47e-1a442102b3a5.png)



# so to find length of the string we need to use utf8.RuneCountInString() function.
# to finf number of bytes in a string, we need to use len() function

# STRING IS MADE UP OF NUMBER OF UNICODE RUNES


![image](https://user-images.githubusercontent.com/80065996/152754987-7e590daf-a76a-4764-a6a0-273047e6019a.png)


# result: you can see utf8 encoded unicode values for runes below as part of resul


![image](https://user-images.githubusercontent.com/80065996/152755015-c6658732-c5ee-4145-aca2-769572fec3b9.png)


# since we can see only utf8 unicoded values, how to see string values?
# type convert it while printing similar to below


![image](https://user-images.githubusercontent.com/80065996/152756058-3c49daf1-cc6e-42f1-b802-283ffa795617.png)


# result:


![image](https://user-images.githubusercontent.com/80065996/152756105-e3040cd1-4954-4a05-a87f-fcfc46745a03.png)


# efficient string operation in golang
# strings are immutable in golang


![image](https://user-images.githubusercontent.com/80065996/152760275-706e0b9c-92dc-40c3-a7bf-eb3fc05e2931.png)


# below example indicates we can re-assign the string but we cannot mutate the value using index operations


![image](https://user-images.githubusercontent.com/80065996/152761096-c122e94a-0371-4bfc-863a-92b519c74fff.png)


# Result:


![image](https://user-images.githubusercontent.com/80065996/152761132-0de755fe-f1c4-4065-be00-01e9b45bd61b.png)


# Inefficient way of concatenating the string


![image](https://user-images.githubusercontent.com/80065996/152763151-5f8cb320-bea5-45d5-8855-a7ae972fe99e.png)


![image](https://user-images.githubusercontent.com/80065996/152763176-6f5a23e6-b8c0-4d05-ad3e-65bf4c66903f.png)


# same example in more efficient way using buffer


![image](https://user-images.githubusercontent.com/80065996/152766127-0938e674-fc66-4878-817c-bf97124c3f76.png)


# result:


![image](https://user-images.githubusercontent.com/80065996/152766169-1bd72ffb-d665-4c36-900d-0541313acce5.png)


# Tip : unless you find real problem in performance then dont do all these things on efficiency part


# Channels


![image](https://user-images.githubusercontent.com/80065996/152768246-91d38efb-f956-436d-9537-71ea1cc729cc.png)


![image](https://user-images.githubusercontent.com/80065996/152768269-9504efb9-fe00-4758-999e-0c116172aac0.png)


# dont's in channel
# we should not use variable of type channel and perform operations with it like below. it will throw 'nil' channel issue


![image](https://user-images.githubusercontent.com/80065996/152769211-622578d3-bdd7-47f1-9b7f-de304da2833f.png)


# Result issue


![image](https://user-images.githubusercontent.com/80065996/152769251-d6179a5b-fc56-41c9-8674-1f66f6837bb7.png)


# solution - how to avoid this -- use 'make' function always for channel


![image](https://user-images.githubusercontent.com/80065996/152770265-6f89075d-400b-47bc-8dbb-0bd8da3800d7.png)


# Result: worked fine


![image](https://user-images.githubusercontent.com/80065996/152770309-07b430c6-a2f1-4e44-8d6f-ea39b0b348da.png)


# Another multiple go routine example


![image](https://user-images.githubusercontent.com/80065996/152771557-c0c9a637-cecf-4d93-82f4-03bd43a1814b.png)


# Result:


![image](https://user-images.githubusercontent.com/80065996/152771994-d2b4ab0d-c3de-47ad-b3a4-0d559d4675c9.png)



# Wait groups - waitgroup waits for number of go-routines to finish. we can use this instead of channels


![image](https://user-images.githubusercontent.com/80065996/152810936-f7830dda-dcb2-4ef2-bd3d-e4d66d9aa9cf.png)


# Result:


![image](https://user-images.githubusercontent.com/80065996/152811002-d5ab0d14-c1a0-4a17-99fa-354b54b51a56.png)


#  Race condition check
# When Race condition will occur ? common shared variable will be accessable by many go routines. we will not be really sure which go routines runs first and last
# so we will get unexpected result


![image](https://user-images.githubusercontent.com/80065996/152812411-21a3859f-88a4-4d14-a163-6d649731404c.png)


# Result:

# you can see value of shared variable gets unexpected results everytime. 


![image](https://user-images.githubusercontent.com/80065996/152812655-c83dda7c-93eb-45a6-a369-8a75907a768e.png)


# command to identify race condition


# Solution := mutex lock and atomic 

# Mutex lock


![image](https://user-images.githubusercontent.com/80065996/152813922-192048de-8236-4657-b8ab-d65995442a11.png)


# Result: Now result is perfectly good regardless of how many times we have run the code as shown below.


![image](https://user-images.githubusercontent.com/80065996/152813988-1c77c46e-580c-41a5-8ebc-ec0061bc1ebf.png)



# Atomic - usage by example - note - we have explicit about type with respect to computer architecure - int,int64,uint,uint64


![image](https://user-images.githubusercontent.com/80065996/152816510-19d74cc0-7006-4aca-a955-d1a6908474ac.png)


# Result:


![image](https://user-images.githubusercontent.com/80065996/152816568-e4cf22d5-2352-4d4c-9909-74e632a5c4d7.png)




