Installation

To run the "News Aggregator" project on your computer, please follow the steps outlined below:

### 1. Clone the Repository from GitHub

1. Ensure that **Git** is installed on your computer. If not, it can be downloaded and installed from [git-scm.com](https://git-scm.com/).

2. Open **terminal** or **command prompt** on your operating system.

3. Navigate to the directory where you want to store the project. For example:

   ```bash
   cd ~/Documents/projects
   ```

4. Clone the repository by using one of the following commands:

   * If you have **GitHub CLI** installed, use:

     ```bash
     gh repo clone UntamedWW/NewsSearcher
     ```

   * Alternatively, if you are using Git, clone the repository with:

     ```bash
     git clone https://github.com/UntamedWW/NewsSearcher.git
     ```

   After executing this command, the repository will be cloned to a folder named `NewsSearcher`.

### 2. Run the Project

Once the repository is cloned:

1. Navigate to the folder containing the cloned repository:

   ```bash
   cd NewsSearcher
   ```

2. Open the `index.html` file in your preferred web browser. You can do this by double-clicking the file, which will open it in the default browser.

### 3. API Configuration

To allow the application to fetch data from an external API, you will need an **API key**. If you are using **NewsAPI** or another API provider, you must register on the respective platform and obtain your key.

* The API key must be added to the code in the appropriate place, for example:

  ```javascript
  const API_KEY = 'your_api_key';
  ```

Make sure to replace `'your_api_key'` with the actual key obtained from the API provider.

### 4. Application Functionality

Once the steps above are completed, the application will automatically fetch data from the API and display it on the webpage, depending on the selected categories or keywords. The project is **static**, meaning it does not require a local server to function correctly.

### 5. Optional Steps

If you wish to run a local server to test or develop the application further, you can use one of the following tools:

* **Live Server** in **Visual Studio Code** (extension).
* **Python HTTP Server**: To start a local server, open the terminal, navigate to the project directory, and run:

  ```bash
  python -m http.server
  ```

  Once the server is running, the application will be accessible at `http://localhost:8000`.

---

By following these steps, the project will be ready for use.
