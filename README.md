# data_types

# str
# int
# float
# boolean



height = input("enter your height in m: ")
weight = input("enter your weight in kg: ")

height_1 = float(height)
weight_1 = float(weight)

bmi = weight_1 / height_1 ** 2

print(f"Your BMI is {bmi}.")
