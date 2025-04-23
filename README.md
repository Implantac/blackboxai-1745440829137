
Built by https://www.blackbox.ai

---

```markdown
# Use Hotel - Sistema de Gestão Hoteleira

## Project Overview
Use Hotel is a comprehensive hotel management system designed to facilitate the management of hotel operations such as client registration, reservations, finances, and inventory management. The application offers a user-friendly interface and utilizes modern web technologies for an optimal user experience.

## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/use-hotel.git
   ```
2. Navigate to the project directory:
   ```bash
   cd use-hotel
   ```
3. Open `index.html` or any other HTML file in your web browser.

**Note:** No additional installation is required for the front-end part as it runs directly in the browser. Ensure you have an internet connection for the libraries sourced from CDN.

## Usage
- **Login:** Start by logging in to the application using the username and password (default: admin/admin).
- **Navigate:** Explore various sections of the system via the navigation menu, which includes options like Home, Clients, Reservations, Parking, Accommodations, Stock, and Financial Management.
- **Manage Items:** Add, edit, or delete clients, reservations, and stock items within their respective sections.

## Features
- **User Authentication:** Login functionality for secure access to the management system.
- **Dashboard:** A dashboard displaying real-time statistics of guests, accommodations, bookings, and finances.
- **Manage Clients:** Add, edit, and delete client information.
- **Reservations:** Handle bookings effectively with options to add new reservations.
- **Financial Tracking:** Manage expenses and revenues generated from hotel services.
- **Responsive Design:** The application is designed to be used seamlessly on desktop and mobile devices.

## Dependencies
The project utilizes the following dependencies:
- [Tailwind CSS](https://tailwindcss.com) (CDN link)
- [jQuery](https://jquery.com) (CDN link)
- [jQuery Mask Plugin](https://github.com/igorescobar/jQuery-Mask-Plugin) (CDN link for input masking)
- [FontAwesome](https://fontawesome.com) (CDN link for icons)
- [Boxicons](https://boxicons.com) (CDN link for icons)

## Project Structure
```
/use-hotel
├── index.html                  # Login page
├── home.html                   # Main dashboard after login
├── clientes.html               # Client management page
├── reservas.html               # Reservation management page
├── estacionamento.html          # Parking management page
├── acomodacoes.html            # Accommodations management page
├── estoque.html                # Inventory management page
├── frigobar.html               # Frigobar management page
├── financeiro.html             # Financial management page
├── pagamentos.html             # Payment management page
├── configuracoes.html          # Hotel configuration page
└── tailwind.config.js          # Tailwind CSS configuration
```

Each HTML file corresponds to a different functional module of the hotel management system, ensuring both maintainability and scalability.

## Contributing
If you want to contribute to this project, feel free to fork the repository and submit a pull request.

## License
This project is open-source and available under the MIT License. Feel free to modify the code to fit your own requirements.
```

### Notes:
- Ensure to replace `yourusername` in the clone command with your actual GitHub username if you choose to host this project on GitHub. 
- Additional features and installation instructions can be added based on further development or package requirements.
- Maintaining updated documentation is crucial as new features are added.