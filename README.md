# Kanban Board

The Kanban Board is a web application built using React.js and React Bootstrap that allows users to manage and organize tickets based on different groupings and sorting criteria. The app provides a visual representation of tickets in columns, each representing a specific grouping (status, user ID, or priority). Users can easily add new tickets to the columns and interact with existing tickets.

## Features

- **Grouping and Sorting:** Users can group and sort tickets based on different criteria such as status, user ID, and priority. The app provides an intuitive interface for selecting these grouping and sorting options.

- **Ticket Visualization:** Tickets are visually represented in columns, allowing users to quickly identify and manage tickets based on their attributes.

- **Ticket Details:** Each ticket card displays relevant details such as title, priority, and status. The app also provides visual indicators for priority and status.

- **Add New Ticket:** Users can add new tickets to the columns by clicking the "Add" button. A modal window pops up to capture ticket details, such as title, priority, and status.

- **Responsive Design:** The app is designed to work seamlessly on both desktop and mobile devices, providing a consistent user experience across different screen sizes.

## Getting Started

### Prerequisites

- Node.js and npm (Node Package Manager) installed on your machine.

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Om-jannu/kanbanboard.git
   ```

2. Install project dependencies:

   ```bash
   npm install
   ```

### Usage

1. Start the development server:

   ```bash
   npm start
   ```

2. Open your web browser and go to `http://localhost:3000` to access the app.

### Configuration

- Modify the `groupOptions` and `sortOptions` arrays in `App.js` to customize the available grouping and sorting options.

- Customize the modal content in the `Board` component of `Board.js` to capture the desired ticket details.

## Contributors

- [Om Jannu](https://github.com/Om-jannu)


