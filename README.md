# Downtime Dashboard - Excel Analytics

A modern, interactive web dashboard for analyzing downtime events from Excel data. This single-page application allows you to import or paste Excel data and automatically generates a comprehensive dashboard with real-time filtering and analytics.

## Features

### Data Import
- **File Upload**: Drag & drop or click to upload Excel files (.xlsx, .xls, .csv)
- **Paste Data**: Copy data from Excel and paste directly into the application
- **Smart Column Detection**: Automatically detects column mappings based on common naming patterns
- **Sample Data**: Load sample data to explore the dashboard features

### Dashboard Analytics
- **Stats Overview**: Total events, total downtime, average duration, and unique event codes
- **Interactive Bar Chart**: View downtime by event code (by duration or count)
- **Timeline Chart**: Visualize downtime trends over time with dual-axis display
- **Top 5 Downtime Events**: Quick view of the most impactful downtime events

### Filtering & Search
- **Date/Time Range Filter**: Filter events by start and end date/time
- **Event Code Filter**: Filter by specific event codes
- **Real-time Search**: Search through event descriptions with instant updates
- **Click-to-Filter**: Click on top downtime events to filter the view

### Interactive Features
- **Expandable Bar Details**: Click on chart bars to see detailed event information
- **Sortable Event Table**: Browse all events with pagination
- **Calculated End Times**: Automatically calculates end time from start time + duration
- **Duration Visualization**: Visual duration bars in the event table

### Design
- **Dark/Light Mode**: Toggle between dark and light themes
- **Modern UI**: Clean, professional design with smooth animations
- **Responsive Layout**: Works on desktop and mobile devices
- **Animated Background**: Subtle gradient animations for visual appeal

## Getting Started

1. Open `index.html` in a modern web browser
2. Upload an Excel file, paste data, or load sample data
3. Map your columns to the required fields:
   - Event Code
   - Event Description
   - Start Time
   - Duration
4. Explore your data with the interactive dashboard

## Excel Data Format

Your Excel data should include columns for:
- **Event Code**: Unique identifier for the event type (e.g., "ERR001")
- **Event Description**: Human-readable description of the event
- **Start Time**: When the event occurred (various date/time formats supported)
- **Duration**: Length of the event (minutes, or formats like "1h 30m", "01:30:00")

## Technologies Used

- **SheetJS (xlsx)**: Excel file parsing
- **Chart.js**: Interactive charts and visualizations
- **Pure CSS**: No CSS framework dependencies
- **Vanilla JavaScript**: No JavaScript framework required

## Browser Support

Works in all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## License

MIT License
