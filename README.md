class Rectangle:
    def __init__(self, length: int, width: int):
        self.length = length
        self.width = width
if __name__ == "__main__":
    rect = Rectangle(10, 5)
    for dimension in rect:
        print(dimension)
