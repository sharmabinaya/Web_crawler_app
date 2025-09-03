### Web Crawler App

The **Web Crawler App** is a simple web application built with Python and Flask that allows you to crawl a given URL and extract all the text from the paragraph (`<p>`) tags on the page. It provides a straightforward interface for fetching and viewing content from any website.

#### Features

  * **URL Input:** A user-friendly form to input any valid URL.
  * **Paragraph Extraction:** Efficiently scrapes all paragraph text from the specified webpage.
  * **Error Handling:** Displays clear error messages if the URL is invalid or the fetching process fails.
  * **Lightweight Backend:** A simple Flask server to handle requests and manage the crawling process.

#### How to Run

Follow these steps to get the application up and running on your local machine.

**Prerequisites**

You need to have Python and `pip` installed.

**Installation**

1.  **Save the files:** Save the Python backend code as `app.py`. Create a new folder named `templates` in the same directory, and save the HTML frontend code inside it as `index.html`.
2.  **Install dependencies:** Open your terminal and install the required libraries using `pip`:
    ```bash
    pip install Flask requests beautifulsoup4
    ```

**Usage**

1.  **Run the application:** From your terminal, navigate to the directory where you saved `app.py` and run the following command:
    ```bash
    python app.py
    ```
2.  **Open in browser:** The app will start running on your local machine. Open your web browser and go to `http://127.0.0.1:5000`.
3.  **Crawl:** Enter a URL (e.g., `https://example.com`) into the input box and click the "Crawl" button to see the extracted paragraphs.
