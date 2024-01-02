# Simple Image Stack Generator

## Overview

The Simple Image Stack Generator is a web application that allows users to create visually appealing image stacks using the Pexels API. This repository contains the source code for the application.

## Getting Started

### Prerequisites

- **Local Web Server:** Download and install any local web server, such as XAMPP, from [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html).
- **Source Code:** Download the provided source code zip file from this repository.

### Pexels API Key

1. **Login or Register on Pexels:**
   - Visit [pexels.com](https://www.pexels.com/) and log in or register.
   - Click the user avatar icon in the navigation bar.
   - From the dropdown menu, select `Image and Video API`.
   - Click the `Your API Key` button to generate your API key.
   - Save the API key for later use.

### Setup Local Environment

1. **Start XAMPP:**
   - Open XAMPP Control Panel and start Apache.

2. **Extract and Copy Source Code:**
   - Extract the downloaded source code zip file.
   - Copy the extracted source code folder and paste it into XAMPP's "htdocs" directory.

3. **Configure Pexels API Key:**
   - Browse PHPMyAdmin in a browser (e.g., [http://localhost/phpmyadmin](http://localhost/phpmyadmin)).
   - Locate and open the `stackAPI.class.php` file with your preferred code editor.
   - Replace the `$this->apiKey` value with your Pexels API Key and save the file.

4. **Run the Application:**
   - Open a web browser and go to [http://localhost/stack_image_generator-main/](http://localhost/stack_image_generator-main/).

## Usage

- Visit the provided local URL to access the Simple Image Stack Generator.
- Follow the on-screen instructions to create image stacks using the Pexels API.

## Contributing

If you'd like to contribute to the development of this project, please follow our [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any inquiries or support, please contact the project maintainer:

- Email: [your.email@example.com](mailto:your.email@example.com)
- GitHub: [YourGitHubUsername](https://github.com/YourGitHubUsername)

Happy image stacking!
