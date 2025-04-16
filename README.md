# Public-Cats-API-Testing

This repository contains a collection of API tests for various Cat APIs, such as **random cat facts**, **cat images**, and other cat-related services. The purpose of this project is to demonstrate how to interact with multiple Cat APIs using **Postman** and automate testing using **Newman**.

The collection includes a variety of API endpoints, allowing you to explore cat facts, fetch random cat images, adopt a cat, search for anime cat scenes, and retrieve cat-related data from Facebook.

---

## 🐱 APIs Tested

The following APIs are tested and included in the collection:

- **Cat Facts API**: Retrieve random cat facts or filter them based on animal type and the number of facts.
- **Cataas (Cat as a Service) API**: Fetch random cat images, and customize the images with text, filters, size adjustments, and color modifications.
- **Adopt A Pet API**: Retrieve a list of cats (and other pets) available for adoption.
- **Trace Moe API**: Identify anime scenes using an image URL (particularly useful for cat-related anime content).
- **Facebook Cat API**: Fetch cat-related data in JSON format from Facebook's API.

---

## 🔧 Features

- **Random Cat Facts**: Get random cat facts, or specify the number and type of facts (e.g., random or filtered).
- **Custom Cat Images**: Fetch customizable cat images with text overlays, adjustments to position, font size, and other image properties.
- **Adopt A Pet**: Retrieve available cats (and other animals) for adoption from the **Adopt A Pet** platform.
- **Anime Scene Search**: Use the **Trace Moe API** to search for anime scenes featuring cats (great for cat anime lovers).
- **Facebook Cat Data**: Fetch cat-related information in JSON format from Facebook's API.

---

## 🧑‍💻 Technologies Used

- **Postman**: A powerful tool used for creating, managing, and running API collections, and performing manual testing.
- **Newman**: A command-line companion for Postman that allows you to automate the execution of your Postman tests for **continuous integration**.
- **Node.js**: Required for installing and using **Newman** for running tests from the command line.

---

## 🚀 How to Run the Tests

### 1. Clone the Repository

Clone this repository to your local machine using Git:

```bash
git clone https://github.com/your-username/five-cats-api-testing.git
```

### 2. Install Postman (If Not Installed)

Download and install **Postman** from the [official website](https://www.postman.com/downloads/).

### 3. Import the Postman Collection

- Open **Postman**.
- Go to **File → Import**.
- Select the Postman collection file located in the **Postman_Collection** folder within the cloned repository.

### 4. Run the Tests in Postman

- Open the **Postman Runner** (located in the Postman app).
- Select the imported collection.
- Click **Run** to execute the tests.

### 5. Automate with Newman

To automate the tests with **Newman**, follow these steps:

1. **Install Newman** (if not already installed):

```bash
npm install -g newman
```

2. **Run the collection with Newman**:

```bash
newman run path_to_your_collection.json --reporters console,html,summary
```

This will execute the API tests and provide reports in **console**, **HTML**, and **summary** formats.

---

## 🛠️ Project Structure

```bash
/Public-Cats-API-Testing
├── /Postman_Collection         # Contains Postman collection files
├── /Newman_Reports             # Directory where Newman test reports are saved
├── /README.md                 # This file
└── /package.json               # Required for Newman installation
```

- **Postman_Collection**: Contains the Postman collection file for testing various Cat APIs.
- **Newman_Reports**: Directory where reports from Newman tests will be stored.
- **package.json**: Defines dependencies, including **Newman**.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, add new tests, or enhance the existing ones. If you'd like to contribute, follow these steps:

1. **Fork** the repository.
2. Create a **new branch** for your changes.
3. **Implement** your changes and **commit** them.
4. **Push** your changes to your fork.
5. Submit a **pull request** for review.

Please ensure that all tests are well-documented and organized.

---

## 📜 License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute the project as long as you retain the license.

---

### Conclusion

This **Public-Cats-API-Testing** repository is a fun and useful demonstration of how to interact with various **Cat APIs** and automate the testing process using **Postman** and **Newman**. It offers a great way to get started with API testing and automation while working with a variety of cat-related APIs. Whether you're looking to get random cat facts, images, or even adopt a cat, this project has you covered!

---
