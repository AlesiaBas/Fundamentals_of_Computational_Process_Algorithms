def calculate_tip(total_amount, tip_percentage):
    return total_amount * (tip_percentage / 100)

def get_valid_input(prompt, input_type):
    while True:
        try:
            value = input_type(input(prompt))
            if value < 0:
                print("Value cannot be negative. Please try again.")
            else:
                return value
        except ValueError:
            print("Invalid format. Please try again.")

total_amount = get_valid_input("Enter the total amount (in xx.xx format): $", float)
tip_percentage = get_valid_input("Enter the tip percentage (in yy format): %", float)

tip = calculate_tip(total_amount, tip_percentage)


print(f"Tips are: ${tip:.2f}")

