# Product List and Detail App
This is a simple Flutter application that displays a list of products and their details. The app demonstrates the use of both full and shallow widget trees and is organized in a clean, scalable project structure.

# Features
Product List Screen: Displays a list of products with their title and price.
Product Detail Screen: Shows detailed information about a product, including an image, title, description, and price.
Clean Architecture: Organized into folders for models, screens, and widgets for better scalability and code management.
Navigation: Tapping on a product in the list navigates to a new screen displaying the product's details.
# Folder Structure
# 1. Models (lib/models/)
Contains the data model for the products. The Product class holds information such as title, description, price, and image URL.

# 2. Screens (lib/screens/)
Product List Screen: Displays a list of products using a ListView.builder().
Product Detail Screen: When a product is tapped, the app navigates to this screen, displaying the full product details using a full widget tree approach.
# 3. Widgets (lib/widgets/)
Product Tile: A reusable widget that represents an individual product in the list. It is used in the Product List Screen and separates concerns, making the widget tree shallow.
# Project Explanation
Shallow Widget Tree: Implemented in the Product List Screen, where complex widgets are broken down into smaller components such as ProductTile.
Full Widget Tree: Implemented in the Product Detail Screen, where all elements like image, title, description, and price are embedded in a single Column widget.

# Screenshots
![image 1](https://github.com/user-attachments/assets/69f034e2-b736-43a6-9126-9fce7c801433)
![image 2](https://github.com/user-attachments/assets/723e4a7e-371f-43b3-9b75-cba75c24e83c)

# Getting Started
To get a local copy up and running, follow these simple steps.

# Prerequisites
Ensure you have Flutter installed on your system. You can check by running:

flutter --version

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
