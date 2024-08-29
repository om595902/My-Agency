# My Agency

**Documentation Language**: This project’s documentation is exclusively in Arabic.

## Overview
**My Agency** is a software system specifically designed for a travel and tourism organization. The system aims to enhance information management and operational processes within the organization by providing effective tools for organized and secure data management. 

The system is built using modern technologies and follows an Agile development methodology, allowing for continuous improvements and updates based on user feedback.

---

## Project Destinations Screenshots

<div id="carousel" class="carousel">
  <div class="slides">
    <img src="path/to/screenshot1.png" alt="Screenshot 1">
    <img src="path/to/screenshot2.png" alt="Screenshot 2">
    <img src="path/to/screenshot3.png" alt="Screenshot 3">
    <!-- Add more images as needed -->
  </div>
  <button class="prev" onclick="prevSlide()">&#10094;</button>
  <button class="next" onclick="nextSlide()">&#10095;</button>
</div>

<style>
.carousel {
  position: relative;
  max-width: 600px;
  margin: auto;
}

.slides {
  display: flex;
  overflow: hidden;
}

.slides img {
  width: 100%;
  transition: transform 0.5s ease;
}

.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

.prev:hover, .next:hover {
  background-color: rgba(0, 0, 0, 0.8);
}
</style>

<script>
let currentSlide = 0;

function showSlide(index) {
  const slides = document.querySelector('.slides');
  const totalSlides = document.querySelectorAll('.slides img').length;
  currentSlide = (index + totalSlides) % totalSlides;
  slides.style.transform = 'translateX(' + (-currentSlide * 100) + '%)';
}

function nextSlide() {
  showSlide(currentSlide + 1);
}

function prevSlide() {
  showSlide(currentSlide - 1);
}
</script>

---

## System Analysis and Development

### Requirements Analysis
The project began with the requirements analysis phase, where the primary needs of the system were identified. Through a comprehensive study of these requirements, the system was divided into four main sections, helping to distribute the work and facilitate the management of the development process.

...

## Conclusion

**My Agency** is a system for managing daily operations in a travel and tourism organization. The system has achieved significant improvements in information management, leading to higher efficiency and reduced errors. Its flexible design ensures scalability for future development and helps meet the changing needs of the organization over time.


## System Analysis and Development

### Requirements Analysis
The project began with the requirements analysis phase, where the primary needs of the system were identified. Through a comprehensive study of these requirements, the system was divided into four main sections, helping to distribute the work and facilitate the management of the development process.

---

### Sections:

#### 1. Database Analysis and Design
- The first part of the system was focused on designing the database to ensure efficient data storage and retrieval.
- The tables and relationships were designed based on the organization’s requirements, with flexibility for future modifications and expansions in mind.

#### 2. Interface Design and User Experience
- After setting up the database, the user interfaces for the first section were designed.
- The design emphasized ease of use and a smooth user experience.
- The system was tested after each development phase to ensure it met the organization’s requirements.

---

## Agile Development Methodology

The project adopted the Agile development methodology, dividing the project into smaller phases that could be implemented and tested independently. This approach:
- Accelerated the development process.
- Improved the final product’s quality.
- Allowed continuous interaction with users and updates based on their feedback.

---

## Key Features and Characteristics

#### 1. Efficient Data Management and Storage
- The system provides advanced tools for efficiently storing and retrieving data in the database.
- Regular backup copies are easily restored via SQL files.

#### 2. Excel Import and Export
- Export table contents to Excel files and import them to avoid manual data re-entry.

#### 3. Alerts and Notifications System
- Customizable alerts based on data in tables.
- Alerts can be set with specific activation times and configurations.

#### 4. Financial Accounts Management
- Comprehensive management of financial operations such as:
  - Recording costs (purchase/sale costs)
  - Cash supply and export
  - Deductions from accounts in accordance with accounting principles.

#### 5. Integrated Support for Financial Import and Export Processes
- Supports cash import/export tracking.
- Ensures accurate fund movement recording in line with approved accounting principles.

---

## Interfaces and Technologies Used

The system includes approximately **60 user interfaces** developed using the following technologies:

- **PHP**: For backend programming and request processing.
- **JavaScript**: For adding interactivity to the interfaces.
- **MySQL**: For database management.
- **Metro UI**: For modern and attractive user interface design.
- **HTML/CSS**: For interface styling and design.

---

## Conclusion

**My Agency** is a system for managing daily operations in a travel and tourism organization. The system has achieved significant improvements in information management, leading to higher efficiency and reduced errors. Its flexible design ensures scalability for future development and helps meet the changing needs of the organization over time.
