def main():
    print("This program finds the cost per square inch of a circular pizza")

    dia = eval(input("Please enter the diameter of the pizza: "))
    cost = eval(input("Please enter the price of the pizza: "))
    r = dia / 2
    area = (pi * r**2)
    print("The cost per square inch of the pizza is", round(cost/area, 2), "cents")

main()
