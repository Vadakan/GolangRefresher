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



