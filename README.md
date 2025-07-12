# github-final-project

def simple_interest(p, t, r):
    """
    Calculate simple interest.

    Parameters:
        p (float): Principal amount
        t (float): Time period in years
        r (float): Annual rate of interest (as a decimal, e.g., 5% = 0.05)

    Returns:
        float: Simple interest
    """
    return p * t * r

# Example
principal = 1000
time = 2
rate = 0.05  # 5%

interest = simple_interest(principal, time, rate)
print(f"Simple Interest: {interest}")

