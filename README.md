class SimpleCalculator:
    def add(self, a, b):
        return a + b

    def subtract(self, a, b):
        return a - b

# Example usage
calculator = SimpleCalculator()
result_add = calculator.add(5, 3)
result_subtract = calculator.subtract(10, 4)
print("Addition result:", result_add)
print("Subtraction result:", result_subtract)