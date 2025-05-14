# python-week-5

activity 1 

# Base class
class Vehicle:
    def move(self):
        print("The vehicle is moving...")

# Subclass for Car
class Car(Vehicle):
    def move(self):
        print("Driving 🚗")

# Subclass for Plane
class Plane(Vehicle):
    def move(self):
        print("Flying ✈️")

# Subclass for Boat
class Boat(Vehicle):
    def move(self):
        print("Sailing 🚢")

# Demonstrating polymorphism
vehicles = [Car(), Plane(), Boat()]

for v in vehicles:
    v.move()


 activity 2 

 # Base class
class Vehicle:
    def move(self):
        print("The vehicle is moving...")

# Subclass for Car
class Car(Vehicle):
    def move(self):
        print("Driving 🚗")

# Subclass for Plane
class Plane(Vehicle):
    def move(self):
        print("Flying ✈️")

# Subclass for Boat
class Boat(Vehicle):
    def move(self):
        print("Sailing 🚢")

# Demonstrating polymorphism
vehicles = [Car(), Plane(), Boat()]

for v in vehicles:
    v.move()




