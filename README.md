- import random 



def generate_random_number(min_value, max_value):

    """ 

    Generates a random integer between min_value and max_value (inclusive).

    """

    return random.randint(min_value, max_value) 



# Example usage

random_number = generate_random_number(1, 10) 

print(random_number) 
