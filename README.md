# Plug-It-In
v0.0.2 - A template for creating new Wordpress plugins using PHP, React, Webpack, and other technologies.


![](./cover.jpg)

## Technologies Used
- PHP
- React
- Webpack

## Directories
- `build-utils`: Contains webpack configuration files for development and production builds.
- `dist`: Contains the compiled assets and files for the plugin.
- `inc`: Contains the PHP classes used for the plugin.
- `node_modules`: Contains the dependencies required for the project.
- `src`: Contains the source code for the plugin.

## Getting Started
1. Clone the repository to your local machine.
2. Install the dependencies by running `npm install` in the root directory of the project.
3. Compile the assets by running `npm run build`.
4. Upload the `plug-it-in` directory to your Wordpress installation's `wp-content/plugins` directory.
5. Activate the plugin in your Wordpress administration panel.

## Building for Production
To compile the assets for production, run `npm run build`. The compiled assets will be located in the `dist` directory.

## Contributing
We welcome contributions to the project. Please fork the repository and open a pull request with your changes.

## License
The code in this repository is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Change Log
0.0.2
- Update read me to better understand use-case for repo

0.0.1
- Initial Release