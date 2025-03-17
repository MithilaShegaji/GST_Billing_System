# GST Billing Dashboard

A web-based GST Billing Dashboard designed to manage business and consumer invoices with ease. This project includes features for handling parties, creating invoices, and analyzing business performance.

## Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About the Project
This GST Billing Dashboard streamlines the process of creating, managing, and tracking invoices for both businesses (B2B) and consumers (B2C). It provides detailed insights into sales, profits, and tax calculations.

## Features
- Add and manage parties (businesses/consumers).
- Create and manage business invoices (B2B).
- Create and manage consumer invoices (B2C).
- Dashboard overview with total business done, B2B/B2C profit analysis, and tracking.
- GST calculation for invoices.
- Responsive UI with Bootstrap.

## Technologies Used
- HTML, CSS, Bootstrap
- JavaScript
- PHP (Blade Templates for Laravel)
- MySQL (for data storage)

## Installation
1. Clone the repository:
```bash
git clone https://github.com/your-username/gst-billing-dashboard.git
```
2. Navigate to the project directory:
```bash
cd gst-billing-dashboard
```
3. Install dependencies:
```bash
composer install
npm install
```
4. Set up environment variables:
```bash
cp .env.example .env
php artisan key:generate
```
5. Migrate the database:
```bash
php artisan migrate
```
6. Run the development server:
```bash
php artisan serve
```

## Usage
1. Access the app at `http://localhost:8000`.
2. Navigate through the dashboard to manage parties, create invoices, and view analytics.

## Screenshots
- **Home:**
![image](https://github.com/user-attachments/assets/a54e77c1-8c4a-469f-bb7d-29d5da05fd80)

![image](https://github.com/user-attachments/assets/2c5b541d-0889-413b-a5ad-42f68151b9b2)

- **Dashboard:**
![image](https://github.com/user-attachments/assets/b59034ea-b47f-470a-b9a7-e7487fd91b8c)

- **Add Party:**
![image](https://github.com/user-attachments/assets/e33e9787-6c24-4576-b258-271c2c99eb0b)


- **Manage Party:**
![image](https://github.com/user-attachments/assets/838c04b7-5869-4edd-9319-82fc7bd9065f)


- **Create Business Invoice:**![image](https://github.com/user-attachments/assets/98f0d4f8-a76b-4517-8b8e-cef45a171893)

- **Manage Business Invoice:**![image](https://github.com/user-attachments/assets/745beae8-4f30-4b00-a6a4-672bb05ec3e8)

- **Create Consumer Invoice:**![image](https://github.com/user-attachments/assets/c9f262b1-4837-47e6-a69a-c5f1069e85c7)

- **Manage Consumer Invoice:**![image](https://github.com/user-attachments/assets/00aaece8-4877-4fcd-9b97-8effa3b926d8)

- **Print Bills:** ![image](https://github.com/user-attachments/assets/ddcc8285-c30a-423f-8cd5-bb75d3b4710d)

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the project.
2. Create a feature branch (`git checkout -b feature/YourFeature`).
3. Commit changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License
This project is licensed under the MIT License.

## Contact
Your Name - Mithila

