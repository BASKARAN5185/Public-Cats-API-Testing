# Public-Cats-API-Testing
This repository contains a collection of API tests for various Cat APIs including random cat facts, cat images, and other cat-related services. The purpose of this project is to demonstrate how to interact with multiple Cat APIs using Postman and automate testing with Newman. The collection includes a variety of API endpoints.
Cats API Testing
This repository contains a collection of API tests for various Cat APIs including random cat facts, cat images, and other cat-related services. The purpose of this project is to demonstrate how to interact with multiple Cat APIs using Postman and automate testing with Newman. The collection includes a variety of API endpoints, including but not limited to:

Cat Facts API: Retrieve random cat facts, or filter them based on animal type and the number of facts.

Cataas (Cat as a Service) API: Fetch random cat images, customize the image with text, filters, and adjust image properties like size and color.

Adopt A Pet API: Access a list of pets available for adoption, including cats.

Trace Moe API: Identify anime scenes using an image URL (useful for cat-related anime content).

Facebook Cat API: Get cat-related data in JSON format from Facebook.

Features:
Random Cat Facts: Get random cat facts or fetch a specific number of facts filtered by animal type.

Custom Cat Images: Fetch cat images with customizable text, position, font size, and more.

Adopt A Pet: Retrieve pet listings from the Adopt A Pet website.

Anime Scene Search: Search for anime scenes with the Trace Moe API, identify cat-related anime scenes.

Facebook Cat Data: Fetch cat-related data in JSON format from Facebook's API.

Technologies:
Postman: Used to create and manage API collections and run tests.

Newman: Used to automate the testing process for continuous integration.

APIs Tested:

Cat-Fact API

Cataas API

Adopt A Pet API

Trace Moe API

Facebook Cat API

How to Run the Tests:
Clone the repository:

bash
Copy
git clone https://github.com/your-username/five-cats-api-testing.git
Install Postman (if not installed):

Download and install from Postman.

Import the Postman collection:

Open Postman, go to File → Import and select the collection from the Postman_Collection folder in the cloned repository.

Run the tests in Postman:

Open the Postman Runner and select the collection. Click Run to execute the tests.

Automate with Newman:

First, install Newman (if not installed):

bash
Copy
npm install -g newman
Run the collection in Newman:

bash
Copy
newman run path_to_your_collection.json --reporters console,html,summary
Contributing:
Feel free to fork this repository and submit pull requests to improve the collection, add new tests, or contribute other useful resources. Please ensure that tests are well-organized and thoroughly documented.
