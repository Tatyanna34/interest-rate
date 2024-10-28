# interest-ratedef calculate_simple_interest(principal, rate, time):
    """
    Calculate the simple interest based on the principal, rate, and time.

    Parameters:
    - principal (float): The initial amount of money.
    - rate (float): The interest rate (as a percentage).
    - time (float): The time period the money is invested or borrowed for.

    Returns:
    - float: The calculated simple interest.
    """
    simple_interest = (principal * rate * time) / 100
    return simple_interest

# Example usage:
principal = float(input("Enter the principal amount: "))
rate = float(input("Enter the interest rate (%): "))
time = float(input("Enter the time period (years): "))

interest = calculate_simple_interest(principal, rate, time)
print(f"The simple interest is: {interest}")
