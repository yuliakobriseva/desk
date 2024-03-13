# desk
class Desk:
    def __init__(self, material, color, width, height, depth):
        self.material = material
        self.color = color
        self.width = width
        self.height = height
        self.depth = depth

    def display_info(self):
        print("Desk Information:")
        print(f"Material: {self.material}")
        print(f"Color: {self.color}")
        print(f"Width: {self.width} inches")
        print(f"Height: {self.height} inches")
        print(f"Depth: {self.depth} inches")

# Example usage
if __name__ == "__main__":
    # Creating an instance of the Desk class
    my_desk = Desk(material="Wood", color="Brown", width=48, height=30, depth=24)

    # Displaying information about the desk
    my_desk.display_info()
