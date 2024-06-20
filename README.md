# Employee Attendance Dashboard

## Overview
The Employee Attendance Dashboard is a web page designed using HTML and CSS. It presents employee details and attendance information in a structured and visually appealing format.

## Features

### Main Container and Header
- The main content is wrapped in a `div` with the class `container_div`.
- The header section contains:
  - A title.
  - A dropdown for selecting the time period (This Year, This Month, This Week).
  - A button for downloading information.

### Employee Details
- Displays a user image and basic details such as:
  - Name
  - Role
  - Phone number
  - Email address
- Utilizes nested `div` elements to structure the content and apply styling.

### Attendance Summary
- Contains four blocks showing different metrics:
  - Total Attendance
  - Average Check-In Time
  - Average Check-Out Time
  - Employee Predictor
- Each block includes an image placeholder and textual details.

### Attendance History
- Another container shows attendance records for specific dates.
- Each record displays:
  - Date
  - Status (On Time, Late, Absent)
  - Check-in time
  - Check-out time
- Utilizes a grid layout to arrange the history items.

### Pagination
- Pagination controls are provided at the bottom of the attendance history section for navigation.

### External Scripts
- Includes links to Popper.js and Bootstrap JavaScript libraries for additional functionality and styling.

### CSS Classes and Structure
- Extensive use of CSS classes (`container_div`, `container_head`, `moni_div`, etc.) for styling.
- The layout is responsive with various grid classes for different screen sizes (`col-12`, `col-sm-12`, `col-md-6`, etc.).

## Overall Structure
The HTML structure is organized and follows a consistent pattern for presenting employee details and attendance information, ensuring a clear and user-friendly interface.

## Links
- [GitHub Repository](https://github.com/askarthi1611/emb)
- [Live Version](https://ask-user.onrender.com)
