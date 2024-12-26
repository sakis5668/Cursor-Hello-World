# CFE Main Website 🌐

A modern, responsive website built with cutting-edge web technologies. This is the main website for CFE, designed to provide an excellent user experience and showcase our services.

![Ubuntu](https://img.shields.io/badge/Ubuntu-24.04%20LTS-E95420?style=flat&logo=ubuntu&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=flat&logo=nginx&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E)

## 📋 Project Overview

This repository contains the source code for the CFE Main Website. The website features a modern design with responsive layouts, interactive elements, and optimized performance.

### 🎯 Key Features

- Responsive design that works on all devices
- Modern and clean user interface
- Fast loading times
- SEO optimized
- Contact form functionality
- Interactive pricing tables
- Sample components and layouts

## 🛠️ Tech Stack

- **Server**: Nginx
- **Frontend**: HTML5, CSS3, JavaScript
- **Hosting**: Ubuntu 24.04 LTS
- **Region**: Frankfurt, DE

## 🚀 Getting Started

### Prerequisites

- Nginx web server
- Git
- Basic knowledge of HTML/CSS/JavaScript

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sakis5668/Cursor-Hello-World.git
   ```

2. Navigate to the nginx web root:
   ```bash
   cd /var/www/my-website
   ```

3. Configure nginx:
   ```nginx
   server {
       listen 80;
       server_name your-domain.com;
       root /var/www/my-website;
       index index.html;
       
       location / {
           try_files $uri $uri/ =404;
       }
   }
   ```

4. Test and reload nginx:
   ```bash
   sudo nginx -t
   sudo systemctl reload nginx
   ```

## 📁 Project Structure

```
my-website/
├── index.html          # Home page
├── about.html          # About page
├── pricing.html        # Pricing information
├── contact.html        # Contact form
├── js/
│   └── main.js        # Main JavaScript file
└── samples/           # Component samples
    ├── nav-sample.html
    └── hero-sample.html
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Contact

- **Developer**: Sakis Tosounidis
- **Email**: sakis.tosounidis@gmail.com
- **GitHub**: [@sakis5668](https://github.com/sakis5668)

## 🙏 Acknowledgments

- Thanks to all contributors who have helped shape this project
- Special thanks to the open-source community for their invaluable tools and resources

---

Made with ❤️ by Sakis Tosounidis