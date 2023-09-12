# AirBnB Clone

**Description of the Project:**

The AirBnB Clone project is a simplified, text-based version of the popular Airbnb platform. It is designed to simulate the basic functionality of Airbnb, allowing users to create, manage, and book property listings. This project is intended for educational purposes and provides a Command Line Interface (CLI) for interaction.

**Description of the Command Interpreter:**

The Command Interpreter is a crucial component of the AirBnB Clone project. It acts as the main interface between the user and the system, enabling users to perform various operations, such as creating properties, searching for properties, booking stays, and managing user accounts.

**How to Start It:**

1. Clone the repository:

   ```
   git clone https://github.com/yourusername/AirBnB_clone.git
   ```

2. Navigate to the project directory:

   ```
   cd AirBnB_clone
   ```

3. Start the command interpreter:

   ```
   ./console.py
   ```

**How to Use It:**

Once the command interpreter is running, you can use a variety of commands to interact with the AirBnB Clone system. Here are some of the available commands:

- `create`: Create a new instance of a property or user account.
  ```
  create User
  ```

- `show`: Display detailed information about a specific property or user.
  ```
  show User 12345
  ```

- `all`: List all available properties or users.
  ```
  all User
  ```

- `update`: Update the information of a property or user.
  ```
  update User 12345 name "John Doe"
  ```

- `destroy`: Delete a property or user from the system.
  ```
  destroy Property 54321
  ```

- `search`: Search for properties based on specific criteria.
  ```
  search Property city "San Francisco"
  ```

- `book`: Book a stay at a specific property.
  ```
  book Property 12345 2023-10-15 2023-10-20
  ```

- `quit` or `EOF`: Exit the command interpreter.

**Examples:**

1. Creating a new user:
   ```
   create User
   ```

2. Listing all properties:
   ```
   all Property
   ```

3. Updating a user's information:
   ```
   update User 12345 name "Alice Smith"
   ```

4. Booking a stay at a property:
   ```
   book Property 54321 2023-09-20 2023-09-25
   ```

5. Searching for properties in a specific city:
   ```
   search Property city "New York"
   ```

6. Quitting the command interpreter:
   ```
   quit
   ```

Feel free to explore the various commands and functionalities of the AirBnB Clone project using the command interpreter. Enjoy your virtual Airbnb experience!
