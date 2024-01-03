# Personal Blog Platform

Welcome to the Personal Blog Platform, a user-friendly web application that allows individuals to share their personal blogs. This project features routes for "/about," "/contact," "/home," and provides access to individual blog posts through the "/posts/:titlename" route.

## Getting Started

Follow these steps to set up the Personal Blog Platform on your local machine:

1. Clone the repository:

   ` git clone https://github.com/desifighter/personal-blog-platform.git`
2. Navigate to the project directory:

   `cd personal-blog-platform`
3. Install dependencies:

   `npm install`
4. Set up your environment variables:

   * Create a `.env` file in the project root.
   * Add the following variables and replace the values with your MongoDB connection details:  `uri=your_mongo_db_uri PORT=3000`
5. Start the application:

The application will be accessible at [http://localhost:3000]().

## Dependencies

* **body-parser:** ^1.18.3
* **dotenv:** ^16.3.1
* **ejs:** ^2.6.1
* **express:** ^4.16.3
* **lodash:** ^4.17.11
* **mongoose:** ^8.0.2

## Usage

### Adding Personal Blog

1. Visit the "/" home route to view existing blog posts.
2. "Add new post" on "/compose" route .
3. Fill in the required details, including the title, content, and any additional information.
4. Click "Submit" to publish your blog post.

### Navigation

* **/:** View a list of all published blog posts.
* **/about:** Learn more about the author or the purpose of the blog.
* **/contact:** Reach out to the author through the provided contact form.
* **/posts/:titlename:** Access individual blog posts using the title name in the URL.

## Contributing

If you'd like to contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   `git checkout -b feature/new-feature`
3. Make your changes and commit them:

   `git commit -m "Add new feature"`
4. Push your changes to your fork:

   `git push origin feature/new-feature`
5. Open a pull request on the main repository.
