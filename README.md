# PDF Data Scrapping

## Description
An automated RPA (Robotic Process Automation) solution built with UiPath for extracting data from PDF documents. This project provides a workflow-based approach to scrape and process information from PDF files.

## Project Details
- **Project Type**: UiPath RPA Process
- **Studio Version**: 19.12.0.61
- **Framework**: Legacy
- **Expression Language**: VisualBasic

## Dependencies
- UiPath.Excel.Activities (2.8.0-preview)
- UiPath.Mail.Activities (1.8.0-preview)
- UiPath.System.Activities (19.12.0-preview)
- UiPath.UIAutomation.Activities (20.4.1)

## Features
- Automated PDF data extraction
- Workflow-based processing
- Support for unattended execution
- User interaction capabilities
- Configurable execution settings

## Runtime Configuration
- **Auto Dispose**: Disabled
- **Lazy Loading**: Disabled
- **Pausable**: Yes
- **Attended**: No
- **User Interaction**: Required
- **Persistence Support**: No
- **Execution Type**: Workflow

## Getting Started

### Prerequisites
- UiPath Studio (Version 19.12.0 or compatible)
- .NET Framework (Legacy)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AishwaryaBhargava/Data-Scrapping-from-PDFs.git
   ```
2. Open the project in UiPath Studio
3. Ensure all required dependencies are installed
4. Build the project

### Usage
1. Open the project in UiPath Studio
2. Configure any necessary settings in the project.json file
3. Run the Main.xaml workflow

## Project Structure
- `Main.xaml`: Entry point of the automation
- `project.json`: Project configuration and dependencies

## Development Notes
- Project Profile: Development
- Output Type: Process
- Modern Behavior: Disabled

## Security
- Private data and passwords are excluded from logging
- Original XAML is not included in library output

## Contributing
Feel free to fork this repository and submit pull requests for any improvements.
