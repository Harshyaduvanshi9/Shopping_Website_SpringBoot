# Shopping_Website_SpringBoot

# Shopping Website with Spring Boot



## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Authors](#authors)
- [Acknowledgments](#acknowledgments)

## Introduction

Welcome to our Shopping Website built with Spring Boot. This project aims to provide a seamless online shopping experience for users, allowing them to browse products, add items to their cart, and complete purchases. Our website is designed to be user-friendly and efficient, making it easy for both customers and administrators to navigate and manage.

## Features

- **User Authentication:** Users can create accounts, log in, and manage their profiles.
- **Product Catalog:** Browse a wide range of products with detailed descriptions and images.
- **Shopping Cart:** Add and remove items from the cart and proceed to checkout.
- **Order Management:** Place and track orders, view order history.
- **Admin Dashboard:** Administrators can manage products, categories, and user accounts.
- **Product Reviews:** Leave and read product reviews and ratings.
- **Secure Payments:** Integration with secure payment methods.
- **Responsive Design:** Accessible on various devices - desktop, tablet, and mobile.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following software installed:

- Java JDK ([Download](https://www.oracle.com/java/technologies/javase-downloads.html))
- Spring Boot ([Installation Guide](https://spring.io/projects/spring-boot))
- MySQL Database ([Download](https://dev.mysql.com/downloads/))
- Maven ([Download](https://maven.apache.org/download.cgi))

  
##Screenshots
-data:image/jpeg;base64,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
