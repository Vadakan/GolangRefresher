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
