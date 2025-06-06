# Student Accommodation System

A web platform for NSBM students and landlords to post, find, and manage student accommodation. Built with PHP, HTML, CSS, and JavaScript.

![Project Banner](assets/images/1.png)

---

## 🚀 Features

- 🏠 **Property Listings:** Browse, search, and filter available accommodations.
- 📝 **Landlord Portal:** Landlords can add, edit, and manage their property listings.
- 👤 **Student Portal:** Students can view, request, and save properties.
- 🔒 **Authentication:** Secure login/register for students, landlords, and admins.
- 🗺️ **Map Integration:** Visualize property locations on a map.
- 📰 **Blog Section:** Admins can post and manage blog articles.
- 📷 **Image Uploads:** Upload and preview property images.
- 📱 **Responsive Design:** Works on desktop and mobile devices.

---

## 📂 Project Structure

```
assets/           # Images and static assets
fonts/            # Custom fonts and icons
public/           # Public entry point (index.php)
src/
  controller/     # PHP controllers
  model/          # Database models and utilities
  view/           # HTML/PHP views and styles
```

---

## 🛠️ Getting Started

### Prerequisites

- PHP 7.4+
- MySQL/MariaDB
- Web server (Apache/Nginx recommended)

### Installation

1. **Clone the repository**
    ```sh
    git clone https://github.com/yourusername/student-accommodation-system.git
    cd student-accommodation-system
    ```

2. **Set up the database**
    - Import the provided SQL file (if available) into your MySQL server.
    - Update database credentials in `src/model/dbutil.php`.

3. **Configure your web server**
    - Set the document root to the `public/` or `src/view/` directory as needed.

4. **Install dependencies**
    - (If you use Composer or npm, add instructions here.)

---

## 💻 Usage

- Visit the site in your browser.
- Register as a student or landlord.
- Landlords can post new accommodations.
- Students can browse and request accommodations.
- Admins can manage users and blog posts.

---

## 📸 Screenshots

| Home Page | Property Listing | Add Post | Profile |
|-----------|-----------------|----------|---------|
| ![](assets/images/1.png) | ![](assets/images/2.png) | ![](assets/images/3.png) | ![](assets/images/4.png) |

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋‍♂️ Contact

For questions or support, please open an issue or contact [your-email@example.com](mailto:your-email@example.com).

---

## ⭐ Acknowledgements

- [Material Design Iconic Font](https://zavoloklom.github.io/material-design-iconic-font/)
- [Poppins Font](https://fonts.google.com/specimen/Poppins)
- [Ionicons](https://ionic.io/ionicons)

---

> _Empowering NSBM students and landlords to connect easily and securely!_
