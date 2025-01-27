
# Online Ticket Sales System

## Overview
The **Online Ticket Sales System** is a Python-based application designed to simulate the process of buying and canceling tickets for concerts. It utilizes a simple architecture divided into three modules: `Agents`, `Events`, and `Example`. This modular approach ensures code readability, reusability, and ease of maintenance.

### Key Features
- User registration with unique IDs, names, and emails.
- Concert management, including adding new events with ticket availability.
- Ticket purchase and cancellation functionality.
- Event-based communication system to handle purchase and cancellation requests.
- Simple command-line interface (CLI) for user interaction.

---

## Why Use This Project?
This project is perfect for:
- **Developers** who want to understand event-driven programming in Python.
- **Beginners** learning modular design and Python fundamentals.
- **Educators** looking for a hands-on example to teach basic programming concepts.
- **Hobbyists** interested in experimenting with ticketing systems.

---

## Installation Guide
### Prerequisites
- Python 3.7 or later installed on your system.

### Steps to Set Up
1. **Download the Repository**
   - Click the "Code" button on the repository page.
   - Download the ZIP file and extract it to your desired directory.

2. **Install Required Dependencies**
   - This project does not require any external libraries. Ensure Python is installed correctly.

3. **Run the Application**
   - Open a terminal or command prompt.
   - Navigate to the directory where you extracted the files.
   - Run the following command:
     ```bash
     python example.py
     ```

---

## How to Use
Once the application starts, you will be presented with a simple menu:
1. **Register Users**: The system allows you to register users with unique IDs.
2. **Add Concerts**: Create concerts with specific dates and ticket quantities.
3. **Buy Tickets**: Users can request tickets for a specific concert.
4. **Cancel Tickets**: Users can cancel their previously purchased tickets.
5. **Process Events**: Handles purchase and cancellation requests in the communication queue.
6. **Exit**: Close the application.

Follow the prompts to interact with the system.

---

## Project Structure
- **`agents.py`**: Contains classes for `User`, `Concert`, and `TicketPlatform`. It handles user management, concert management, and event processing.
- **`events.py`**: Defines event classes such as `TicketPurchaseRequestEvent`, `TicketCancellationEvent`, and their confirmation counterparts. Includes a shared communication queue for event handling.
- **`example.py`**: Implements the command-line interface for user interaction and serves as the entry point to the application.

---

## Example Usage
1. Register a user:
   ```
   Enter User ID: 1
   Enter User Name: Alice
   Enter Email: alice@example.com
   ```
   Output:
   ```
   User Alice registered successfully!
   ```

2. Add a concert:
   ```
   Enter Concert ID: 101
   Enter Concert Name: Rock Fest
   Enter Concert Date: 2025-05-10
   Enter Total Tickets: 100
   ```
   Output:
   ```
   Concert 'Rock Fest' added with 100 tickets.
   ```

3. Buy tickets:
   ```
   Enter User ID: 1
   Enter Concert ID: 101
   Enter Number of Tickets: 2
   ```
   Output:
   ```
   Event ticket_purchase_request emitted by Alice!
   2 tickets confirmed for User 1.
   ```

---

## Contribution
Contributions are welcome! If you find any issues or have suggestions for improvement:
1. Fork the repository.
2. Make your changes.
3. Submit a pull request.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contact
For any inquiries or support, please reach out via the [GitHub Issues](https://github.com/your-username/Ticket_sale/issues) section.

---
Also you can check the blogpost about it : https://medium.com/@can.aydogan.2004/revolutionizing-online-ticket-sales-bridging-gaps-with-efficient-systems-84157334e2b4
Thank you for using the **Online Ticket Sales System**! Happy coding! 🎟️

