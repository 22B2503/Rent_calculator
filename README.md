# Rent_calculator
rent=int(input("Enter the rent amoount = "))
food=int(input("Enter food amount ="))
electricity_spend = int(input("Enter the total electricity spend ="))
charge_per_unit=int(input("Enter charge per unit ="))
persons=int(input("Enter no of persons living ="))

total_bill= electricity_spend  * charge_per_unit

output=(rent + food + total_bill) //persons

print("Each persons will pay=",output)
