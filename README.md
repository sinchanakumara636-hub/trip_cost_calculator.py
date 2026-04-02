# trip_cost_calculator.py
 CodeAlpha Python Internship - Task 1 submission
def calculate_cost(distance, mpg, cost_per_gallon):
    total_gallons = distance / mpg
    total_cost = total_gallons * cost_per_gallon
    return total_cost

distance = float(input("Enter distance: "))
mpg = float(input("Enter mileage (mpg): "))
cost_per_gallon = float(input("Enter cost per gallon: "))

trip_cost = calculate_cost(distance, mpg, cost_per_gallon)

print("Total trip cost:", trip_cost)
