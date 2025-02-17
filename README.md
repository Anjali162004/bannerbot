 
# Next.js Ad Banners Project

Welcome to the Next.js Ad Banners Project! This project is a Next.js application built with TypeScript that displays a list of ad banners on the homepage. It includes functionality to edit these banners through a bottom sheet interface. The banners are powered by a JSON list and include various elements such as title, description, CTA (Call-to-Action), image, and background/template.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation) 
- [Components](#components)
- [JSON Structure](#json-structure)
- [Best Practices](#best-practices) 

## Introduction

This project demonstrates how to build a feature-rich, modular, and maintainable web application using Next.js and TypeScript. It showcases a list of ad banners that can be dynamically edited through a user-friendly interface. This project is ideal for learning or demonstrating advanced frontend development practices.

## Features

- **Next.js with TypeScript**: Provides type safety and an enhanced development experience.
- **Dynamic Ad Banners**: Displays a list of ad banners fetched from a JSON file.
- **Edit Functionality**: Allows users to edit banner details via a bottom sheet interface.
- **Modular Components**: Reusable components designed for maintainability and scalability.
- **Professional UI**: A clean and polished user interface.

## Tech Stack

- **Next.js**: Framework for server-rendered React applications.
- **TypeScript**: Superset of JavaScript that adds type safety.
- **React**: Library for building user interfaces.
- **Tailwind CSS Modules**

## Installation

To get started with this project, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/Anjali162004/bannerbot.git
   ```

2. **Navigate to the project directory**:
   ```sh
   cd bannerbot
   ```

3. **Install the dependencies**:
   ```sh
   npm install
   ```

4. **Run the development server**:
   ```sh
   npm run dev
   ```

5. **Open your browser**:
   Go to [http://localhost:3000](http://localhost:3000) to view the project.

## Usage

1. **Home Page**: Displays a list of ad banners with their respective title, description, CTA, image, and background/template.
2. **Edit Functionality**: Click the edit icon on any ad banner to open a bottom sheet. Modify the details and save to update the banner.
3. 
## Components

### BannerImageComp

A reusable component for displaying ad banners. This component includes:

- **Title**: The title of the ad banner.
- **Description**: A brief description of the ad.
- **Call-to-Action (CTA)**: A button or link for user interaction.
- **Image**: Visual representation of the ad.
- **Background/Template**: Styling background for the ad banner.
- **Edit Icon**: An icon to open the edit interface.

### EditBannerTemplateBs

A component for the bottom sheet edit functionality. This component includes:

- **Input Fields**: Fields for modifying banner details (title, description, CTA, image, background/template).
- **Save Button**: Button to save changes and update the banner.

## JSON Structure

The ad banners are powered by a JSON list. The structure of the JSON file (e.g., `banners.json`) is as follows:

```json
[
  {
    "id": 1,
    "title": "Ad Banner 1",
    "description": "This is the first ad banner.",
    "cta": "Learn More",
    "image": "/images/banner1.jpg",
    "background": "#f0f0f0"
  },
  {
    "id": 2,
    "title": "Ad Banner 2",
    "description": "This is the second ad banner.",
    "cta": "Buy Now",
    "image": "/images/banner2.jpg",
    "background": "#e0e0e0"
  }
]
```
